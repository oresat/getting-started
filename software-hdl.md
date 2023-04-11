flowchart BT
    subgraph OreSat
    subgraph OreSat0
        s_id0(Controller)
        s_id1(Chip)
        s_id2(Chip)
        s_id0-->|CAN Bus| s_id1
        s_id0-->|CAN Bus| s_id2
    end
    subgraph OreSat1.5
        s_id3(Controller)
        s_id4(Chip)
        s_id5(Chip)
        s_id6(Chip)
        s_id3-->|CAN Bus| s_id4
        s_id3-->|CAN Bus| s_id5
        s_id3-->|CAN Bus| s_id6
    end
    end

    subgraph GroundStation
    subgraph id_sg_1 [container]
    id1(YAMCs)
    end
    subgraph idsg_2 [container]
    id2(YAMCs)
    end
    subgraph idsg_3 [container]
    id3(YAMCs)
    end
    end

    id1-->|EDL| s_id0
    s_id0-->|EDL| id1

    id2-->|EDL| s_id3
    s_id3-->|EDL| id2

    OreSat-->|EDL| GroundStation

    OreSat-->|StatusUpdates| GroundStation


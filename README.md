# Getting Started on OreSat

**OreSat** is Oregon's first satellite! It's a state-wide educational CubeSat project being run out of Portland State University, along with many of Oregon's other educational institutions including University of Oregon and Oregon State University.

Designing, building, and testing CubeSats isn't easy, but OMG we're going to space. So get involved! Even if you're not involved with PSU at all, we could use your help!

Please email <oresat@pdx.edu> if you have any questions about ramping up or getting involved!

## Part One: The Basics!

- Read the [Wikipedia page on Cubesats]. This is a surprisingly good summary of CubeSats. OreSat0, Oregon's first satellite, is a 1U CubeSat, and OreSat0.5 and OreSat1 are a 2U CubeSats.
- Read a bit about the [NASA CubeSat Launch Initiative (CSLI)], which is the program we applied to in 2016 to get launched by NASA through the [Educational Launch of Nanosatellites (ELaNa)](https://science.nasa.gov/category/missions/small-satellite-missions/elana/) initiative.
- Skim over NASA's [CubeSat 101] document. This is a _great_ but very detailed introduction to CubeSats. Later, you should come back and read this in full.
- Skim over the [CubeSat Design specification (CDS)]. As we design OreSat, we'll constantly refer to this design spec.

## Part Two: OreSat!

- It's _really_ out of date now, but please skim the [OreSat 2016 CubeSat Launch Initiative proposal]. Ignore all the technology descriptions and timeline; those are all out of date. Ignore the CFC description, that _way_ out of date. Read mostly for the overview of what we promised OreSat would do, and why we're doing this.
- Watch this 20 minute video from the 2021 open Source CubeSat Workshop on the [technical overview](https://www.youtube.com/watch?v=f-3HAv4VBUc) of OreSat. Do NOT worry if you don't understand everything, just get the jist of the OreSat architecture and all its various parts.
- Look over the [OreSat Block Diagram](https://drive.google.com/file/d/1crq5eg1g2U3-BLZJRUnqu_Eka9oKfZFJ/view?usp=sharing). It'll raise more questions than it answers, but you'll get a sense for how much _stuff_ is crammed in our CubeSats.

## Part Three: Onboarding!

As an open source organization, our collaboration tools really define how we operate. Everyone, regardless of discipline, should:

- Email <oresat+join@pdx.edu> and ask to get involved. You'll be sent a Google Form to fill out, where we'll ask you how you heard about us and you'll have to agree to our open source IP and community policies.
- We use Slack to communicate: make sure to download Slack and bug us to get you on Slack if we haven't already.
- We use a shared Google Drive for most of OreSat's internal documentation. Bug us to share the drive with you if we haven't already.
- We use Git and GitHub. Make yourself a GitHub login, ask to join the [OreSat GitHub organization], and become familiar with Git.

If you're doing technical work for OreSat, you have more homework to do:

### Mechanical Engineers

- Subscribe to all of the mechanical-y Slack channels, like #oresat-structure and #psas-onshape
- If you're interested in Thermal, subscribe to #oresat-thermal and we'll tell you how to install CRT's Thermal Desktop.
- We use [Onshape CAD](https://www.onshape.com/) for mechanical CAD. It's not perfect, but it fits our needs super well. Ask if you want to know why we use it instead of SolidWorks.
- Start attending the mechanical team meetings, which are usually Sundays at 10:00am!
- Finally, we have some great videos to watch:
    - Watch this 20 minute video from the 2021 open Source CubeSat Workshop on the [OreSat Mechanical Design](https://youtu.be/0-Tlg6fqUgA?t=25) by Marvin!
    - [CAD with Hayden](https://www.youtube.com/watch?v=OYUZ3eE1vc8): A walk through of the Summer 2022 work by Hayden (and Zach!) on moving OreSat CAD from SolidWorks to OnShape. 
    - [CAD with Catie Series](https://www.youtube.com/watch?v=Bzgoayj21Vc) - it's old, but goes through everything on Oresat from back in 2020.

### Electrical Engineers

- Subscribe to all the electrical-y Slack channels, like #oresat-bus, #oresat-comms, etc.
- Install [KiCAD](https://www.kicad.org/). Note that we're using the latest KiCad stable build. Ramping up on KiCAD is a great first step for all things Oresat.
- Get to know [Git](https://git-scm.com/) and [Github](https://github.com/).
- Clone the electrical system repos (batteries, solar, C3, etc) that seem interesting from our [OreSat GitHub] to get all of our current designs.
   - Eventually let one of our admins know you're ready to contibute and we'll add you to the Github organization so you can push.
- Start attending the electrical team meetings, which are usually Sunday noon!
- If you can stand it, watch [Andrew's OreSat technical overview](https://www.youtube.com/watch?v=L4ZFTi2mGLw) to BroncoSpace in Spring 2024.
- Watch this 20 minute video from the 2021 open Source CubeSat Workshop on [OreSat Electrical Power System](https://youtu.be/n3-lD2CVcbM?t=16) by David!


### Computer Engineers (Firmware)

- Subscribe to all the firmware-y Slack channels, like #oresat-firmware, #oresat-software, and #oresat-bus.
- You'll need a Linux install (either on your laptop, in VM, or in WSL).
- Note that we're using the latest KiCad stable build. Ramping up on KiCAD is a great first step for all things Oresat.
- Clone #oresat-firmware in the [OreSat GitHub organization] and follow the README instructions to download tools and get set up for writing firmware!
- See [Getting Started in firmware](https://github.com/oresat/oresat-firmware).
- Start attending the firmware team meetings, which are usually Sundays at 2:00pm!
- Watch this 20 minute video from the 2021 open Source CubeSat Workshop on [OreSat Firmware and Software Architecture](https://youtu.be/rwz4FqyghRo?t=21)
- If you're interested in communications and ground station design, watch this 20 minute video from the 2021 open Source CubeSat Workshop on [OreSat Communication Protocols and Ground Stations](https://www.youtube.com/watch?v=mC4On8ECt2E).

### Computer Science Majors (Software)

- Subscribe to all the software-y Slack channels, like #oresat-software, #oresat-testing, #oresat-uniclogs, etc.
- You'll need a Linux install (either on your laptop or in a VM).
- Software has a lot of repos!
  - Generally all embedded OreSat Linux repo names follow the _oresat-linux\*_ or the _oresat-\*-software_ pattern.
  - All UniClOGS (our ground station) repos names follow the _uniclogs-\*_ pattern.
  - Support project repo(s): [SavvyCAN](https://github.com/collin80/SavvyCAN)
- We try to make use of GitHub Issue for all software repos, so check out the Issues tab in all the software repos. The general rule is if no one is assigned to the Issue, no one is working on it.
- Start attending the software team meetings, which are usually Sundays at 4:00pm!
- Watch this 20 minute video from the 2021 open Source CubeSat Workshop on [OreSat Firmware and Software Architecture](https://youtu.be/rwz4FqyghRo?t=21)
- If you're interested in communications and ground station design, watch this 20 minute video from the 2021 open Source CubeSat Workshop on [OreSat Communication Protocols and Ground Stations](https://www.youtube.com/watch?v=mC4On8ECt2E).
- Please read through the [software intern onboarding guide](https://github.com/oresat/oresat-software-docs)!

## Part Four: Getting Involved!

There are a _lot_ of things to be done for OreSat. They range from the technical (thermal simulations, board layout, RF communications, embedded Linux, firmware, machining, solar power systems, space deployables, radiation hardening, etc) to the day-to-day (fund-raising, project management, etc). 

- We meet weekly at PSU - please see the [Portland State Aerospace Society's Google Calendar] for our current meeting times and locations. Usually OreSat meets Fridays from 2:00pm - 3:00pm in PSU's Engineering Building in room 91. We also meet online using zoom; email us for the link!
- All of our designs are open source, and located at <http://github.com/oresat>. Go take a gander and see what's there.
- All of our shared documents that aren't on GitHub are in Google Drive. They're mostly logistical in nature. Once you start volunteering with us, we'll share that folder with you.

Otherwise, contact us at `oresat@pdx.edu` in order to learn about what's going on and how to get involved!


<!-- External Links -->
[Wikipedia page on Cubesats]:https://en.wikipedia.org/wiki/CubeSat
[NASA CubeSat Launch Initiative (CSLI)]:http://www.nasa.gov/directorates/heo/home/CubeSats_initiative
[Educational Launch of Nanosatellites (ELaNa)]:http://www.nasa.gov/mission_pages/smallsats/elana/index.html
[CubeSat 101]:https://www.nasa.gov/sites/default/files/atoms/files/nasa_csli_cubesat_101_508.pdf
[CubeSat Design specification (CDS)]:https://static1.squarespace.com/static/5418c831e4b0fa4ecac1bacd/t/56e9b62337013b6c063a655a/1458157095454/cds_rev13_final2.pdf

<!-- Tool Links -->
[KiCAD]:https://www.kicad.org/
[OnShape]: 
[SolidWorks]:https://www.solidworks.com/

<!-- GitHub Links -->
[OreSat GitHub organization]:https://github.com/oresat/
[OreSat Structure repo]:https://github.com/oresat/oresat-structure
[CANopen-monitor]:https://github.com/oresat/CANopen-monitor

<!-- OreSat Links -->
[Portland State Aerospace Society's Google Calendar]:http://psas.pdx.edu/join/
[OreSat Block Diagram]:https://github.com/oresat/oresat.github.io/blob/master/pub/OreSat_CS0_Block_Diagram.pdf
[OreSat 2016 CubeSat Launch Initiative proposal]:http://oresat.github.io/mission/oresat-2016-csli-application-r6-PUBLIC.pdf
[walkthrough]:https://www.youtube.com/watch?v=Bzgoayj21Vc&list=PLErHfvfxHlH09auH2yG9p9x0MbHu5K8v4
[Wiki]:https://github.com/oresat/oresat-structure/wiki

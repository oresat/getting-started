# Getting Started on OreSat

**OreSat** is Oregon's first satellite! It's a state-wide educational CubeSat project being run out of Portland State University, along with many of Oregon's other educational institutions including University of Oregon and Oregon State University.

Designing, building, and testing CubeSats isn't easy, but OMG we're going to space. So get involved! Even if you're not involved with PSU at all, we could use your help!

Please email <oresat@pdx.edu> if you have any questions about ramping up or getting involved!

## Part One: The Basics!

- Read the [Wikipedia page on Cubesats]. This is a surprisingly good summary of CubeSats. OreSat0 is a 1U CubeSat, and OreSat is a 2U CubeSat.
- Read a bit about the [NASA CubeSat Launch Initiative (CSLI)], which is the program we applied to in 2016 to get launched by NASA through the [Educational Launch of Nanosatellites (ELaNa)](http://www.nasa.gov/mission_pages/smallsats/elana/index.html) initiative.
- Skim over NASA's [CubeSat 101] document. This is a _great_ but very detailed introduction to CubeSats. Later, you should come back and read this in full.
- Skim over the [CubeSat Design specification (CDS)]. As we design OreSat, we'll constantly refer to this design spec.

## Part Two: OreSat!

- It's _really_ out of date now, but please do read the [OreSat 2016 CubeSat Launch Initiative proposal]. Ignore all the technology descriptions and timeline; those are all out of date. Ignore the CFC description, that _way_ out of date. Read mostly for the overview of what we promised OreSat would do.
- Look over the [OreSat Block Diagram]. It'll raise more questions than it answers, but you'll get a sense for how much _stuff_ is crammed in our CubeSats.

## Part Three: Onboarding!

As an open source organization, our collaboration tools really define how we operate. Everyone, regardless of discipline, should:

- Email <oresat+join@pdx.edu> and ask to get involved. You'll be sent a Google Form to fill out, where we'll ask you how you heard about us and you'll have to agree to our open source IP and community policies.
- We use Slack to communicate: make sure to download Slack and bug us to get you on Slack if we haven't already.
- We use a shared Google Drive for most of OreSat's internal documentation. Bug us to share the drive with you if we haven't already.
- We use Git and GitHub. Make yourself a GitHub login, ask to join the [OreSat GitHub organization], and become familiar with Git.

If you're doing technical work for OreSat, you have more homework to do:

### Mechanical Engineers

- Subscribe to all of the mechanical-y Slack channels, like #oresat-structure.
- Install [SolidWorks]. If you can't get a student license, bug us on Slack and we'll get you one.
- Please clone (NOT fork!) the [OreSat Structure repo] and begin playing around with SolidWorks. 
- If you're interested in Thermal, subscribe to #oresat-thermal and we'll tell you how to install CRT's Thermal Desktop.
- Start attending the mechanical team meetings, which are usually Sunday 10:00am!

### Electrical Engineers

- Subscribe to all the electrical-y Slack channels, like #oresat-bus, #oresat-comms, etc.
- Install [KiCAD]. Note that we're using the "nightly" build (v5.99), not the stable. If you've never used it, that's fine, start using it! Ramping up on KiCAD is a great first step for all things Oresat.
- Clone the electrical system repos (batteries, solar, C3, etc) in the [OreSat GitHub organization] to get all of our current designs.
- Start attending the electrical team meetings, which are usually Sunday noon!

### Computer Engineers (Firmware)

- Subscribe to all the firmware-y Slack channels, like #oresat-firmware, #oresat-software, and #oresat-bus.
- You'll need a Linux install (either on your laptop or in a VM).
- Clone #oresat-firmware in the [OreSat GitHub organization] and follow the README instructions to download tools and get set up for writing firmware!
- Start attending the firmware team meetings, which are usually Fridays at 5:30pm!

### CS Majors (Software)

- Subscribe to all the software-y Slack channels, like #oresat-software, #oresat-server, etc.
- You'll need a Linux install (either on your laptop or in a VM).
- Clone #oresat-software and all of the other repos you need in the [OreSat GitHub organization].
- Start attending the software team meetings, which are usually Tuesdays at 4:30pm!


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
[SolidWorks]:https://www.solidworks.com/

<!-- GitHub Links -->
[OreSat GitHub organization]:https://github.com/oresat/
[OreSat Structure repo]:https://github.com/oresat/oresat-structure

<!-- OreSat Links -->
[Portland State Aerospace Society's Google Calendar]:http://psas.pdx.edu/join/
[OreSat Block Diagram]:https://github.com/oresat/oresat.github.io/blob/master/pub/OreSat_CS0_Block_Diagram.pdf
[OreSat 2016 CubeSat Launch Initiative proposal]:http://oresat.github.io/mission/oresat-2016-csli-application-r6-PUBLIC.pdf

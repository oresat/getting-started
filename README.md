# Getting Started on OreSat

**OreSat** is Oregon's first satellite! It's a state-wide educational CubeSat project being run out of Portland State University, along with many of Oregon's other educational institutions including University of Oregon and Oregon State University.

Designing, building, and testing CubeSats isn't easy, but OMG we're going to space. So get involved! Even if you're not involved with PSU at all, we could use your help!

Please email <oresat@pdx.edu> if you have any questions about ramping up or getting involved!

## Part One: The Basics!

- Read the [Wikipedia page on Cubesats](https://en.wikipedia.org/wiki/CubeSat). This is a surprisingly good summary of CubeSats. OreSat0 is a 1U CubeSat, and OreSat is a 2U CubeSat.
- Understand the [NASA CubeSat Launch Initiative (CSLI)](http://www.nasa.gov/directorates/heo/home/CubeSats_initiative) is the program we applied to  for in order to get launched by NASA through the [Educational Launch of Nanosatellites (ELaNa)](http://www.nasa.gov/mission_pages/smallsats/elana/index.html) initiative.
- Skim over NASA's [CubeSat 101](https://www.nasa.gov/sites/default/files/atoms/files/nasa_csli_cubesat_101_508.pdf) document. This is a _great_ but very detailed introduction to CubeSats. Later, you should come back and read this in full.
- Mechanical Engineers: Read the [CubeSat Design specification (CDS)](https://static1.squarespace.com/static/5418c831e4b0fa4ecac1bacd/t/56e9b62337013b6c063a655a/1458157095454/cds_rev13_final2.pdf). As we design OreSat, we'll constantly refer to this design spec so understanding it deeply is a good idea.
- Mechanical Engineers:  Read the [NanoRacks Interface Definition Document (IDD)](https://nanoracks.com/wp-content/uploads/NR-NRCSD-S0003-Rev-NanoRacks-CubeSat-Deployer-IDD-Copyright-Stamped.pdf). Nanoracks is most likely going to be our launch provider, so this is their version of the CDS. 

## Part Two: OreSat!

- It's _really_ out of date now, but do read the [OreSat 2016 CubeSat Launch Initiative proposal](http://oresat.org/mission/oresat-2016-csli-application-r6-PUBLIC.pdf). Ignore all the technology bits and timeline; read mostly for the overview of what we promised OreSat would do.
- Look over the [OreSat Block Diagram](https://github.com/oresat/oresat.github.io/blob/master/pub/OreSat_CS0_Block_Diagram.pdf). It'll raise more questions than it answers, but you'll get a sense for how much _stuff_ is crammed in our little 2U CubeSat.

## Part Three: Tools!

- We use Slack to communicate. Get yourself on PSAS' slack channel by emailing <oresat+join@pdx.edu>.
- We use Git and Github. Make yourself a Github login, ask to join the OreSat organization, and become familiar with Git.
- MEs please install [SolidWorks](https://www.solidworks.com/). 
   - Please clone (NOT fork!) the [OreSat Structure repo](https://github.com/oresat/oresat-structure) and begin playing around with SolidWorks. ME thermal tools also include Thermal Desktop and ANSYS.
- EEs please install [EAGLE CAD](https://www.autodesk.com/products/eagle/overview). EE RF tools also include HFSS.
   - Please clone any of the electrical repos in the [OreSat organization](https://github.com/oresat/) to get started.

## Part Four: Space!

Fourth, you should know some things about the space environment:

- https://en.wikipedia.org/wiki/Radiation_hardening
- https://en.wikipedia.org/wiki/Outgassing
   - https://en.wikipedia.org/wiki/Materials_for_use_in_vacuum
   
- [Bryan Klofas](https://www.klofas.com/papers/) a ground station engineer from [Planet Labs](https://www.planet.com/) wrote two papers discussing communications systems used on CubeSat missions which also touch on mission details and some of the failures experienced.
   - [Missions from the 1999 beginnings to 2008](https://www.klofas.com/papers/CommSurvey-Bryan_Klofas.pdf)
   - [Missions from 2009 to 2012](https://www.klofas.com/papers/Klofas_Communications_Survey_2009-2012.pdf)
- _TODO: more links here on the space environment, specifically thermal and power_

## Part Five: Getting Involved!

There are a _lot_ of things to be done for OreSat. They range from the technical (thermal simulations, board layout, RF communications, embedded Linux, firmware, machining, solar power systems, space deployables, radiation hardening, etc) to the day-to-day (fund-raising, project management, etc). 

- We meet weekly at PSU - please see the [Portland State Aerospace Society's Google Calendar](http://psas.pdx.edu/join/) for our current meeting times and locations. Usually OreSat meets Fridays from 2:00pm - 3:00pm in PSU's Engineering Building in room 91. We also meet online using zoom; email us for the link!
- All of our designs are open source, and located at <http://github.com/oresat>. Go take a gander and see what's there.
- All of our shared documents that aren't on Github are in Google Drive. They're mostly logistical in nature. Once you start volunteering with us, we'll share that folder with you.

Otherwise, contact us at `oresat@pdx.edu` in order to learn about what's going on and how to get involved!

# Alejandro's Meeting Minutes
**GDP_2425 | Alejandro Parra Pintado**

This README markdown document contains my meeting minutes for each of our meetings. If I am unable to attend a meeting then I will add someone else from this group's minutes.

**More recent minutes appear closer to the top of this document (i.e. ascending chronological order).**

**SM = Supervised Meeting (i.e. a meeting with Ara and/or Gary).**
<br>
**UM = Unsupervised Meeting (i.e. a meeting whithout supervisors).**

## SM Monday 14th October 2024
Vicky is absent due to an appointment

* We are GDP group 1!
* We have a week 4 or week 5 presentation on Friday where we will have to review our work with our examiner.
    * All of us should be available.
    * 10 minutes per person.
    * We have a lecture on the GDP this Wednesday were we should be given some info about the GDP review.
* Andrew Hamilton is going to give us a talk about stakeholders of our project at some point.
* Ara mentions again Open-Source options.
* Because we are not collecting personal information we should be able to call to ask for customer research insights.
* Ara clue: Prusa 3.5 and above versions have a pressure sensor in the nozzle that is used for self-calibration of the printer -> Because prusa's have open source sofware we could perhaps use this for defect detection.
* Mark scheme is of course the most important part of the GDP guidelines.
* Ara mentions once again making this system compatible with other types of printers (SLA, metal, etc.).
* Make a requirements list/table, to guide all of our decissions.
* One of the problems with a requirements table is that they focus a lot on the technical aspects, so make sure that we incorporate the good things about the design description (e.g. ergonomics, ethics etc).
* We can add our own templates and slides for how we choose to do things.
* If the whole system works and we prove that it works then we are in a good place.
* Remember that this is an iterative project and the final solution may not really be the final one.

**TO DO**
* Meeting with A.Toth on Wednesday.
    * Power requirements (sockets for printers and laptops!).
    * Make sure that storage is secure.
* Send team NASA document about how to make a good requirements document.
* A Gantt Chart has to be done by next Monday
    * Gantt Chart is a living document and can change, so change it in the future whenever the need arises.
    * It should be our own group's plan.
    * Account for extra time in our Gantt chart since some processes could be affected by setbacks.
    * Do not get stuck! Keep the ball rolling.
    * Manufacturing and testing is the part that often goes wrong.
    * Give time for additional iteration after the final solution has been developed.
* For deciding our project roles keep the hierarchy as flat as possible.
* Tim wants to be in charge of the Gantt Chart.

## UM Friday 11th October 2024
Vicky and Ben late

* Octoprint.
    * Obico
        * Free for 1 printer but have to pay if you want them to host a server for pritners.
        * Open source!
* Live monitoring defect detection -> A.I.
        * Light changes affect this process.
* Automated planning -> humans make suboptimal decissions.
* Formlabs.
    * SLA solution.
    * Only runs G-code.
* 3DQue.
    * Central hub to which printers are attached.
    * Centralised file storage.
    * Statistics on performance.
    * 40 pounds a month.
* SimplyPrint
    * 3D printing farm for free.
    * Bed levelling.
    * Graphing and statistics.
    * In-built slicer.
    * Material management system.
* Marking scheme has to guide our work.

## SM Monday 7th October 2024
* Briefing slides help with assessment criteria.
    * This document is our "Bible".

* Follow the Design Process (Double Diamond Diagram)
    * Discover -> Define -> Develop -> Deliver

* Justify all design decissions. 
    * Reference the Requirements
    
* Note how marking credits the different aspects of this project.
    * 50% of assessment is process.
    * 25% is communication.
    * 25% is innovation.

* Environmental, economical, ethical and other human aspects of this project must be adressed.

* READ THE GUDELINE REQUIREMENTS.

* For GDP budget you often pay for material.
    * We may need to do a health and risk assessment.

*   Find people and ask what they want.

*   If we ask stakeholders we need to make sure our research ethics are correct.

* Gary would like for us to contact externals but we need confirmation from him.
    * Don't look just at the UK, look at a wider or more global market.

*   Google scholar for research.
    * Bachelor's thesis from Finland documents a very similar project.

*   Ara wants us to use 3D experience.
    * He will send us invites to the license.
    * 3D experience can be linked to SolidWorks like a github but for CAD -> browser based but for it to work we need to download something.


THE DAY-1 SPECIFICATION

* Make system where we link printers together.
    * Send orders to the system.
    * System is able to assign tasks to printers including slicing and pre-printing tasks + turning on printers and checks.
    * KEY IS AUTOMATION.
        * Including Troubleshooting.
            * Someone should not need to go into do troubleshooting.
            * If printer misprints it must be able to tell how.
    * Make system expandable to other printers which may or may not be Prusa printers.
    * Develop something that is both hardware and software.
    * Find who our stakeholders/customers are (e.g. Factories, small businesses, universities, R&D).
    * Identify which points of a submitted print might fail and which ones are unlikely to fail.
    * Make this system as safe as possible.
    * Make system as easy and intuitive to use as possible.

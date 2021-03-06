---
layout: page
title: Program
---

* __Start:__ Monday 15<sup>th</sup> February 2021
* __Finish:__ Friday 19<sup>th</sup> February 2021

The two main topics these GAP Days will tackle are:

**GAP Release Process**
and 
**Release and CI tools used in GAP**


Please note the resources that need to be obtained **BEFORE** the workshop are
laid out on [the preparation page]({{ site.baseurl }}/preparation). This note
will also be updated as the workshop nears with more information and details
about the various work packages.

All scheduled talks are going to be held in [BigBlueButton](https://bbb.rlp.net/b/hor-foe-hdv-ahz).
The room code will be sent to participants.

For **gather.town** all participants have been sent the passwords for the rooms.

## Schedule
The tentative schedule is as follows; note that **all time are UTC** (so e.g. our German visitors should add 1 hour)
- **Monday, 15th February 2021** GitHub & GAP-Julia Day
  - 9:00: **Opening of GAPDays**  Welcome and setup
  - 9:10 -- 10:10 GitHub Actions 
    - *"An introduction to GitHub Actions"* (Wilf Wilson)
      ([Slides]({{ site.baseurl }}/slides/wilf-wilson.pdf))
    - *"Doing GAP package CI with GitHub Actions"* (Sergio Siccha)
      ([Slides](https://ssiccha.github.io/21-gapdays-gap-actions/))
  - 10:20 -- 11:20 Profiling and Code Coverage in GAP
    - *"Profiling GAP code"* (Chris Jefferson)
    - *"Code coverage tracking with [Codecov](https://codecov.io)"* (Max Horn)
  - 11:30 -- 12:30 GAP-Julia
    - *"An introduction to [OSCAR](https://oscar.computeralgebra.de) with a focus on the GAP-Julia integration"* (Max Horn)
    - *"The GAP package SingerAlg -- using the GAP-Julia integration"* (Thomas Breuer) ([More information and slides](http://www.math.rwth-aachen.de/~Thomas.Breuer/gapdays2021/))
  - 12:30 -- 14:00 Lunch time and offline exercise time
  - 14:00 -- 16:00 Hands-on, discussions etc for all Github, Codecov and GAP-Julia related exercises and questions. [In gather.town](https://gather.town/app/VH8AqAKh79qp1cdJ/gapdaysHandsOn)
- **Tuesday, 16th February 2021**  GAP Release discussion Day
  - 10:00: Discussion of release process and making a plan for the rest of the week.
  - 12:15: Talk: *"How a GAP release is made"* (Alexander Konovalov)<br>
           This will help participants understand the current processes, with an emphasis
           on steps that are essential and need to be ported to the new release system.
- **Wednesday, 17th February 2021** Work on release process
  - 9:00: Discussions and plan for the day -- Standup style in [gather.town](https://gather.town/app/nVLGg495C43fTrka/GAPDaysWorkspace)
  - 16:00: End of Day standup in [gather.town](https://gather.town/app/nVLGg495C43fTrka/GAPDaysWorkspace)
- **Thursday, 18th February 2021** Work on release process
  - 9:00: Discussions and plan for the day -- Standup style in [gather.town](https://gather.town/app/nVLGg495C43fTrka/GAPDaysWorkspace)
  - 16:00: End of Day standup in [gather.town](https://gather.town/app/nVLGg495C43fTrka/GAPDaysWorkspace)
  - 19:00(ish) Virtual Pub (in [gather.town](https://gather.town/app/KgZHhZP9v7IHMYDX/gapdayspub), participants were sent password.)
- **Friday, 19th February 2021** Finalising work on release process, and release a new version of GAP using that system.
  - 9:00: Discussions and plan for the day -- Standup style in [gather.town](https://gather.town/app/nVLGg495C43fTrka/GAPDaysWorkspace)
  - 16:00(ish): End of GAP Days wrap up in [gather.town](https://gather.town/app/nVLGg495C43fTrka/GAPDaysWorkspace)

<!-- 
We will have the introductory talks to the various workpackages on Monday and Tuesday, overall the video conference will be running throughout the conference and any check-ins will be done through it or via slack.
To avoid major conflicts and uncontrolled merges we ask for hourly commits/pushes and exchanges (also we are human, we can talk to each other).
The official end of these GAP Days will be around 3pm on Friday (but for the hardcore GAPers you are welcome to stick around for longer). 
This schedule is very flexible as it is highly dependent on the work progress, and any issues that might come up. 
Thus in the "work" slots, there is freedom for impromptu discussions, talks or other formats of communication.
Please note that for the peace of mind, you can set up side-calls with jitsi to take some subdiscussions away from the main call.

The overall idea for the progress throughout the week will for everyone to start off with an overhaul of the webpage infrastructure, before splitting into separate groups working on the webpage and release management. 
This is done so that the cross-over of some of the release mechanisms that involve the webpage (version number, package management etc.) are dealt with hand in hand.

Note that we have removed "fixed" meal times.

**ALL TIMES PROVIDED ARE GMT!!!**
- **Monday, 23rd March 2020** Webpage infrastructure day
  - 9:30: **Opening of the GAP Days**
  - 9:31: Organising everyone with a decent jitsi setup
  - 10:00: Talks and discussion of what needs doing and where additional resources are
    - 10:00: Max Horn "GAP Webpage Infrastructure Overhaul" [(slides)]({{ site.baseurl }}/slides/Horn-Webpage-Infrastructure.pdf)
    - 10:30: Ruth Hoffmann "GAP Webpage Content and Design" [(slides)]({{ site.baseurl }}/slides/Hoffmann-Webpage-Contents.pdf)
  - 16:30(ish): End of Day

- **Tuesday, 24th March 2020** Intertwine Release Management into Webpage
  - 09:30: Talks
    - 09:30: Alex Konovalov "GAP Release Process"
    - 10:00: Alex Konovalov "GAP Package Management"
    - 10:30: Chris Jefferson "Why Windows is Special"
  - 11:00: Discussion over "Ideal Release Management" [HackMD Note](https://hackmd.io/@rIiSpwN0QGCbqBK0N6bl5Q/SJHzYQar8)
  - 12:00: Work
  - 16:00: Touch base via jitsi
  - 16:30: EoD

- **Wednesday, 25th March 2020** Independent work on release management and webpage
  - 09:30: Discussions and plan for the day
  - 10:00: Work
  - 16:00: Touch base via jitsi
  - 16:30: EoD

- **Thursday, 26th March 2020** Independent work on release management and webpage
  - 09:30: Discussions and plan for the day
  - 10:00: Work
  - 15:30: Standup talks from anyone who has an unfinished work packages
  - 16:30: EoD

- **Friday, 27th March 2020** Discussion of release of work
  - 09:30: Discuss timeline or release/merge/integrate the work achieved
  - 11:00: Work on unfinished work packages
  - 13:00: Release?
  - 15:00: **End of GAP Days Spring 2020** 
  -->

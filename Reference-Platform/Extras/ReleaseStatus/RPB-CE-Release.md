---
layout: container-breadcrumb
title: CE Reference Platform Release Status
permalink: /reference-platform/extras/release-status/rpb-ce-release/
---

### CE Release Schedule

| Date          | Checkpoint |
| ------------- | ------------- |
| 2016-07-04    | New release cycle starting      |
| 2016-07-18    | Release goals proposal deadline |
| 2016-0x-xx    | Alpha                           |
| 2016-0x-xx    | Beta                            |
| 2016-0x-xx    | RC                              |
| 2016-0x-xx    | Final freeze                    |
| 2016-09-xx    | Release                         |

**TBA:**
* upstream projects key dates and events
  * v4.8 kernel predictions: merge window closes on 2016-08-07 and release on 2016-09-25 
  * Linaro Connect Las Vegas, from 2016-09-26 to 2016-09-30
  * OP-TEE 2.2.0, around 2016-10-15
* QA checkpoints
  * Alpha: feature complete, no blocker bugs
  * Beta: code freeze, no blocker bugs, no critical bugs (only bugfixes are accepted after this point)
  * RC: no critical bugs, possibly no major bugs

### CE Release Goals

This section lists the current release goals for CE Reference Platform 16.09 and additional candidates which may become a release goal in the future.

The criteria for release goals are described below:
* SMART (Specific, Measurable, Attainable, Realistic, Timely)
* Have an 'advocate/owner', who can track and keep status of progress
* Be generally consensual

The template to propose entries is describerd below:
```
* **Summary:** one-liner summary
* **Description:** one-liner short description with more info
* **Advocate/Owner:** Firstname Lastname, ...
* **State:** {proposed,accepted,rejected,completed}
* **Bug(s):** https://...
```

Note: if it's relevant, add tags in the summary. e.g. [Debian] [OE]

#### Proposed Goals
* **Summary:** Auotomated UI testing covered with Robot Framework
* **Description:** Automated UI regression testing performed on at least browser (more applications to be covered if possible)
* **Advocate/Owner:** Milosz Wasilewski
* **State:** proposed
* **Bug(s):** TBA
<br />
<br />
* **Summary:** update kernel to 4.8
* **Description:** update kernel to 4.8
* **Advocate/Owner:** Mark Brown
* **State:** proposed
* **Bug(s):** TBA
<br />
<br />
* **Summary:** latest Chromium release running on Wayland Ozone
* **Description:** latest Chromium release running on Wayland Ozone
* **Advocate/Owner:** Zoltan Kuscsik
* **State:** proposed
* **Bug(s):** https://...
<br />
<br />
* **Summary:** Video playback using Encrypted Media Extensions/OpenCDM
* **Description:** Video playback using Encrypted Media Extensions/OpenCDM
* **Advocate/Owner:** Zoltan Kuscsik
* **State:** proposed
* **Bug(s):** https://...
<br />
<br />
* **Summary:** image compatible with commercial DRMs (Widevine/Playready)
* **Description:** image compatible with commercial DRMs (Widevine/Playready)
* **Advocate/Owner:** Zoltan Kuscsik
* **State:** proposed
* **Bug(s):** https://...
<br />
<br />
* **Summary:** 32bit build on Hikey with graphics/Wayland support
* **Description:** 32bit build on Hikey with graphics/Wayland support
* **Advocate/Owner:** Zoltan Kuscsik
* **State:** proposed
* **Bug(s):** https://...
<br />
<br />
* **Summary:** [Debian] update CE RPB from Jessie to Stretch
* **Description:** for CE, Debian Jessie is too "old". Switch to Debian Stretch.
* **Advocate/Owner:** Fathi Boudra
* **State:** proposed
* **Bug(s):** https://...
<br />
<br />
* **Summary:** [OE] update CE RPB from Jethro to Krogoth
* **Description:** update CE RPB to latest official release, Krogoth.
* **Advocate/Owner:** Fathi Boudra, Nicolas Dechesne, Koen Kooi
* **State:** proposed
* **Bug(s):** https://...
<br />
<br />
* **Summary:** [Debian] SD card installer for HiKey
* **Description:** provide a SD card for HiKey
* **Advocate/Owner:** Fathi Boudra, Riku Voipio
* **State:** proposed
* **Bug(s):** https://...
<br />
<br />
* **Summary:** [OE][HiKey] fix the poor performance with RPK 4.4.11 and Weston image
* **Description:** fix poor performance with RPK 4.4.11 and Weston image
* **Advocate/Owner:** Fathi Boudra, Xinliang Liu
* **State:** proposed
* **Bug(s):** https://bugs.linaro.org/show_bug.cgi?id=2394
<br />
<br />
* **Summary:** [HiKey] support HDMI hotplug detection
* **Description:** fix HDMI hotplug detection on HiKey
* **Advocate/Owner:** Guodong Xu
* **State:** proposed
* **Bug(s):** https://bugs.96boards.org/show_bug.cgi?id=385
<br />
<br />
* **Summary:** [OE] switch from conman to NetworkManager
* **Description:** use NM instead of conman to be consistent with Debian RPB
* **Advocate/Owner:** Fathi Boudra
* **State:** proposed
* **Bug(s):** https://...
<br />
<br />
* **Summary:** [OE] use meta-mali layer
* **Description:** use meta-mali layer instead of our own recipes to provide Mali support
* **Advocate/Owner:** Fathi Boudra
* **State:** proposed
* **Bug(s):** https://...
<br />
<br />
* **Summary:** 32bit RP builds for Debian and OE
* **Description:** 32bit RP builds for Debian and OE
* **Advocate/Owner:** Fathi Boudra
* **State:** proposed
* **Bug(s):** https://...
<br />
<br />

#### Accepted Goals

NONE atm.

#### Rejected Goals

NONE atm.

#### Completed Goals

NONE atm.

### CE Release Hardware Platforms

Tested hardware platforms are splitted into 2 categories: Tier 1 (Reference Hardware Platforms) and Tier 2 (Optional Test Hardware Platforms).

**Note:** Serious bugs on Tier 1 platforms are release blockers, while they will be listed as known issues on Tier 2 platforms.

#### Tier 1 - Reference Hardware Platforms

* LeMaker HiKey

#### Tier 2 - Optional Test Hardware Platforms

* Dragonboard 410c

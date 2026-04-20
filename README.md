# FPV flight-control hardware, INAV firmware, and tuning tools

![FPV flight-control lab banner](assets/profile-cover.svg)

[![GitHub profile](https://img.shields.io/badge/GitHub-19379353560-181717?logo=github)](https://github.com/19379353560)
[![Portfolio](https://img.shields.io/badge/Portfolio-19379353560.github.io-0f766e)](https://19379353560.github.io/)
[![Updates](https://img.shields.io/badge/Updates-RSS%20%2B%20changelog-c2410c)](https://19379353560.github.io/updates.html)
[![Press Kit](https://img.shields.io/badge/Press%20Kit-shareable%20links-2563eb)](https://19379353560.github.io/press-kit.html)
[![Guides](https://img.shields.io/badge/Guides-review%20checklists-0f766e)](https://19379353560.github.io/guides.html)
[![Contribute](https://img.shields.io/badge/Contribute-good%20first%20issues-b91c1c)](https://19379353560.github.io/contribute.html)
[![INAV](https://img.shields.io/badge/INAV-firmware-blue)](https://github.com/iNavFlight/inav)
[![FPV](https://img.shields.io/badge/focus-FPV%20flight%20control-green)](https://github.com/19379353560?tab=repositories)

I build and document FPV drone flight-control projects across hardware,
firmware, and Blackbox-log analysis.

## Current Review Requests

If you work with INAV, FPV hardware, ESCs, or Blackbox logs, specific feedback is welcome:

| Area | What I need | Links |
|---|---|---|
| SkyPilot H743 | PCB layout, ICM42688P DRDY wiring, vibration and grounding review | [Issue](https://github.com/19379353560/skypilot/issues/1) / [Discussion](https://github.com/19379353560/skypilot/discussions/2) |
| 75A 4-in-1 ESC | High-current routing, MOSFET/gate-driver placement, thermal assumptions | [Issue](https://github.com/19379353560/DIY_Flight_Controller_and_4in1_ESC/issues/1) / [Discussion](https://github.com/19379353560/DIY_Flight_Controller_and_4in1_ESC/discussions/2) |
| INAV PID Tuner | Anonymized Blackbox logs and tuning-rule feedback | [Issue](https://github.com/19379353560/inav-pid-tuner/issues/1) / [Discussion](https://github.com/19379353560/inav-pid-tuner/discussions/2) |
| INAV D-term LPF | Flight-test logs on noisy frames and filter-profile behavior | [Issue](https://github.com/19379353560/inav/issues/1) / [Discussion](https://github.com/19379353560/inav/discussions/2) |

## Featured Projects

| Project | What it is | Status |
|---|---|---|
| [SkyPilot H743](https://github.com/19379353560/skypilot) | Open-source STM32H743 flight controller hardware for INAV, with ICM42688P IMU and firmware files. | Hardware files published; review wanted |
| [DIY Flight Controller and 4-in-1 ESC](https://github.com/19379353560/DIY_Flight_Controller_and_4in1_ESC) | 10-layer 75A 4-in-1 ESC hardware project with Gerbers, schematic, and PCB previews. | Manufacturing files published; thermal/current review wanted |
| [INAV PID Tuner](https://github.com/19379353560/inav-pid-tuner) | FastAPI tool for analyzing INAV Blackbox logs and generating PID/filter tuning recommendations. | Prototype available; validation logs wanted |
| [INAV Firmware Experiments](https://github.com/19379353560/inav) | Personal INAV branch focused on D-term pre-differentiation filtering, scheduler cleanup, and SkyPilot target support. | Upstream PRs opened; flight-test feedback wanted |

## Current Focus

- Reducing D-term noise amplification in INAV with pre-differentiation filtering.
- Improving IMU sampling latency for custom STM32H743 flight-controller hardware.
- Turning Blackbox logs into practical PID and filter tuning suggestions.
- Publishing PCB files and firmware notes so other FPV builders can inspect and reproduce the work.

## Upstream Work

- [iNavFlight/inav#11464](https://github.com/iNavFlight/inav/pull/11464) - D-term pre-differentiation LPF.
- [iNavFlight/inav#11465](https://github.com/iNavFlight/inav/pull/11465) - D-term pre-diff LPF plus code quality improvements.

## Feedback Welcome

I am especially interested in feedback from INAV and FPV builders on:

- D-term filtering behavior on noisy frames.
- STM32H743 flight-controller target design.
- Blackbox-based PID and filter tuning workflows.
- PCB layout review for high-current ESC and IMU signal integrity.

The fastest way to help is to comment on one of the review-request issues above with logs, screenshots, board notes, or comparable design references.

## Useful Links

- [Portfolio site](https://19379353560.github.io/)
- [Good first issues and contribution paths](https://19379353560.github.io/contribute.html)
- [Updates and RSS](https://19379353560.github.io/updates.html)
- [Press kit and project data](https://19379353560.github.io/press-kit.html)
- [Guides and review checklists](https://19379353560.github.io/guides.html)
- [AI-readable project summary](https://19379353560.github.io/llms.txt)
- [SkyPilot H743 project page](https://19379353560.github.io/skypilot.html)
- [75A 4-in-1 ESC project page](https://19379353560.github.io/esc.html)
- [INAV PID Tuner project page](https://19379353560.github.io/pid-tuner.html)
- [INAV D-term pre-diff LPF project page](https://19379353560.github.io/inav-dterm-lpf.html)

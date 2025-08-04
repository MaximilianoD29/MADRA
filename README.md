# MADRA: Quadruped Robotic Guide Dog

Welcome to the official companion site for **MADRA (Medical Autonomous Droid Remote Assistant)** — a quadruped robotic guide dog designed to assist individuals with blindness and vision impairment (BVI) through fully onboard object detection and voice interaction.

This site offers supporting media and materials referenced in our paper:

**“MADRA: Quadruped Robotic Guide Dog”**  
_University of Galway, HIVE Lab, 2025_

---

## 🎯 Project Summary

MADRA runs entirely on a Unitree Go1 Edu platform, using only its native onboard hardware. It supports:

- **Voice-guided mobility** using a Vosk-based wakeword + command system  
- **Obstacle awareness** with a fisheye-adapted YOLOv8 object detector  
- **Multimodal navigation** including leash-based guidance and semi-autonomous modes  
- **Field testing** in a simulated urban facility replicating public transport and terrain challenges

---

## 🎥 Demo Videos

These videos correspond to the **three-part testing structure** from the paper (Section II.E and Table III):

| Test Phase                | Description                                       | Video |
|--------------------------|---------------------------------------------------|-------|
| **Terrain Traversal**     | MADRA crossing gravel, ramps, and concrete | [Watch](https://drive.google.com/file/d/1YuEDupqHcTejxY4UnGiHg9LeYNgSlZg7/view?usp=drive_link) |
| **Stair Climbing**        | Inclined stair ascent using standard gait         | [Watch](https://drive.google.com/file/d/1uDg50wn8Ia0FKkLn-5p9iieBwtFtvfr9/view?usp=drive_link) |
| **Crosswalk Detection**   | Object classification using YOLOv8n + audio cue   | [Watch](https://drive.google.com/file/d/13FYVZR2MGwEMnntFbif5GTtFpPSyTAgs/view?usp=drive_link) |

Each clip reflects qualitative test outcomes and system behavior during real deployment.

---

## 🧠 System Highlights

- **Wakeword-activated voice interface** using “Guide Dog”
- **Command parsing** via predefined YAML/JSON vocabulary
- **Live object detection** (crosswalks, stairs, doors, people) with confidence-based feedback
- **No reliance on external GPUs or cloud** — everything runs onboard

---

## 🖼️ Image Samples

| Image Title           | Link |
|-----------------------|------|
| **Crosswalk Detection** | [View Image](https://drive.google.com/file/d/1UN7-KU3VOOA8EUbtbBKh5SNLAGjoxIJG/view?usp=drive_link) |
| **Terrain Types**       | [View Image](https://drive.google.com/file/d/1cep9Km6itADe78FNASx-GIcFfFl0ke1N/view?usp=drive_link) |
| **Tram Boarding**       | [View Image](https://drive.google.com/file/d/1C5GlZuv6yYU-fsLu0XE4bO8nroAP6tTb/view?usp=drive_link) |


---

## 📍 Testing Environment

Testing was conducted at the **Wayfinding Centre** (Dublin), which offers high-fidelity urban simulation.  
Tests included:
- Parallel/perpendicular crosswalk alignment
- Stair ascent
- Tram boarding with gap navigation
- Multi-surface terrain (gravel, tiles, slope)

---

## 📹 Additional Footage (Non-Testing)

The following videos are **not part of formal evaluation**, but offer relevant footage of MADRA operating in diverse environments:

| Clip                             | Description                              | Video |
|----------------------------------|------------------------------------------|-------|
| **Testing Centre Walkthrough**    | Ambient footage from the urban simulation site | [Watch](https://drive.google.com/file/d/1tV6kSjt_ZUKyNaLByC-fAnyKb2fdjH28/view?usp=drive_link) |
| **Walking Inside Aircraft Cabin** | MADRA walking through a plane aisle (no test) | [Watch](https://drive.google.com/file/d/1yEEPkz0OswvMyNVGzLPwK2F4cQUAiOCF/view?usp=drive_link) |

---

---

## 🤝 Acknowledgements

MADRA is developed at the [HIVE Lab, University of Galway](https://www.universityofgalway.ie/), with support from CÚRAM, SFI, and CISCO.

📧 For correspondence:  
`maximiliano.delgado@universityofgalway.ie` (author format)

---

_© 2025. Site maintained as supporting material for peer review and future development._

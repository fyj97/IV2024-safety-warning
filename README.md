# Digital Twin for Pedestrian Safety Warning

This repository contains the source code and supporting files for the research paper:

> **Digital Twin for Pedestrian Safety Warning at a Single Urban Traffic Intersection**  
> Yongjie Fu, Mehmet K. Turkcan, Vikram Anantha, Zoran Kostic, Gil Zussman, Xuan Di  
> *IEEE Intelligent Vehicles Symposium (IV), 2024*  
> [DOI: 10.1109/IV55156.2024.10588544](https://ieeexplore.ieee.org/document/10588544)

## 📌 Overview

This project develops a digital twin-based system that enhances pedestrian safety at urban traffic intersections. The system integrates smart city infrastructure, machine learning-based trajectory forecasting, and real-time communication between infrastructure and mobile users.

## 🏗 System Components

- **Object Detection & Tracking:**  
  Real-time detection and tracking using YOLOv8 and ByteTrack on video feeds from high-mounted COSMOS cameras.

- **Trajectory Prediction:**  
  Transformer-based models predict future positions of vehicles and pedestrians.

- **Time-to-Collision (TTC) Estimation:**  
  Collision risks are calculated using predicted trajectories and TTC thresholds.

- **MQTT Communication:**  
  Vehicle and pedestrian data are transmitted using the MQTT protocol to client devices.

- **Mobile Warning App:**  
  A smartphone app receives data and alerts pedestrians of potential collisions via UI and vibration/audio cues.

- **CARLA Simulation (optional):**  
  Digital twin implementation in CARLA for virtual testing and hardware-in-the-loop validation.
## 📚 Citation

If you use this codebase or refer to our work in your research, please cite the following paper:

### BibTeX

```bibtex
@inproceedings{fu2024digital,
  title     = {Digital Twin for Pedestrian Safety Warning at a Single Urban Traffic Intersection},
  author    = {Fu, Yongjie and Turkcan, Mehmet K. and Anantha, Vikram and Kostic, Zoran and Zussman, Gil and Di, Xuan},
  booktitle = {2024 IEEE Intelligent Vehicles Symposium (IV)},
  pages     = {2640--2645},
  year      = {2024},
  organization = {IEEE},
  doi       = {10.1109/IV55156.2024.10588544}
}

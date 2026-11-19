# Junhyeong Kwon

Robotics Software Engineer | robot audition and deep-learning perception, SLAM and navigation, embedded control

[Portfolio (PDF)](https://github.com/Kwon-Junhyeong/Kwon-Junhyeong/blob/main/Kwon_Portfolio_EN.pdf) | [LinkedIn](https://www.linkedin.com/in/junhyeong-kwon/) | meoruu00@gmail.com

I build robots that hear, see, and move.

- **Robot audition:** At the KIST AI and Robotics Institute (Humanoid Research Center), I worked on robot audition for human-robot interaction using 4-channel microphone arrays. The work included deep-learning direction-of-arrival estimation and speech separation, tested on a humanoid robot.
- **Robotics and embedded systems:** I have also built ROS 2 robots with SLAM and navigation, STM32 motor-control firmware, and FPGA accelerators.
- **Education:** B.S. in Electrical and Electronics Engineering at Chung-Ang University, expected February 2027.

## Projects

| Project | What it does | Code / status |
|---|---|---|
| Sound source localization on a robot body | Direction and separated speech of each speaker from 4 microphones on a robot body: SRP-PHAT, RTF, and a modified oSpatialNet on microphone responses computed with the boundary element method | [robot-body-sound-localization](https://github.com/Kwon-Junhyeong/robot-body-sound-localization), [stl2bem](https://github.com/Kwon-Junhyeong/stl2bem) |
| Localization without manual microphone calibration | Channel gains, phases, and delays recovered from unlabeled audio | [calibration-free-sound-localization](https://github.com/Kwon-Junhyeong/calibration-free-sound-localization) |
| Conformal prediction for sound source localization | A region built to contain the true direction with a chosen probability, with a confidence gate that withholds uncertain answers | [robot-body-sound-localization](https://github.com/Kwon-Junhyeong/robot-body-sound-localization) |
| Audiovisual sound event localization | DCASE 2026 Task 3 audiovisual track: low-threshold detection, a learned reranker, and dense mask output | [audiovisual-sound-event-localization](https://github.com/Kwon-Junhyeong/audiovisual-sound-event-localization) |
| Live captioning device | Tabletop device that labels each caption with its speaker (ROS 2, Jetson Orin Nano) | [live-caption-device](https://github.com/Kwon-Junhyeong/live-caption-device) |
| Smart indoor walker | Maps a room with LiDAR, drives to a clicked goal, and lifts its seat (ROS 2, Nav2) | [smart-indoor-walker](https://github.com/Kwon-Junhyeong/smart-indoor-walker) |
| Generative survivor search | Disaster-site search robot: a generative model predicts unseen space from LiDAR and sound | In progress, portfolio p. 14 |
| Face-tracking gimbal | Two-axis camera gimbal with closed-loop FOC firmware on an STM32 | [tracking-gimbal-foc](https://github.com/Kwon-Junhyeong/tracking-gimbal-foc) |
| LiDAR scan-matching accelerator | Gauss-Newton scan matching on an FPGA (Verilog, ZCU104) | [scan-matching-accelerator](https://github.com/Kwon-Junhyeong/scan-matching-accelerator) |
| YOLO object detection accelerator | YOLOv2-tiny CNN accelerator on an Artix-7 FPGA (Verilog, Nexys A7-100T) | [yolo-fpga-accelerator](https://github.com/Kwon-Junhyeong/yolo-fpga-accelerator) |
| Lane-following car | Camera-only lane following with an offloaded detector and a course state machine (Raspberry Pi) | [lane-following-car](https://github.com/Kwon-Junhyeong/lane-following-car) |

## Contact

meoruu00@gmail.com | [LinkedIn](https://www.linkedin.com/in/junhyeong-kwon/)

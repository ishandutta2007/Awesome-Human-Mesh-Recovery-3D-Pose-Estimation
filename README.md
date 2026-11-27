# Awesome-Human-Mesh-Recovery-3D-Pose-Estimation

# Awesome-Human-Mesh-Recovery-3D-Pose-Estimation

Top Human Mesh Recovery 3D Pose Estimation (Opensource) 🌟 Star if you like it! 🌟

A curated list of top human mesh recovery (HMR), 3D human pose estimation, markerless motion capture, SMPL/SMPL-X body reconstruction, and 3D character animation pipelines—featuring commercial SaaS/Hosted platforms alongside their open-source equivalents.

---

## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source Equivalents & Tools](#open-source-equivalents--tools)
  - [Monocular & Video Human Mesh Recovery (SMPL / SMPL-X)](#monocular--video-human-mesh-recovery-smpl--smpl-x)
  - [Markerless Multi-View & Monocular 3D Motion Capture](#markerless-multi-view--monocular-3d-motion-capture)
  - [2D & 3D Skeleton Pose Estimation Frameworks](#2d--3d-skeleton-pose-estimation-frameworks)
  - [Whole-Body, Hand & Face Mesh Reconstruction](#whole-body-hand--face-mesh-reconstruction)
  - [3D Animation, Retargeting & Blender/DCC Integrations](#3d-animation-retargeting--blenderdcc-integrations)
- [Contributing](#contributing)

---

## SaaS/Hosted Platforms

Commercial, cloud-hosted AI motion capture studios, browser-based video-to-3D animation platforms, and proprietary character rigging services.

* **[DeepMotion (Animate 3D)](https://deepmotion.com)** - Cloud-based AI markerless motion capture platform converting standard 2D videos into 3D skeletal animations with physics simulation.
* **[Plask](https://plask.ai)** - Browser-based AI motion capture and 3D animation editing suite enabling video-to-keyframe extraction and retargeting.
* **[Move.ai](https://move.ai)** - Commercial AI markerless motion capture platform transforming multi-camera and single-camera video into high-fidelity 3D motion data.
* **[Rokoko Studio & Rokoko Video](https://rokoko.com)** - Proprietary motion capture suite combining inertial mocap suits with cloud-based AI webcam/video motion capture.
* **[Kinetix](https://kinetix.tech)** - Cloud AI motion capture and user-generated 3D emote creation platform for games and virtual worlds.
* **[RADiCAL Motion](https://radicalmotion.com)** - Real-time, cloud-based 3D human motion capture and body reconstruction service accessible via browser and mobile apps.
* **[Wonder Dynamics (Autodesk Flow Studio)](https://wonderdynamics.com)** - Cloud AI platform that automatically animates, lights, and composes CG characters into live-action scenes from monocular video.
* **[Cascadeur Cloud & AI Assisted Animation](https://cascadeur.com)** - Physics-based 3D keyframe animation software featuring AI-assisted auto-posing and cloud rendering/processing tools.
* **[Anyworld / Mixamo (Adobe)](https://mixamo.com)** - Cloud-hosted automated 3D character rigging and motion-captured animation library platforms for game developers.
* **[ActorCore (Reallusion)](https://reallusion.com)** - Cloud-based 3D character and high-precision optical motion capture asset platform with automated rigging.

---

## Open-Source Equivalents & Tools

Free and open-source software (FOSS) models, real-time human mesh recovery pipelines, markerless mocap systems, and 3D skeleton estimators.

### Monocular & Video Human Mesh Recovery (SMPL / SMPL-X)

* **[InstantHMR (naturalpad-studio)](https://github.com)** - High-speed, open-source human mesh recovery pipeline engineered for real-time 3D body reconstruction and interactive applications.
* **[4D-Humans (HMR 2.0)](https://github.com)** - State-of-the-art transformer-based 3D human mesh reconstruction and tracking system from single-view video.
* **[WHAM (World-Grounded Humans with Accurate Motion)](https://github.com)** - Open-source method accurately recovering 3D human motion and SMPL meshes in global world coordinates from monocular video.
* **[TRAM (Trajectory-Aware Human Mesh Recovery)](https://github.com)** - Open-source pipeline combining SLAM with human mesh recovery to reconstruct global 3D human trajectories in dynamic scenes.
* **[CameraHMR](https://github.com)** - Open-source human mesh recovery model incorporating camera intrinsics estimation for accurate 3D body proportions and alignment.
* **[TokenHMR](https://github.com)** - Open-source tokenized representation framework advancing 3D human pose and shape recovery accuracy.
* **[VIBE (Video Inference for Body Pose and Shape Estimation)](https://github.com)** - Adversarial temporal learning framework predicting kinematically plausible 3D SMPL body sequences from video.
* **[ROMP (Monocular, One-stage, Regression of Multiple 3D People)](https://github.com)** - Fast, one-stage open-source network for simultaneous 3D mesh recovery of multiple people in real time.

### Markerless Multi-View & Monocular 3D Motion Capture

* **[FreeMoCap](https://github.com)** - Hardware- and software-agnostic open-source markerless motion capture system built for research, animation, and biomechanics.
* **[Pose2Sim](https://github.com)** - Open-source Python workflow connecting 2D pose estimators (OpenPose/MMPose/RTMPose) with OpenSim for 3D markerless kinematics.
* **[EasyMocap](https://github.com)** - Comprehensive open-source toolbox for multi-view and monocular human motion capture and neural body reconstruction.
* **[OpenCap](https://github.com)** - Stanford's open-source smartphone-based 3D human movement dynamics and musculoskeletal biomechanics capture system.
* **[MotionBERT](https://github.com)** - Unified open-source pretraining framework for 3D human motion representation, lifting 2D poses to 3D skeletons and meshes.

### 2D & 3D Skeleton Pose Estimation Frameworks

* **[MMPose (OpenMMLab)](https://github.com)** - Comprehensive open-source PyTorch toolbox supporting 2D/3D human pose estimation, whole-body tracking, and RTMPose models.
* **[MediaPipe Pose Landmarker](https://github.com)** - Google's fast, cross-platform open-source ML solution outputting 33 3D body landmarks in real time on CPU and mobile GPUs.
* **[Ultralytics YOLOv8 / YOLO11 Pose](https://github.com)** - Ultra-fast, real-time single-stage keypoint detection models deployable across edge devices, ONNX, and TensorRT.
* **[AlphaPose](https://github.com)** - Accurate open-source multi-person whole-body pose estimator and tracker supporting 2D and 3D keypoint lifting.
* **[ViTPose](https://github.com)** - Simple, scalable Vision Transformer baseline achieving top accuracy in human pose estimation benchmarks.
* **[MotionAGFormer](https://github.com)** - Open-source Attention-GCNFormer architecture for high-accuracy 2D-to-3D human pose lifting.

### Whole-Body, Hand & Face Mesh Reconstruction

* **[SMPLer-X](https://github.com)** - Open-source generalist foundation model for expressive whole-body 3D human mesh recovery (body, hands, and face).
* **[OSX (One-Stage Expressive Human Pose and Shape Estimation)](https://github.com)** - Open-source one-stage transformer pipeline jointly estimating 3D body, hand, and facial expressions without separate crop detectors.
* **[PIXIE](https://github.com)** - Expressive 3D whole-body mesh regressor capturing nuanced hand articulations and facial expressions from a single image.
* **[HaMeR (Hand Mesh Recovery)](https://github.com)** - High-precision transformer-based 3D hand mesh reconstruction model from monocular RGB images.
* **[EMOCA / DECA](https://github.com)** - Open-source 3D face mesh reconstruction frameworks capturing detailed facial geometry and emotional expressions.

### 3D Animation, Retargeting & Blender/DCC Integrations

* **[SMPL-X Blender Add-on](https://github.com)** - Official open-source Blender integration for loading, posing, and animating SMPL, SMPL+H, and SMPL-X body meshes.
* **[Rokoko Studio Live for Blender (Open-Source Plugin)](https://github.com)** - Open-source Blender add-on for automated bone retargeting between arbitrary 3D armatures and motion capture rigs.
* **[Auto-Rig Pro / Rigify (Blender)](https://blender.org)** - Blender's built-in open-source modular rigging system for converting raw mocap skeletons into production-ready animation rigs.
* **[Mediapipe-Blender / BlendArMocap](https://github.com)** - Open-source Blender add-on driving 3D character rigs directly from webcam pose, hand, and face tracking.

---

## Contributing

Contributions are welcome! Feel free to open a Pull Request to add more open-source human mesh recovery models, 3D pose estimators, or markerless mocap pipelines.

1. Fork the repository.
2. Add your project under the appropriate category with a concise description.
3. Submit a Pull Request.

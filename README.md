# Juxt Space 

An Ultra Fast Pose Estimation App aims to accelerate sport analysis workflows. (Runs with FastAPI executable as Tauri Sidecar).

## Overview

This is my undergraduate final year project (FYP).

This project is the second rebuilt (3rd time build); it was initialized using `create-next-app` on Dec 25, 2023. A public beta link will be dropping on December 31, 2023.

Link dropped: [https://beta.juxt.space](https://beta.juxt.space)

The public beta link is about 30% of the features. Join the waitlist.

![landing page](https://github.com/ziqinyeow/juxt-minified/raw/main/public/landing.png)

## Tech Stacks

1. Frontend: React & Vite
2. Styling: Tailwind, shadcn
3. Video Processing: MediaInfo wasm + React Player + Fabric JS
4. State Management + File Storage: Zustand + IndexedDB
5. Backend: FastAPI (Compiled with ONNX GPU Runtime using Pyinstaller)
6. Object Detection + Pose Estimation SDK: juxtapose
7. Pose Analysis: juxtematics
8. Desktop: Tauri (Github Actions to auto port React app to Windows/Mac/Ubuntu Installer)


## Features

- Modern, Sleek & Fast User Interface Build Using Next.js 14
- Minimalist Styled by Shadcn/ui + Tailwind
- Resizable Side Tab (Size Stored In Cookies) + Sonner Toaster + Command Palette + Keybindings
- Files/Folders Dropzone + Recursive Media Files Filtering + Store Into Browser Indexed DB
- State Management & Persistence With Zustand + Browser Indexed DB
- Configurable In Browser Model Inference (Model/Tracker Type + Model Runtime + CPU/WebGPU)
- Optional Region Of Interest Inference (Draw ROIs Before Inferencing)
- Ported Model: YOLOv8,RTMDet + RTMPose (-> JS)
- ByteTrack + BotSORT in the Browser (JS)
- Ported Runtime: ONNXRuntime + WASMRuntime (Rust -> JS)
- 17 Key Points Per Person + Bounding Boxes Displayed by Custom Video Canvas
- Responsive Video Canvas With Auto Keypoint + Skeleton + Any Object Scaling
- Real-Time Body Parts (Nose, Eye, Knee, ...) + Person Of Interest Toggler While Playing Video
- Accurate Per-Frame Operation Video Player Seeker Sync Perfectly With Canvas
- Configurable Playback Speed + FPS Seeker + Theatre Mode
- Real-Time Kinematics Metrics (Angle, Displacement, ...) Calculations + Displayed in Line Graph
- Stream Data Points Linked with Apache EChart Straight While Playing Video
- Per-Frame Keypoints Rectification to Update Real-Time Graph

## Conclusion

Star it till I open-source it. The plan is to open-source it to Vercel Template.

## Sneak Peak
![landing page](https://github.com/ziqinyeow/juxt.space/raw/main/assets/chart.png)

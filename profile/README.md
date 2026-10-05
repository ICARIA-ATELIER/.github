# Icaria Atelier

We are a creative collective of architects, artists, engineers & filmmakers that integrate design, storytelling and technology to transform spaces into immersive experiences. Whether at a museum, a public exhibition, a research environment, or a live installation, we create experiences that merge physical space, storytelling, and digital systems.

## Naming Convention

- `ICARIA_[NAME]`: Internal projects and shared components across the organization.
- `[PROJECT]_[NAME]`: Artifacts or modules specific to a concrete project.
- `com.icaria.[MODULE]`: Reusable Unity packages published as libraries.

## Project Portfolio

### CORALLIUM Series
Immersive marine and interactive experiences featuring VR/AR environments, educational interactives, and real-time location systems.

| Project | Type | Language |
|---|---|---|
| Corallium-Mangrove | Interactive Experience | C# |
| Corallium_Juvenile | Interactive Experience | C# |
| CORALLIUM_2-10_IA01_Animal_Rescue | Educational Game | C# |
| CORALLIUM_The_Device | Interactive Installation | C# |
| CORALLIUM_FP_Mockup | Prototype / Mockup | C++ |
| CORALLIUM_VR_Mockup | VR Prototype | C# |
| CORALLIUM_Seagrass_URP | Rendering Pipeline | C# |
| CORALLIUM_Seagrass_HDRP | Advanced Graphics | C# |
| CORALLIUM_Retail | Commerce Integration | C# |
| CORALLIUM_MeetExpert | Interactive Meeting | C# |
| CORALLIUM_DivingExhibit | Immersive Exhibition | C# |
| CORALLIUM_Coral_Resilience | Educational Experience | C# |
| CORALLIUM_Coral_Ecology | Ecological Experience | C# |
| CORALLIUM_SYNC | Data Synchronization (GraphQL) | JavaScript |
| CORALLIUM_Camera_server | Media Server | JavaScript |
| CORALLIUM_RTLS-SEWIO_SIMULATOR | Real-time Location System | HTML |
| CORALLIUM_Juvenile_OLD | Legacy Archive | C# |
| CORALLIUM_Mangrove_OLD | Legacy Archive | C# |
| Icaria_mangrove_system | Marine Ecosystem System | C# |

### ILMI Series
Large-scale immersive installations and interactive floor/simulator experiences.

| Project | Type | Language |
|---|---|---|
| ILMI_WR0-201-IA01_Immersive_Energy_Experience.floor | Interactive Floor | ShaderLab |
| ILMI_WR0-201-IA01_Immersive_Energy_Experience.simulator | Simulator | C# |
| ILMI_WR0-201-IA01_Immersive_Energy_Experience.floorTouchDesigner | Touch Designer | Python |
| ILMI_WR0-302-IA01_A_Seed_Interactive.interactive | Interactive Installation | C# |
| ILMI_WR0-302-IA01_A_Seed_Interactive.tracking | Hand Tracking System | C# |
| ILMI_WR0-303-IA01_A_Body_Interactive | Motion-Capture Experience | C# |
| ILMI_IA02_Explorers_Toolbar_Underwater_Microscopy | Educational Tool | C# |
| ILMI_WR1-103-IA02_Explorers_Toolbar_Underwater_Microscopy | Educational Tool | C# |
| ILMI_WR1-303-IA01_Explorers_Toolbar_Camera_Phase_1 | Camera Tool | C# |
| ILMI_WR2-403-IA01_Tide_Timelapse | Interactive Experience | C# |
| ILMI_WR2-406-IA01-Satellite_Monitoring | Monitoring Experience | C# |
| ILMI_MockupCameras | Camera Mockup | C++ |
| ILMI_MockupCameras_VR | VR Camera Mockup | C++ |
| ILMI_TC001Max_Control | Control System | Python |
| ILMI_Documentation | Project Documentation | HTML |
| ILMI_Design | Design Assets & Systems | HTML |
| ILMI_CMS | Content Management | JavaScript |

### Abu Dhabi Collection
Cultural immersive experiences featuring VR and desktop applications.

| Project | Type | Language |
|---|---|---|
| ABUDHABI_Oud_and_Pearls_VR | VR Experience | C# |
| ABUDHABI_Oud_and_Pearls_Desktop | Desktop Application | C# |

### EFM Expeditions
Exploratory VR experiences and control systems.

| Project | Type | Language |
|---|---|---|
| EFM_VR_ExpeditionVoyager | VR Experience | - |
| EFM_VRControlApplication | Control System | - |

### Fish Detection & AI
Machine learning and image processing projects.

| Project | Type | Language |
|---|---|---|
| ICARIA_FISH_DETECTION | ML Detection System | Vue |
| ICARIA_FISH_SEARCH_IMAGES | Image Database | Python |

### ICARIA Platform & Tools
Core infrastructure, launchers, and shared utilities.

| Project | Type | Language |
|---|---|---|
| ICARIA_LAUNCHER | Application Launcher | Rust |
| ICARIA_CAMERA_SERVER | Media Server | Rust |
| ICARIA-Kiosk-Launcher | Kiosk Interface | Kotlin |
| ICARIA_CheckIn | Check-in System Backend | TypeScript |
| ICARIA_CheckIn_APP | Mobile Check-in App | TypeScript |
| ICARIA_WEB | Corporate Website | PHP |
| ICARIA_REACT_SITE | React Portal | TypeScript |
| ICARIA_SPHERE | Immersive Display | JavaScript |
| ICARIA_SW_BASE | Software Base (Unity 6) | C# |

### Reusable Unity Packages (com.icaria.*)
Published libraries for common functionality across experiences.

| Package | Purpose | Language |
|---|---|---|
| com.icaria.foundation | Core framework and utilities | C# |
| com.icaria.deviceio | Hardware integration and device communication | C# |
| com.icaria.localization | Multi-language support | C# |
| com.icaria.inputaction | Input handling system | C# |
| com.icaria.hands | Hand tracking and gesture recognition (UDP) | C# |
| com.icaria.presence | Presence detection and awareness | C# |
| com.icaria.uitransitions | UI animation and transitions | C# |
| com.icaria.ui | Themable UI Components (Design System) | C# |
| com.icaria.video | Dual-player video playback with transitions | C# |
| com.icaria.appshell | Kiosk application shell framework | C# |
| com.icaria.overlayui | Runtime-built technical UI surfaces | C# |
| com.icaria.calibration | Keystone and projector calibration tools | C# |
| com.icaria.rendering | URP rendering helpers | C# |
| com.icaria.devtools | Debug and demo tooling for experiences | C# |

### EFPRU Project
Educational interactive experiences with backend infrastructure.

| Project | Type | Language |
|---|---|---|
| EFPRU_Directus | Headless CMS (Docker) | TypeScript |
| EFPRU_node_scripts | Automation Scripts | JavaScript |
| EFPRU_interactives | Interactive Content | TypeScript |

### Demo & Reference
Public-facing examples and documentation.

| Project | Type | Language |
|---|---|---|
| demo-repository | GitHub Best Practices Example | HTML |

## Technology Stack Summary

### Primary Platforms
- **Unity + C#**: VR/AR experiences, interactive installations, games, desktop applications
- **React + TypeScript**: Web applications, SPAs, interactive visualizations
- **Node.js**: Backend services, APIs, real-time systems, CMS integrations
- **Python**: Machine learning, computer vision, automation

### Specialized Technologies
- **WebSockets**: Real-time communication for synchronized experiences
- **FFmpeg / Media Services**: Video processing and streaming
- **OpenCV + YOLO**: Computer vision and object detection
- **TensorFlow + ConvNeXt**: Machine learning models
- **Directus**: Headless CMS platform
- **Touch Designer**: Visual programming for interactive installations
- **Tauri**: Native cross-platform desktop apps
- **Rust**: High-performance systems and servers

### Hardware & Integration
- **VR Platforms**: Oculus Quest, HTC Vive
- **Tracking Systems**: RTLS (Real-Time Location System), Hand tracking, Motion capture
- **Mobile**: Android, React Native
- **Kiosk/Embedded**: Custom Android launchers

## Featured Experience Types

- **🥽 VR/AR Experiences** - Immersive virtual and augmented reality environments
- **🎮 Interactive Installations** - Real-time motion tracking, gesture recognition, immersive floors
- **📊 Educational Interactive Content** - Engaging learning experiences with visualization
- **🌐 Web Applications** - Responsive platforms, CMSs, digital services
- **🎯 Real-time Systems** - RTLS tracking, live synchronization, networked experiences
- **📱 Mobile Applications** - Check-in systems and companion apps
- **🐠 AI & Computer Vision** - Fish detection, image processing, ML models

## Repository Statistics

- **Total Repositories**: 65+
- **Primary Language**: C# (Unity ecosystem)
- **Secondary Languages**: TypeScript, JavaScript, Python
- **Project Categories**: 10 major series/categories
- **Reusable Packages**: 14 com.icaria.* libraries

---

**Organization**: ICARIA-ATELIER  
**Focus**: Immersive Experience Design & Technology Integration  
**Scale**: 65+ repositories spanning VR, AR, interactive installations, web platforms, machine learning, and supporting infrastructure  
**Latest Update**: October 2026

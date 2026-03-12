# NDHU IM25 Graduation Project

Built a high-fidelity VR vocational training system with Unity HDRP — bridging the gap where physical training lacks repeatability and web-based training can't handle real conversational scenarios.

![Unity](https://img.shields.io/badge/Unity-HDRP-black?logo=unity)
![C#](https://img.shields.io/badge/C%23-239120?logo=csharp&logoColor=white)
![VR](https://img.shields.io/badge/Platform-VR-blueviolet)
![Status](https://img.shields.io/badge/Status-Graduation%20Project%202025-blue)

## System Architecture

```mermaid
graph TD
    A[User / Trainee] --> B[VR Headset]
    B --> C[Unity Scene Manager]
    C --> D[Training Scenario Loader]
    D --> E1[Scenario: Customer Service]
    D --> E2[Scenario: Emergency Response]
    D --> E3[Scenario: Equipment Operation]
    E1 & E2 & E3 --> F[Interaction & Response Engine]
    F --> G[Feedback & Scoring System]
    G --> H[Performance Report]
```

## Highlights

- **Problem**: Physical training limits practice frequency; web-based training fails at conversational and spatial tasks — VR solves both
- **Technical approach**: Unity HDRP rendering pipeline delivers photorealistic training environments with real-time interaction logic in C#
- **Outcome**: Graduation project, NDHU Information Management, Class of 2025

## Repositories

| Repo | Description |
|------|-------------|
| [IM25_HDRP](https://github.com/Love-MrHou/IM25_HDRP) | Main VR training system — Unity HDRP rendering pipeline, core interaction logic |
| [IM25_final](https://github.com/Love-MrHou/IM25_final) | Final release build — optimized scenes and packaged for deployment |

![Status](https://img.shields.io/badge/Status-Graduation%20Project%202025-blue)

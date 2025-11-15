<p align="center">
  <img width="1000" src="prof.gif" />
</p>

## Aleksandr Puström
### *Robotics Engineer*  
Anyang, South Korea  

---

## Education
- **M.S. (2023–2025):** Seoul National University — Mechanical Engineering  
- **B.Eng. (2017–2021):** University of Aberdeen — Mechanical Engineering  

---

## Research / Work Interests
- Robotics integration  
- Teleoperation systems  
- Aerial manipulation  
- Digital twins & VR interfaces  

---

## Skills
- **Languages:** Estonian, English, Russian, Korean  
- **Programming:** Python, C/C++, MATLAB  
- **Typesetting:** LaTeX  
- **Frameworks:** ROS / ROS2, TensorFlow  

---

## Projects

<!-- ======== LASDRA DROPDOWN START ======== -->

<details>
  <summary><strong>LASDRA Teleoperation System (Click to Expand)</strong></summary>
  <br>

  <!-- Small preview video at the top -->
  <p align="center">
    <img width="800" src="lasdra_preview.gif" />
  </p>

  ## 🚁 LASDRA Teleoperation System

  ![UE5](https://img.shields.io/badge/Unreal_Engine-5.0-black?logo=unrealengine)
  ![ROS2](https://img.shields.io/badge/ROS2-Jazzy-blue?logo=ros)
  ![VR](https://img.shields.io/badge/VR-Meta_Quest_2-purple?logo=meta)
  ![Franka](https://img.shields.io/badge/Haptic-Franka_Emika-orange)
  ![Python](https://img.shields.io/badge/Python-3.10-yellow?logo=python)
  ![C++](https://img.shields.io/badge/C++-17-blue?logo=c%2B%2B)

  **Digital Twin • VR Teleoperation • Aerial Manipulation**

  - **UE5 Digital Twin**  
    High-fidelity model synced with real-time LiDAR, IMU, and motion-capture  
    <p align="center">
      <img width="700" src="dt_photo_01.jpg" />
    </p>

  - **VR Spatial Interface** (Meta Quest 2)  
    Immersive real-time navigation and manipulation  
    <p align="center">
      <img width="700" src="vr_photo_01.jpg" />
    </p>

  - **Gesture-Based View Control (VIST Glove)**  
    Single-hand viewport manipulation with pinch-activated controls  
    <p align="center">
      <img width="700" src="vist_glove.jpg" />
    </p>

  - **Haptic Teleoperation (Franka Emika)**  
    Force-feedback master device for fine manipulation  
    <p align="center">
      <img width="700" src="franka_photo_01.jpg" />
    </p>

  - **Unified PyQt Control Panel**  
    A single GUI controlling joint locking, velocity modes, and telemetry  
    <p align="center">
      <img width="700" src="gui_photo_01.jpg" />
    </p>

  - **Two-PC Architecture over NNG**  
    Ubuntu (ROS) ↔ Windows (UE5 + VR) real-time data pipeline

  **Thesis:** _VR Digital Twin & Hand-Tracking Interface for Aerial Manipulator Operators_

  <br>
</details>

<!-- ======== LASDRA DROPDOWN END ======== -->

<!-- ======== TRI TILT-ROTOR PROJECT DROPDOWN START ======== -->

<details>
  <summary><strong>Tri Tilt-Rotor VTOL UAV — Bachelor’s Thesis (Click to Expand)</strong></summary>
  <br>

  <!-- Small preview video or GIF -->
  <p align="center">
    <img width="800" src="tri_tilt_preview.gif" />
  </p>

  ## ✈️ Tri Tilt-Rotor VTOL UAV — Transition Flight Project

  ![UAV](https://img.shields.io/badge/UAV-Tilt--Rotor-blue)
  ![VTOL](https://img.shields.io/badge/VTOL-Hover_↔_Cruise-green)
  ![ArduPilot](https://img.shields.io/badge/Autopilot-ArduPilot-orange)
  ![Pixhawk](https://img.shields.io/badge/Flight_Controller-Cube_Orange-red)
  ![CAD](https://img.shields.io/badge/CAD-SolidWorks-lightgrey)
  ![Testing](https://img.shields.io/badge/Field_Tests-Completed-success)

  **Tri-Rotor • Fully Tiltable • Autonomous Transition Flight**  
  Bachelor's Thesis, University of Aberdeen (2021)  
  :contentReference[oaicite:1]{index=1}

  ### **Overview**
  Designed, built, and flight-tested a **Tri Tilt-Rotor VTOL UAV** capable of transitioning  
  from **Hover mode** to **Cruise mode** using a fully tiltable three-rotor configuration.  
  Demonstrated successful transition flights and provided the architecture to the  
  Aerospace Engineering Society for competition use.

  ### **Key Contributions**

  - **Tri-Rotor Tilting Mechanism Design**  
    3D-printed servo-driven tilt joints enabling 0–90° rotation for all three motors  
    <p align="center">
      <img width="700" src="tilt_mechanism.jpg" />
    </p>

  - **Flight Dynamics & Control Architecture**  
    - Hover mode: tricopter dynamics, vectored yaw  
    - Cruise mode: aerodynamic control via ailerons & V-tail  
    - Transition: gain-scheduled mixed controller (20°–40° tilt blending)  
    <p align="center">
      <img width="700" src="transition_diagram.jpg" />
    </p>

  - **Full CAD Design & Prototype Manufacturing**  
    - Airframe built from plywood & custom 3D-printed parts  
    - Inverted V-tail, equilateral motor placement  
    <p align="center">
      <img width="700" src="prototype.jpg" />
    </p>

  - **Motor Selection, Testing & Thrust Characterization**  
    - T-Motor AT3520 + APC 17x4 propellers  
    - Complete thrust-current & thrust-throttle curve analysis  
    <p align="center">
      <img width="700" src="motor_test.jpg" />
    </p>

  - **Autopilot Integration (ArduPilot + Pixhawk Cube Orange)**  
    - PID tuning, gain scheduling, mission planner integration  
    - SBUS radio link, telemetry radio, GPS, ESCs  
    <p align="center">
      <img width="700" src="pixhawk_setup.jpg" />
    </p>

  - **Hover & Transition Flight Testing**  
    Completed multiple hover flights → transition to cruise → return to hover  
    <p align="center">
      <img width="700" src="flight_test.gif" />
    </p>

  ### **Results**
  - Successful autonomous transition from vertical takeoff → cruise → return  
  - Verified concept and handed system to the **Aerospace Engineering Society**  
  - Achieved stable hover, controllable cruise, and reliable transition behavior  

  ### **Thesis**
  _“Transition Flight of Tri Tilt-Rotor VTOL UAV”_  
  Bachelor of Engineering, University of Aberdeen  
  (Full document available in repository)  
  :contentReference[oaicite:2]{index=2}

  <br>
</details>

<!-- ======== TRI TILT-ROTOR PROJECT DROPDOWN END ======== -->

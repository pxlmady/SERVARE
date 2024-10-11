# Software Requirements Specification

Table of Contents
=================
* [Revision History](#revision-history)
* 1 [Introduction](#1-introduction)
  * 1.1 [Document Purpose](#11-document-purpose)
  * 1.2 [Product Scope](#12-product-scope)
  * 1.3 [Definitions, Acronyms and Abbreviations](#13-definitions-acronyms-and-abbreviations)
  * 1.4 [References](#14-references)
  * 1.5 [Document Overview](#15-document-overview)
* 2 [Product Overview](#2-product-overview)
  * 2.1 [Product Perspective](#21-product-perspective)
  * 2.2 [Product Functions](#22-product-functions)
  * 2.3 [Product Constraints](#23-product-constraints)
  * 2.4 [User Characteristics](#24-user-characteristics)
  * 2.5 [Assumptions and Dependencies](#25-assumptions-and-dependencies)
  * 2.6 [Apportioning of Requirements](#26-apportioning-of-requirements)
* 3 [Requirements](#3-requirements)
  * 3.1 [External Interfaces](#31-external-interfaces)
    * 3.1.1 [User Interfaces](#311-user-interfaces)
    * 3.1.2 [Hardware Interfaces](#312-hardware-interfaces)
    * 3.1.3 [Software Interfaces](#313-software-interfaces)
  * 3.2 [Functional](#32-functional)
  * 3.3 [Quality of Service](#33-quality-of-service)
    * 3.3.1 [Performance](#331-performance)
    * 3.3.2 [Security](#332-security)
    * 3.3.3 [Reliability](#333-reliability)
    * 3.3.4 [Availability](#334-availability)
  * 3.4 [Compliance](#34-compliance)
  * 3.5 [Design and Implementation](#35-design-and-implementation)
    * 3.5.1 [Installation](#351-installation)
    * 3.5.2 [Distribution](#352-distribution)
    * 3.5.3 [Maintainability](#353-maintainability)
    * 3.5.4 [Reusability](#354-reusability)
    * 3.5.5 [Portability](#355-portability)
    * 3.5.6 [Cost](#356-cost)
    * 3.5.7 [Deadline](#357-deadline)
    * 3.5.8 [Proof of Concept](#358-proof-of-concept)
* 4 [Verification](#4-verification)
* 5 [Appendixes](#5-appendixes)



## Revision History
| Name | Date    | Reason For Changes  | Version   |
| ---- | ------- | ------------------- | --------- |
|      |         |                     |           |
|      |         |                     |           |
|      |         |                     |           |



## 1. Introduction

### 1.1 Document Purpose
This Software Requirements Specification (SRS) document is intend to give a complete overview of PC game project named SERVARE, including the game mechanics, user interface and story therein.

### 1.2 Product Scope
The project is a highly-optimised 3D game on PC in a low-poly style. The story is designed to showcase beautiful landscapes and environments, allowing the players to fully immerse themselves in the storyline of this fantasy adventure game. It also provides enjoyment through mechanics that enable players to overcome engaging challenges.

### 1.3 Definitions, Acronyms and Abbreviations

### 1.4 References
1. ISO/IEC 9126 - Software Quality Standards.
2. Playdead’s INSIDE and LIMBO - Gameplay, Visual and Sound Design Style Analysis.
3. Unity Documentation - Physics and Animation Systems.
4. Game Design Patterns in Low-Poly Environments, John Smith, 2023.
5. API Documentation for Steam Integration, Steamworks Developer Portal.



## 2. Product Overview

### 2.1 Product Perspective
SERVARE is a 3D linear low-poly adventure game designed for the PC platform. It is a standalone product inspired by Playdead’s games such as INSIDE and LIMBO, focusing on an immersive player experience through detailed environments and challenging gameplay challenges. The game does not require any multiplayer components, external server integration or donation implementation. However, it will feature integration with Steam for distribution and achievements. The primary interaction with the game will be through keyboard and mouse, with potential support for gamepads. SERVARE will rely on Unity for physics, animation, and rendering systems. Minimal hardware requirements include a mid-range GPU and at least 8GB of RAM for smooth performance. The product must meet platform-specific requirements for Steam integration, such as compliance with the Steamworks SDK for achievements and cloud saving features.

### 2.2 User Characteristics
The typical SERVARE player is a fan of atmospheric single-player adventures, who enjoys games like INSIDE and LIMBO, focusing on exploration and puzzle-solving.



## 3. Requirements

### 3.1 Functional
1. **Character Movement**: 
   - The player can control the main character's movement using keyboard and mouse or gamepad inputs.
2. **Exploration Mechanics**: 
   - The player can explore the environment, interact with objects, and uncover hidden paths.
3. **Challenges Solving**: 
   - The game includes various challenges that players must solve to progress through the story and unlock new areas.
4. **Save/Load Functionality**: 
   - Players can save their progress at specific points and load their game from a saved state.
6. **User Interface**: 
   - The game features an intuitive and simple user interface. The loading menu must include the game logo in the middle, as well as buttons in the following order:
        1) Continue
        2) Load
        3) Settings
        4) Exit (Ask the player about assurance of exit)
 7. **Sound Design Mechanisms**: 
   - Audio feedback will be provided for player actions, such as successful puzzle completion or interactions with the environment. 

### 3.2 Minimum System Requirements:
Operating System: Windows 7/8/10 (64-bit)
Processor: Intel Core i5-750 or equivalent AMD
Memory: 4 GB RAM
Graphics: NVIDIA GTX 460 or equivalent AMD Radeon HD 5750 (DirectX 11 compatible)
Storage: 3 GB available space
Sound Card: DirectX 9.0c compatible

### 3.3 Deadline
Ship date: December 2024

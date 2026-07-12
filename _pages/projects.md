---
permalink: /projects/
title: "Projects"
author_profile: true
---

{% include base_path %}

- **Critical Path Method Project Scheduler** (July 2026, In Progress) — C++ project scheduling system with MVC architecture and CPM algorithm. Object-Oriented Programming Training, Tsinghua University.
  - Developed a C++ project scheduling system implementing the Critical Path Method (CPM) algorithm
  - Designed with MVC architecture and a template-based file I/O plugin system supporting extensible formats
  - Supports four standard dependency types (FS, SS, FF, SF) with configurable lag, resource management, and DAG cycle detection via DFS-based topological check

- **Catgirl Resource Machine --- A Programming Puzzle Game** (November 2025) — C++/Qt 6 puzzle game with assembly-like instruction set and 4-level campaign. Fundamentals of Programming, Tsinghua University.
  - Built a puzzle game in C++/Qt 6 inspired by *Human Resource Machine*, featuring an assembly-like instruction set (inbox, outbox, add, sub, copyto, copyfrom, jump, jumpifzero)
  - Implemented a 4-level campaign with progressive difficulty, single-step debugging, and real-time visual feedback via Qt signal/slot mechanism

- **Home Service Robot Vision Pipeline (YOLO11-seg + SAM3)** (June 2026) — Full-stack deep learning pipeline for household object detection and instance segmentation. Introduction to Artificial Intelligence, Tsinghua University.
  - Built a full-stack deep learning pipeline for household object detection and instance segmentation, targeting home service robotics applications
  - Integrated SAM3 for zero-shot automatic annotation with seed-and-propagate workflow across video frames, and YOLO11-seg for real-time inference
  - Implemented automatic dataset export (YOLO format), data augmentation (Albumentations), and a React + Vite web frontend with WebSocket-based real-time training feedback

# 🚀 Exclusive Courses: A Journey into Robotics and AI Engineering

Welcome to the exclusive learning repository curated by **Jiang (BlueDarkUP)** for FTC Team 27570 and the broader robotics community.

This is not just a collection of code snippets; it's a **structured learning path** designed to take you from a novice programmer to a confident systems engineer. Each course, built upon real-world competition projects, represents a step forward in technical skill and, more importantly, in engineering thinking.

---

## 💡 Core Philosophy

This curriculum is built on three core principles:

> **1. Beyond Just Code: Understanding the "Why"**
> We don't just write code; we solve problems. These courses focus on the design patterns, architectural decisions, and engineering trade-offs behind every line of code.

> **2. From Prototype to Product: An Evolutionary Approach**
> Witness the evolution of a system from a single, all-in-one script to a modular, robust, and maintainable API. This is how real-world software is built.

> **3. Building Tools, Not Just Solutions**
> The ultimate goal of a senior engineer is not just to build a solution for one problem, but to build tools that empower others to solve many problems. This curriculum culminates in the creation of powerful, reusable development tools.

---

## 📚 The Curriculum: From Novice to Architect

The seven courses are designed to be followed in order, building upon the concepts learned in the previous stage.

### Part I: Foundations of FTC Robotics - Mastering TeleOp

This section is for anyone new to FTC Java programming. We start with the basics of controlling a robot and introduce the fundamental concepts of software structure.

#### 🎓 **Course 1: Your First Competition-Ready TeleOp**
- **What you'll learn:** The fundamental structure of a `LinearOpMode`, how to map hardware, and implement robust driver controls for a Mecanum drive base.
- **Key Concepts:** Hardware Mapping, Field-Centric Drive, State Machines, Debouncing.
- ➡️ **[Access the Course on Notion](https://grizzly-treatment-ac4.notion.site/FTC-27570-TeleOp-250969a5284d8075b144dca6f421e9b8?pvs=73)**

#### 🔧 **Course 2: Advanced TeleOp with Road Runner Integration**
- **What you'll learn:** How to integrate a sophisticated motion planning library (Road Runner) into your TeleOp for powerful, semi-autonomous actions like "one-click return to a saved position."
- **Key Concepts:** Road Runner API, `Pose2d`, Action Sequences, Position Memory.
- ➡️ **[Access the Course on Notion](https://grizzly-treatment-ac4.notion.site/FTC-27570-250969a5284d8098bb35c9c637ac0fa3?pvs=73)**

---

### Part II: The Leap to Intelligent Systems - Vision APIs

Here, we move beyond simple control and begin to give our robot "eyes." You will learn how to build and consume powerful, reusable vision APIs.

#### 🧠 **Course 3: Building a Vision API (The Journey Begins)**
- **What you'll learn:** An introduction to designing a self-contained vision system. This course covers the initial architecture for a vision pipeline that can be used by any OpMode.
- **Key Concepts:** API Design (Facade Pattern), `OpenCvPipeline`, Color Segmentation, Contour Analysis.
- ➡️ **[Access the Course on Notion](https://grizzly-treatment-ac4.notion.site/FTC-27570-API-250969a5284d8039bb4ee5f524f3279f?pvs=73)**

#### ✨ **Course 4: Architecting a Production-Grade Vision System**
- **What you'll learn:** A masterclass in software architecture. This course refactors the initial API into a highly modular, maintainable, and powerful system with clear separation of concerns, culminating in the final version used in the `INTO THE DEEP` season.
- **Key Concepts:** Separation of Concerns (SoC), Configuration Management (`VisionConstants`), Advanced Decision Logic (`DetectionProcessor`), Physics & Kinematics Modeling (`GraspingCalculator`).
- ➡️ **[Access the Course on Notion](https://grizzly-treatment-ac4.notion.site/FTC-27570-API-250969a5284d808380a8ea220da47436?pvs=73)**

---

### Part III: End-to-End AI Projects - From Pixels to Action

This section dives deep into complete, standalone AI projects. You will learn to build systems that perceive, think, and act entirely on their own.

#### 🌊 **Course 5: Case Study - The FLL AquaHunter (Autonomous ROV)**
- **What you'll learn:** How to build a complete, single-script AI system from scratch. This project covers real-time object tracking with the SORT algorithm and visual servoing for an underwater robot.
- **Key Concepts:** `YOLOv8` Inference, **SORT Algorithm (Kalman Filter + Hungarian Algorithm)**, Hardware Abstraction Layers (HAL), Serial Communication.
- ➡️ **[Access the Course on Notion](https://grizzly-treatment-ac4.notion.site/FTC-27570-250969a5284d802eabe6de3f2173870d?pvs=73)**

---

### Part IV: The Masterclass - Building the Tools for AI

This final section represents the pinnacle of engineering: instead of just *using* AI, you will learn how to build the **professional tools and pipelines** that *enable* AI development.

#### 🛠️ **Course 6: Building Your Own Data Engine - Zero-to-YOLO-Yard**
- **What you'll learn:** How to architect and build a full-stack web application for managing the entire machine learning data lifecycle. This is a deep dive into creating a local, powerful alternative to cloud-based annotation platforms.
- **Key Concepts:** `Flask` Web Framework, `SQLite` Database Design, REST APIs, Asynchronous Tasks, **SAM 2.1 Integration**, Frontend Development (`JavaScript`, `jQuery`).
- ➡️ **[Access the Course on Notion](https://grizzly-treatment-ac4.notion.site/FTC-27570-AI-250969a5284d80aa8ccfe5e2bc11e73e?pvs=73)**

#### 🏭 **Course 7: Building Your Own AI Factory - The FTC-Easy-TFLITE Pipeline**
- **What you'll learn:** How to create a standardized, automated, and reproducible MLOps pipeline for training and deploying FTC-compatible models. This course solves the most significant pain points in the custom model workflow.
- **Key Concepts:** **MLOps (Machine Learning Operations)**, Automation with `Bash`, Environment Management (`Conda`), Model Quantization, **TFLite Metadata Injection**, Standalone Diagnostic Tools.
- ➡️ **[Access the Course on Notion](https://grizzly-treatment-ac4.notion.site/FTC-27570-AI-250969a5284d8001ab71c9365a4827e8?pvs=73)**

---

## 📖 How to Use This Repository

This GitHub repository serves as a centralized hub and curriculum guide. All course content is hosted on Notion for a richer reading experience.

1.  Start with Course 1 and proceed in order.
2.  Read the documentation thoroughly to understand the concepts.
3.  Clone the associated project repositories (linked within the Notion docs) to follow along with the code.
4.  Experiment, modify, and break things. That's the best way to learn!

---

## 👨‍💻 About the Author

This curriculum was developed and curated by **Jiang (BlueDarkUP)**, a Grade 11 student and the lead programmer for FTC Team 27570. He is a full-stack developer and AI robotics engineer passionate about building end-to-end systems that solve real-world problems.

<p align="left">
  <a href="https://github.com/BlueDarkUP" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
  <a href="https://www.youtube.com/@BlueDarkUP" target="_blank"><img src="https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white" alt="YouTube"/></a>
  <a href="mailto:BlueDarkUP@Gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

Happy building! ✨

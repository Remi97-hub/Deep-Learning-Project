# Milk Theft Detection from CCTV (Computer Vision)

## Overview

This project demonstrates an **AI-based system to detect potential milk theft events from CCTV footage** using computer vision and event-level reasoning.

Instead of relying only on frame-level object detection, the system applies **temporal and rule-based logic** across consecutive frames to identify suspicious milk-handling actions and automatically capture visual evidence.

---

## Problem

* Manual CCTV monitoring requires dedicated time
* Milk theft occurs as a sequence of actions, not a single frame
* Object detection alone cannot capture intent

**Objective:** Automatically detect suspicious milk theft events and store evidence for review.

---

## Approach (High Level)

1. CCTV video input
2. Frame-wise object detection (YOLO)
3. Temporal analysis across frames
4. Rule-based event detection
5. Evidence frame capture with timestamp

This project focuses on **system design**, not just model training.

---

## Tools & Technologies

* Python
* YOLO (Ultralytics)
* OpenCV
* Roboflow (annotation)
* Rule-based event logic
* CCTV video footage

---

## Dataset

* 720 annotated images
* Annotated using Roboflow
* Domain-specific CCTV data

 Dataset is limited in size and diversity.

---

## Evaluation (Note)

* Metrics may look strong
* Results are not benchmark-level
* Dataset is small and environment-specific

The key contribution is the end-to-end event detection pipeline, not the scores.

---

## Future Scope

* Pose-based reasoning
* Improved temporal consistency
* Robustness to zoomed/noisy footage
* Multi-camera integration

---

## Limitations

* Small dataset
* Rule-based logic requires tuning
* Not tested in production environments

---

> Practical AI is built, not just trained.

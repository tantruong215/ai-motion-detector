# Pseudocode – AI Motion Detector

## Goal
Detect and classify human motion using camera + ML model on Jetson Nano or Raspberry Pi.

## Flow
- [ ] Capture image or video frame
- [ ] Run object detection (YOLO or MobileNet)
- [ ] If human detected → store timestamp
- [ ] Track movement across zones
- [ ] Send alert if new person enters frame
- [ ] Log detections with confidence score

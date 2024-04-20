Sure, here's the revised description with that addition:

---

# GunGuard: Real-time Gun Detection and Notification System

GunGuard is an open-source project aimed at enhancing safety by detecting firearms in real-time video streams and providing immediate notifications to users. Leveraging the power of YOLOv3 object detection, GunGuard can accurately identify guns and send alerts to mobile devices via the Pushbullet API.

## Features

- **Real-time Gun Detection:** Utilizes YOLOv3, a state-of-the-art object detection algorithm, to identify firearms in live video streams.
  
- **Mobile Notifications:** Integrates with the Pushbullet API to send instant notifications to users upon detecting a gun, including the timestamp and location of the detection.
  
- **User-Friendly Interface:** Offers a simple and intuitive interface for configuring settings and managing notifications.

## How it Works

GunGuard continuously analyzes video feeds in real-time, detecting any presence of firearms. Upon detection, the system captures the frame containing the gun and sends a notification to the user's mobile device via Pushbullet. The notification includes the time and location of the detection, allowing users to take immediate action if necessary.

## Training Data

GunGuard was trained using a custom dataset consisting of over 3000 images of handguns. The model was trained over 900 epochs to ensure robust performance and accurate detection of firearms.


---

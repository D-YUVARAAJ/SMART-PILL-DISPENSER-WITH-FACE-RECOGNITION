# SMART-PILL-DISPENSER-WITH-FACE-RECOGNITION
This repo is all about explaining the project that makes tablet consumption much easier than the traditional manual method!!


This project is a smart medication dispenser that combines AI (face recognition) and IoT to help people take their medicines on time. The system dispenses pills automatically according to a set schedule and uses face recognition to ensure the right person is taking the medicine.

If the pills are not taken within a given time (e.g., 15 minutes), the system sends alerts (buzzer, LED, or email notification). It can also be monitored remotely through a Cloudflare tunnel with live video streaming.

The main goal is to help elderly people and patients with chronic conditions stick to their medication routine in a safe and reliable way.

Features

Automated pill dispensing at scheduled times.

Face recognition to verify the user’s identity.

Alerts via buzzer/LED and email if a dose is missed.

Remote monitoring with live video streaming.

Compact hardware design that can be deployed at home.

Hardware Used

Raspberry Pi 4 (4GB RAM recommended)

Stepper motor (28BYJ-48) + ULN2003 driver

Pi Camera V2

LEDs and buzzer

microSD card (16–32GB)

Power adapter

Custom pill dispenser casing

Software / Tools

Python 3.x

OpenCV for image processing

Face recognition models (Haar cascades / dlib)

Cloudflare Tunnel for remote access

Email notification service

How It Works

The system runs on a Raspberry Pi.

When it’s time for medication, the motor rotates to dispense pills into a slot.

The camera verifies the user’s face before confirming intake.

If the pill is not collected within 15 minutes, an alert is triggered.

Caregivers (or yourself) can also monitor the system remotely using the livestream.

Why I Built This

I wanted to build something that combines embedded systems, AI, and IoT to solve a real-world health problem. Managing medicines can be challenging, especially for elderly people. By adding automation, recognition, and remote monitoring, I created a device that makes this process more reliable and stress-free.

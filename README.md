# RESTIQ

## About the Project

RESTIQ is an AI-powered sleep tracking application designed to provide users with a comprehensive and personalized understanding of their sleep health. By integrating with fitness trackers and a user's phone, RESTIQ captures key health metrics and uses a custom AI model to analyze the data, offering insights that rival professional, medical-grade sleep analysis. Our goal is to empower users with accurate, actionable information about their sleep, promoting better health and well-being.

## Core Features

Harnessing the power of our custom AI model, RESTIQ intelligently analyzes your sleep data to detect and inform you about:

- **Increased Snoring Intensity**: Monitoring for changes in snoring patterns and volume.
- **Sleep Apnea-like Pauses**: Identifying potential breathing irregularities during sleep.
- **Restlessness**: Tracking tossing and turning to measure sleep quality.
- **Circadian Rhythm Shifts**: Understanding and visualizing changes in your natural sleep-wake cycle.
- **Recovery Monitoring**: Using metrics like Heart Rate Variability (HRV) to gauge recovery from stress, illness, or fatigue.
- **Difficulty Breathing**: Providing alerts for signs of impaired respiration.
- **Medical Referrals**: If the data indicates a significant health concern, the app will provide information on hospitals and specialized centers for professional diagnosis.

## Tech Stack

The RESTIQ application is built using a robust and modern technology stack to ensure performance, security, and scalability.

### Frontend & Mobile

- **React Native**: For building cross-platform mobile applications.
- **HealthKit API (iOS)**: To securely access and utilize health and fitness data from a user's devices.

### Backend & AI

- **Python**: The core language for developing the custom AI sleep analysis model.
- **HTML, CSS**: For any web-based components or future web application interfaces.
- **S3 Bucket**: For scalable and secure storage of user data and analysis results.

### APIs & Services

- **Sleep Data API**: An API to compare user data with normal sleep patterns.
- **Emergency Services API**: To make calls to emergency services if critical health events are detected.
- **Loved Ones Messaging API**: For sending automated messages to emergency contacts.

### Developers

- **Taufeeq Ali** (Project Lead)
- **Dillon Ngyuen** (Frontend Developer)
- **Garrett Smith** (Frontend Developer)
- **Pranav Cheedalla** (Backend Developer)
- **Sreyas Chakka** (Backend Developer)
- **Saharsh Buddhe** (Frontend Developer)

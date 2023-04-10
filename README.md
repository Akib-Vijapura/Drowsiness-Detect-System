# Drowsiness Detect System

This system uses computer vision to detect drowsiness in a person and sends an alert message to a WhatsApp number and also sounds an alarm to prevent accidents caused by drowsy driving or working.

## How it Works
The system continuously analyzes a video feed from a camera to detect the following signs of drowsiness:

- Eye closure
- Yawning
- Head drooping

When the system detects drowsiness, it sends an alert message to a WhatsApp number using the Twilio API and sounds an alarm to alert the person.

## Requirements

To run this system, you will need:

- Python 3
- OpenCV
- dlib
- imutils
- pygame
- Twilio API credentials
- A camera
- dotenv

## Installation

1. Clone this repository to your local machine.
2. Install the required Python packages using pip: pip install opencv-python dlib imutils pygame twilio (for mac user use pip3).
3. Create a Twilio account and obtain your account SID, auth token, and WhatsApp number. You can sign up for a free trial account at https://www.twilio.com/try-twilio.
4. Update the .env file with your Twilio API credentials and WhatsApp number.
5. Run the drowsiness_detect.py file: python drowsiness_detect.py (for mac user use python3).

## Contributing

If you would like to contribute to this project, please feel free to submit a pull request.

## License
This project is licensed under the MIT License

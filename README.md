Working of the Project

This project aims to develop a robust multi-factor authentication (MFA) system that enhances digital security by integrating multiple authentication layers, including graphical passwords, email-password verification, facial recognition using Convolutional Neural Networks (CNN), and QR code authentication.

Features

Two-Phase Graphical Password: Combines recognition and recall stages for enhanced security.
Email-Password Authentication: Traditional credential verification.
Facial Recognition: Utilizes advanced VGG16 and VGG19 models for high accuracy.
QR Code Authentication: Dynamically generated QR codes with personalized metadata for secure identity verification.

How It Works

1. Initialization

The project begins by initializing user registration, where users provide essential details like username, password, personal information, complete CAPTCHA validation, and select images for graphical passwords.
Initial checks include CAPTCHA validation and the selection of key points in images during registration.

2. Core Functionality

Input: The user provides a combination of inputs, including selected images for graphical passwords, email credentials, facial recognition data, and a QR code.
Processing: The project processes these inputs by:
Authenticating the user through a two-phase graphical password system.
Verifying email credentials.
Performing facial recognition using VGG16 and VGG19 models.
Generating and validating a QR code based on personalized metadata.
Output: Upon successful processing, the system grants access to secure web pages, allowing users to upload/download files after additional QR code-based verification.

3. Flow of Operations

Step 1: The user logs in by selecting the correct images in the first phase of the graphical password.

Step 2: The system then authenticates the user's email and password.

Step 3: In the second phase of the graphical password, the user selects key points in an image.

Step 4: Facial recognition is performed, and if there is a 95% match, the user is granted access.

Step 5: The user scans a QR code, to access the requested web page.

4. Error Handling

The project includes error handling for cases such as incorrect image selection, incorrect email credentials, and failed facial recognition.
In the event of an error, the user is prompted to retry the authentication steps or reattempt the graphical password.

5. Finalization

After successful authentication, users are directed to the web homepage where they can upload or download files.
The results of the authentication process are displayed, and secure access is granted upon successful completion of all steps.


Conclusion

This MFA system provides a comprehensive approach to digital security, balancing robust protection with user-friendly features. With a 93% success rate and advanced facial recognition, it is suited for a variety of secure applications.

For a detailed explanation of the project, [watch the video Explanation here]([Beyond Passwords A Multi-Factor Authentication Approach for Robust Digital Security.mp4](https://github.com/Raghavanhk/Projects/blob/main/Beyond%20Passwords%20A%20Multi-Factor%20Authentication%20Approach%20for%20Robust%20Digital%20Security.mp4)).

# Biometric Account Recovery AI Agent

## Overview
This AI-powered system helps users recover hacked personal accounts and delete compromised ones using biometric verification. The system leverages facial recognition and deep learning models to verify users based on their unique biometric signatures.

## Features
- **Biometric Verification:** Uses facial recognition for user authentication.
- **AI-Powered Anomaly Detection:** Detects unauthorized access or duplicate accounts.
- **Account Recovery:** Unlocks personal accounts upon successful biometric verification.
- **Secure Account Deletion:** Allows users to delete affected accounts securely.
- **User-Friendly UI:** Gradio-based interface for easy interaction.

## Tech Stack
- **Python**
- **Gradio (UI Framework)**
- **OpenCV**
- **PyTorch** (Facial Recognition Model)
- **FaceNet (MTCNN + InceptionResnetV1)**

## Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/PSivaMallikarjun/biometric-account-recovery.git
   cd biometric-account-recovery
   ```
2. Install dependencies:
   ```bash
   pip install gradio torch torchvision facenet-pytorch opencv-python numpy
   ```
3. Run the application:
   ```bash
   python main.py
   ```

## Usage
1. **Upload a Biometric Scan:** Provide an image of your face for verification.
2. **Verify Identity:** AI will compare your biometric data with stored records.
3. **Recover or Delete Account:** If verified, you can unlock or remove compromised accounts.

## Future Enhancements
- Integration with fingerprint and iris recognition.
- Multi-device authentication.
- Real-time anomaly detection and alerts.

## License
This project is licensed under the MIT License.

## Contributors
- **Siva Mallikarjun Parvatham** (Project Engineer at Wipro)
- Open for contributions! Fork and submit a pull request.


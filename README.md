

# Face Recognition Attendance System in Django | Source Code

## Overview

A powerful face recognition-based attendance system built with Django, utilizing deep learning models for secure and accurate face detection and verification. This system includes multi-camera support, real-time attendance logging, and an intuitive dashboard. Ideal for institutions and businesses looking to streamline their attendance tracking system and improve security with biometric verification.

---

## Key Features

- **Real-Time Face Recognition:** Integrates MTCNN and InceptionResnetV1 for precise face detection and encoding.
- **Multi-Camera Support:** Configurable for multiple IP and local cameras.
- **Automated Attendance Logging:** Supports automated check-in/check-out, reducing the need for manual intervention.
- **Admin Dashboard:** Access to the student database, attendance records, and customizable settings.
- **Alert Sound on Successful Recognition:** Plays a sound for successful face recognition using Pygame.
- **Secure Login and Access:** Restricts admin access to view, edit, and authorize users, ensuring data security.

---

## Installation Guide

To get started with the project, follow the steps below:

### Requirements

The following Python libraries and dependencies are required to run this project:

- Django
- OpenCV
- Pygame
- MTCNN
- InceptionResnetV1

You can find the complete list of dependencies in the `requirements.txt` file.

### Setup Instructions

1. **Install Dependencies:**

   Run the following command to install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

2. **Configure the System:**

   - Set up your camera devices (IP or local) and configure them in the settings file.
   - Ensure your server is set up to handle real-time face recognition processing.

3. **Run the Server:**

   After completing the configuration, start the Django development server:

   ```bash
   python manage.py runserver
   ```

4. **Access the Dashboard:**

   Once the server is running, access the dashboard at `http://127.0.0.1:8000/` and log in with your admin credentials.

5. **Admin Setup:**

   Create user profiles for each individual (students/employees) and assign them roles as required.

---

## **Paid Version (v2)**

For access to the **Paid Version v2**, which includes advanced features like custom user roles, data export capabilities, and optimized performance for larger deployments, click below:

[Download Paid Version v2 Source Code](https://apycoder.com/product/face-based-student-attendance-system-version-2-0/#google_vignette)

---

## License and Pricing

The Paid Version v3 of the Face Recognition Attendance System offers a range of features designed for scalability and enhanced security. For more details on pricing or to purchase a license, please visit [your website link] or contact us directly.

---

## Support

For any questions or support, feel free to reach out to us through:

- Email: info@apycoder.com
- Phone: +91-9525845873
- Website: www.apycoder.com


# Remisense

<img src="static/images/doctors-animate.svg" align="right" height="300px">

Remisense is a web application developed using Flask, a web framework in Python that aims to assist patients in obtaining the necessary medical care for their needs. The system allows users to register as patients or doctors, book appointments, and predict diseases based on symptoms. Doctors can view and manage appointments, while patients can track their appointments and update their profiles. Additionally, the system provides information on various health-related topics through blog posts and also analyses mental health conditiion of patients.

## Event Name - NinjaSprint Ideathon 1.0

## Contributors

### Team Hackonauts
- Soumalya Bhattacharyya
- Ritam Koley
- Sayan Pan
- Soumyadeep Banerjee
- Dinayan Mallick

## Theme - Healthcare

## Problem Statement
Develop a comprehensive, user-centric Personalized Healthcare Platform integrating a Multi-Disease Predictor Tool and Telemedicine Support System. The system must efficiently analyze patient data, predict multiple diseases, and facilitate remote consultations, ensuring timely interventions and personalized care delivery for improved health outcomes.

# Tech Stacks 

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=html,css,js,py,flask,git,github,php,mysql,netlify,vercel,pycharm,tensorflow,sklearn" />
  </a>
</p>

## Features

1. **User Registration:**
   - Patients and doctors can register using the system.
   - Patients provide basic information such as username, email, and password.
   - Doctors provide additional information, including their type of specialization.

2. **User Login and Logout:**
   - Users can log in to access personalized dashboards.
   - Sessions are managed to ensure secure access, and users can log out when done.

3. **Appointment Booking:**
   - Patients can book appointments with doctors.
   - Doctors can view and manage appointments assigned to them.

4. **Disease Prediction:**
   - A machine learning model predicts diseases based on user-input symptoms.
   - The system uses a Decision Tree Classifier trained on medical data.

5. **Blog Section:**
   - Information on various health-related topics is provided through blog posts.
   - Topics include Transforming Healthcare, Holistic Health, Nourishing Body, and Importance of Games.

6. **Admin Section:**
   - Admins can access an admin dashboard (admin.html).
   - Admins have privileged access to manage the system.

7. **Privacy Policy:**
   - Users can view the privacy policy.

8. **Video Call:**
   - Users can access a video call feature (videocall.html).

9. **Scans Section:**
   - Users can find information on different medical scans, such as brain tumor, lung, and cataract scans.

## Project Structure

- **app.py:** The main Flask application file containing routes and functionality.
- **templates:** Contains HTML templates for rendering web pages.
- **static:** Contains static files such as CSS, images, and data.
- **database.db:** SQLite database file storing user and appointment information.
- **Data:** Contains CSV files used for training and testing the disease prediction model.


## Getting Started

1. Clone the repository: `git clone https://github.com/your-username/Remisense.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the application: `python app.py`

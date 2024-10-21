# AkashGupta-SmartAttendenece
The Smart Attendance Management System uses face recognition technology to automate attendance tracking. Developed by Akash Gupta, it captures facial images, trains a recognition model, and marks attendance automatically. The system sends notifications via email and SMS and includes a user-friendly Tkinter interface for easy operation

# **Smart Attendance Management System using Face Recognition 👦🏻👧**

**A Face Recognition-Based Attendance System**  
This system not only marks your attendance but also sends notifications via email & SMS. It includes a pre-defined instruction chatbot, and the user interface (UI) is built using **Tkinter**, a popular Python framework for desktop applications.

---

## **About the Project** ℹ️

This Smart Attendance System makes attendance management seamless with the power of **face recognition**. The system captures facial data, trains a model, and then recognizes faces to automatically fill in attendance, notifying users instantly. Whether you're a student or a professional, this system can modernize your attendance process.

---

## **Features** 🌟

- **Face Detection**: Automatically captures facial images and stores data.
- **Attendance Marking**: Fills attendance by recognizing your face.
- **Notification System**: Sends notifications via **Email & SMS**.
- **Chatbot Assistance**: Provides a helpful chatbot with predefined instructions.
- **User-Friendly Interface**: Built with **Tkinter** for an intuitive experience.

---

## **How it Works** 🛠️

1. **Add Your Face Data**:  
   Enter your **ID** and **Name** in the input box, then click on "Take Images." The system captures 100 images and stores them in the `data` folder.
  
2. **Train the Model**:  
   After data collection, click on "Train Image" to train the model. It takes approximately 1 minute to train (for 5 people).
  
3. **Detect Faces and Mark Attendance**:  
   Click "Face Detector" to begin face recognition and automatic attendance marking. A `.csv` file will be generated with attendance data, including time and name.

4. **Store Attendance in Database**:  
   Data can be stored in **MySQL Workbench**. Modify the database name as per your requirements.

## **Requirements** 📋

To run the project, install the following Python libraries:

pip install tkinter
pip install opencv
pip install mysql
pip install csv
pip install cv2
pip install pyttsx3
pip install datetime
pip install pytz
pip install twilio
pip install smtp

### **2) Python Version**  
- **Python 3.11.5** or higher

### **3) Software Used**  
- **Pycharm IDE** for development.  
- **MySQL WorkBench** for database management.  
- **Twilio Account** for SMS notifications.

### **4) Hardware Requirements**  
- **Camera**: For capturing facial images.  
- **Storage**: To save images and model data.  
- **Processor**: Requires moderate to high processing power.

---

## **Project Structure** 🏗️  
- **Face Data Collection**: Collects 100 images for each user.  
- **Model Training**: Trains the model based on the collected face data.  
- **Face Recognition**: Detects faces and marks attendance.  
- **Attendance Records**: Stores attendance in a `.csv` file.  
- **Database Integration**: Option to store attendance in **MySQL**.

---

## **Screenshots** 📸  
- **Basic UI**  
![Basic UI](https://github.com/harshit-jain-2109/Smart-Attendance-Management/blob/main/basic%20ui.png)

- **Student Details**  
![Student Details](https://github.com/harshit-jain-2109/Smart-Attendance-Management/blob/main/details.png)

- **Training Portal**  
![Training Portal](https://github.com/harshit-jain-2109/Smart-Attendance-Management/blob/main/training.png)

- **Face Recognition in Action**  
![Face Recognition](https://github.com/harshit-jain-2109/Smart-Attendance-Management/blob/main/recognition.png)

- **Attendance Record**  
![Attendance Record](https://github.com/harshit-jain-2109/Smart-Attendance-Management/blob/main/csv.png)

- **Notification Portal**  
![Notification Portal](https://github.com/harshit-jain-2109/Smart-Attendance-Management/blob/main/notification.png)

- **Chatbot**  
![Chatbot](https://github.com/harshit-jain-2109/Smart-Attendance-Management/blob/main/chatbot.png)

### **Demo Video**  
Watch it in Action 🎥  
[Watch it Here](https://youtu.be/o_Ji7Up4RSM)

---

## **Notes** 📝  
- **High Processing Power**: The project requires a decent system. (Tested on 8GB RAM and 2GB Graphics Card).  
- **Image Quality**: The accuracy of recognition can be affected by the quality of the images.

---

## **Credits** 👏  
Created by **Akash Gupta**.  


---

## **Just Follow Me!** 🙌  
If you find this project helpful, don't forget to **star ⭐ my repository** and **follow ☝️ me** for more cool projects!







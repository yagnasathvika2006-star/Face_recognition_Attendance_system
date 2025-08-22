# Face Recognition Attendance System with Groups & SMS


**Description:**

This Python program is a Face Recognition Attendance System with Group Support and Automated SMS Alerts.
It uses a webcam to recognize students’ faces, mark attendance, group students (e.g., BCA, BCOM, BSC), store all data in Excel, and automatically send SMS to parents of absentees via Twilio.
The GUI is built with Tkinter and provides registration, attendance, group stats, and deletion features.

**Key Features:**

Register students with name, roll, group, mobile, and parent phone number (face image captured via webcam)
Attendance via real-time face recognition
Group-wise attendance stats (present/absent counts)
Stores all attendance and registration in an Excel (.xlsx) file
Sends SMS to parents of absent students (using Twilio API)
GUI for all operations (register, take attendance, show stats, delete students, etc.)

**Advantages**

- Fast, contactless, non-intrusive attendance.
- Automated notifications reduce manual follow-up.
- Group-based reporting aids institutional management.
- Easy record-keeping and Excel export.
- Customizable and extensible for various needs.

**Limitations**

- Requires good lighting and camera placement for accurate recognition.
- Less robust with large numbers of students in poor conditions.
- SMS sending incurs cost and is limited by provider (e.g., Twilio trial restrictions).
- Data privacy and security responsibility is on the institution.
- Not a replacement for formal access control in secure facilities.


**How It Works**

1. **Student Registration**  
   - Operator enters student name, roll number, group (e.g., BCA, BCOM, BSC), student and parent mobile numbers.
   - System captures the student's face via webcam and stores the image locally.
   - All registration data is saved in an Excel file.

2. **Attendance Process**
   - The system uses the webcam to recognize faces in real-time.
   - When a student's face is recognized, their attendance is marked with the current date and time in Excel.
   - Attendance is grouped by the student's group/branch.

3. **Group Statistics and Reporting**
   - Attendance stats (present/absent per group) are displayed in the GUI and stored in Excel.
   - Admin can view group-wise attendance and export or analyze data as needed.

4. **Automated SMS Notifications**
   - After attendance is taken, the system identifies absentees.
   - Using the Twilio API, it sends SMS notifications to the parents of absent students.

5. **GUI Features**
   - Register new students
   - Take attendance
   - View attendance and group stats
   - Delete a single student or all students
   - All via a user-friendly Tkinter interface


**Impact**

- **Improved Efficiency**: Automates the attendance process, saving staff time and reducing manual errors.
- **Enhanced Communication**: Immediate SMS notifications keep parents informed about their child’s absence, fostering accountability and student safety.
- **Transparency & Accountability**: Records are digitally secured and easily auditable, reducing attendance fraud.
- **Data-Driven Decisions**: Grouped attendance stats enable targeted interventions (e.g., extra help for groups with high absenteeism).
- **Contactless & Hygienic**: Reduces the spread of germs compared to manual sign-ins or fingerprint systems.
- **Scalable for Institutions**: Easily adaptable for schools, colleges, or training centers.

**Future Scope**

- **Cloud Integration**: Store attendance and student data on the cloud for remote access, backup, and centralized reporting.
- **Mobile App Extension**: Allow staff to take attendance and view reports via a mobile app.
- **Advanced Analytics**: Integrate dashboards for trends, predictive absenteeism, and performance correlation.
- **Access Control**: Link attendance with smart doors/gates for automated entry/exit control.
- **Multi-Camera Support**: Cover multiple entry points or classrooms.
- **Multi-Factor Authentication**: Add RFID, OTP, or fingerprint as an additional layer for critical environments.
- **Automated Alerts**: Email or WhatsApp notifications in addition to SMS.
- **Language Localization**: Support for multiple languages in the GUI and notifications.
- **Integration with Learning Management Systems**: Automatically update attendance in institutional LMS or ERP software.
- **Face Recognition Improvements**: Use deep learning models for even greater accuracy, handle masks, and support for aging.


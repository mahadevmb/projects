# smart attendence monitoring system by facial recognition using python

refference for facial recognition - https://www.analyticsvidhya.com/blog/2018/08/a-simple-introduction-to-facial-recognition-with-python-codes/

The code runs for 20sec from its execution. Time of execution can be changed before execution mannualy by editing the code with required number of seconds.


Folder named comparing_images contain images of elon musk and bill gates. It is only used to test the core part of code. The next folder students_data contains images of 2 students with naming format "name-usn" (strictly have to be maintained) which are used to compare with the faces to detect in real time video capture and mark the attendence. During video capture the attendence of student will be recorded only if the studens's image present in student_data folder. Unknown students will not be recorded.
Attendance will be recorded in csv for both present and absent. Files automatically will be saved in working directory. As and when the code is executed these records gets refreshed and replaced with new attendance.


note: path for data input need to be taken care for success.

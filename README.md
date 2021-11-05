# SECURITY-CHECK-SYSTEM
A facial authentication system that uses the comparative method
You will need to set your database by uploading photos of authorized people with their names as a file name (jhon.png for example) 
The system will learn the authorized faces and their names, then we will use a video as an input. It could be a live cam or a recorded video
We will use a face detection function, which will detect if there is at least a face in the video source
if a face is found, the system will take some frames from the video to compare the face with faces from the database if the face is identified and authorized the system will give permission to the person to enter and send a notification mail mentioning the individual's name to the admin, otherwise the system will not authorize this person and will send a notification mail containing one of the frames with the individual photo

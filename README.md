# Littering--management--system 
Overview
In many cities, the problem of littering from moving vehicles is growing. Traditional surveillance systems struggle to catch these events in real-time and identify the culprits. This project aims to solve this issue using a computer vision pipeline that performs the following:

Plastic Waste Detection – A YOLOv8 model trained to detect plastic items such as bottles and wrappers thrown from vehicles.
Vehicle Detection – Identifies and localizes the vehicle responsible for the action using a separate YOLOv8 model.
License Plate Detection and OCR – The number plate is detected from the vehicle region, cropped, and passed to an OCR module to extract the alphanumeric registration number.
Data Logging and Evidence Storage – Cropped images of the plastic waste, vehicle, and number plate are saved along with the recognized text for further verification or legal action.
Real-time Feed Processing – The system works on a live video stream or recorded footage for continuous monitoring.
This solution can be used by municipal bodies and smart city projects to automate litter detection, issue fines, and build a cleaner environment.
Features
Plastic Waste Detection using YOLOv8
Vehicle Detection
License Plate Detection
OCR for extracting vehicle number
Cropping and saving evidence images
Organized storage by date and time
Real-time camera feed 
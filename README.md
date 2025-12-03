**Human Emotion Detection App (YOLOv5 + Custom Dataset)** 
 
This project is a human emotion detection system built using YOLOv5 and custom data captured from my webcam. I collected images, labeled them in Label Studio, generated a YOLO-compatible .yaml file, trained a custom model, and tested it on images and real-time webcam feed.

**🚀 Features**
 
Real-time webcam detection

Image-based detection

Custom dataset (self-collected + labeled)

YOLOv5 training workflow included

Clean YOLO data configuration file

**🔧 Workflow**

1️⃣ Data Collection

Used my pc webcam to capture various images of myself

Collected multiple poses and expressions to improve model generalization

Ensured variety in lighting/background for robustness

2️⃣ Annotation with Label Studio

Imported all images into Label Studio

Created bounding box labels for each class (e.g., human face, emotion category)

Exported YOLO-format dataset

Generated a clean data.yaml file mapping classes + dataset paths

3️⃣ Model Training (YOLOv5)

Used Ultralytics YOLOv5

Loaded a pretrained model (yolov5s)

Fine-tuned on my custom dataset

Trained for multiple epochs

Saved checkpoints, best weights, and training logs (not uploaded)

4️⃣ Testing & Evaluation

Tested the model on:

Sample images

Real-time webcam feed

**🔐 Privacy**

For privacy reasons, the dataset, YOLO training outputs, and checkpoints are not uploaded, but the workflow and code are fully included.

**💡 Future Improvements**

Whole app will be developed using the trained model

**👨‍💻 Author**

Sahran Khuwaja 🚀 Maching Learning Engineer | AI & Robotics Enthusiast | Full-Stack Developer | Data Scientist

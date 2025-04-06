🕵️‍♂️ Thief Detection Using YOLOv8
This project implements a custom object detection model using YOLOv8 to detect suspicious human activities that may indicate theft. It includes classes such as:

human

suspicion

📊 Results
Training Info:

Model: YOLOv8 (Ultralytics 8.3.102)

Epochs: 20

Training Time: 2.04 hours

GPU: Tesla T4

mAP@0.5: 83.5%

mAP@0.5:0.95: 54.1%

Class	Images	Precision	Recall	mAP50	mAP50-95
Human	853	0.914	0.816	0.882	0.59
Suspicion	701	0.676	0.725	0.788	0.491
🖼️ Sample Detection Images
![Screenshot from 2025-04-05 19-25-20](https://github.com/user-attachments/assets/463cf47f-aae6-4e95-96a9-b064f40205d0)
![Screenshot from 2025-04-05 19-27-19](https://github.com/user-attachments/assets/fc5a16db-9d2a-4ae7-90c1-b2f89a07b3a1)

🚀 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/thief-detection.git
cd thief-detection
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run inference:

bash
Copy
Edit
yolo detect predict model=weights/best.pt source=your_video.mp4
📬 Contact
For queries or collaborations:
📧 janstylewis11@email.com
🔗 LinkedIn


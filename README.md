# Face-Detection-with-Landmark-using-YOLOv8
The advent of deep learning combined with computer vision has brought forth unparalleled advancements in facial detection and landmark identification. One pivotal player in this transformation has been the YOLO (You Only Look Once) series, setting new milestones in object detection methodologies. Our research is centered on harnessing the YOLOv8 model to optimize face detection processes. We incorporate the OpenCV library for image processing, enhancing detection fidelity through adjustable parameters like confidence and intersection over union (IoU) thresholds. A standout feature of our methodology is its innate ability to adjust to diverse image proportions. This is achieved by innovatively resizing and padding input images, which not only maintains consistency in detection but also augments accuracy. The proposed technique not only demarcates the face but also pinpoints facial landmarks, thus offering a comprehensive spatial map for each detected face. Preliminary results on benchmark datasets underscore the model's dual advantage of speed and precision. Our approach promises not only improved face detection but also paves the way for its amalgamation into expansive facial recognition and analytic platforms.

## Dataset

For our research, we utilized the FaceLandmarks-YOLOv8 dataset during the training phase. This dataset is a specialized collection, tailored for optimizing facial detection and landmark localization using deep learning models. It comprises approximately 100,000 meticulously annotated images, offering a diverse spectrum of facial features, expressions, and orientations. This vast array of data ensures that our model is exposed to varied scenarios, from different ethnicities and lighting conditions to a range of facial expressions. Each image is distinctly annotated to mark crucial facial landmarks such as the eyes' corners, mouth's contours, and nose tip, facilitating precise feature extraction during the model training. Designed to leverage the YOLOv8 algorithm's capabilities, the FaceLandmarks-YOLOv8 dataset served as an ideal foundation for our model's training phase. The diversity embedded within this dataset equipped our model to generalize effectively, ensuring robustness in real-world applications. For the testing phase, we incorporated random images, distinct from the training set, to evaluate our model's adaptability and accuracy in unfamiliar scenarios, further establishing its viability for practical applications in the realm of computer vision.

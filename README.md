# ML-Based-Real-Time-Worker-Safety-Helmet-Detection
🦺 Personalized ML-based Helmet Detection System using ESP32-CAM for real-time worker safety monitoring. Implements pruned CNN, illumination-aware preprocessing, and adaptive thresholding for robust edge inference. Achieved 97.2% accuracy with &lt;170 ms latency, outperforming cloud-based systems in efficiency and reliability.

**RESULTS AND DISCUSSION **
<img width="484" height="478" alt="image" src="https://github.com/user-attachments/assets/aa4f5745-f99f-48c5-babc-35df68ca56bb" />  <img width="484" height="478" alt="image" src="https://github.com/user-attachments/assets/830dd2fb-40af-469f-ab21-271901698720" />


•	No Helmet Result: The system accurately identified the individual without a helmet and marked the detection using a red bounding box along with the label “No Helmet.” This output demonstrates the model’s ability to correctly recognize non-compliance by focusing on head features such as hair texture and head shape. Even under indoor lighting conditions with noticeable shadows and moderate background clutter, the system maintained reliable detection. The personalized thresholding and illumination-aware preprocessing helped reduce misclassification, ensuring that the absence of a helmet was clearly highlighted for safety monitoring purposes 
•	Helmet Result: In the case where the user wore a helmet, the system successfully detected compliance by displaying a green bounding box and the label “Helmet.” The model effectively differentiated the helmet from surrounding elements, confirming its capability to recognize variations in shape, color, and reflective surfaces. Despite similar lighting conditions and background environment, the detection remained stable, indicating strong generalization of the trained model. This reliable classification ensures that workers wearing proper safety gear are correctly identified in real time, supporting automated safety supervision in industrial settings

**CONCLUSION**
The project successfully demonstrates an edge-based, personalized ML-driven helmet detection system implemented on the ESP32-CAM platform. Through adaptive preprocessing, structured pruning, and dynamic thresholding, the system delivers superior accuracy, robustness, and latency performance compared to cloud and server-based solutions. This work contributes to real-time industrial safety monitoring and sets the foundation for scalable, low-cost embedded vision solutions.


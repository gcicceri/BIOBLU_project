# BIOBLU_project

The following is a brief description and potential use of the waste detection and recognition models files described for the article: ''An Intelligent Hierarchical Cyber-Physical System for beach waste management: the BIOBLU case study.'' 

Specifically: 

* **best_detection.pt**:
    * **Description**: This file includes the PyTorch model checkpoint, containing the parameters and weights of the trained YOLOv5 waste detection model.
    * **Usage**: Developers or researchers can use this file to load the pre-trained model for waste detection in their applications or research projects.

* **best_recognition.pt**:
    * **Description**: Similar to "best_detection.pt," this file includes the PyTorch model checkpoint file, containing the parameters and weights of a trained YOLOv5 model used for multiclass/material (plastic/metal/glass/paper) waste recognition. 
    * **Usage**: Developers or researchers can use this file to load the pre-trained model for multiclass/material waste recognition tasks.

* **yolov5l.yaml**:
    * **Description**: This YAML file likely contains configuration parameters for the YOLOv5 detection model, specifying the model architecture, hyperparameters, and data-related settings.
    * **Usage**: Developers and researchers can use this YAML to configure and fine-tune the YOLOv5 model for specific tasks.

* **yolov5n.yaml**:
    * **Description**: Similar to "yolov5l.yaml," this is the YAML file associated with the YOLOv5 waste recognition model.
    * **Usage**: Developers and researchers can use this YAML to configure and fine-tune the YOLOv5 model for specific tasks.


For the training and testing phases of the above-described detection and recognition models, we created and obtained a final dataset, using the proportions of 85% (Training set), 10% (Validation set) and 5% (testing set), respectively. The final dataset is available at the following open-access repository:  https://universe.roboflow.com/bioblu/merged_datasets

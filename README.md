# brain-tumor-segmentation

* Developed by: Apoorva Goswami

* The provided code is a comprehensive implementation for the segmentation of gliomas in pre-operative MRI scans. It begins by setting up the necessary environment, importing essential libraries, and defining the segmentation classes. The dataset, consisting of multimodal MRI scans, is loaded and visualized. The segmentation task employs a U-Net model with a custom dice coefficient loss function, designed to handle the specific classes related to gliomas. The training process is facilitated by a custom DataGenerator class, and the model's performance is evaluated using various metrics such as accuracy, mean IoU, and dice coefficients for different classes. The training history is visualized, showcasing the model's progression over epochs. Additionally, the code includes functions for loading and predicting on new data.

The implementation demonstrates a robust pipeline for medical image segmentation, integrating essential steps from data loading and preprocessing to model training and evaluation. The U-Net architecture, known for its effectiveness in biomedical image segmentation, is employed with a focus on glioma sub-region classification. The use of custom loss functions tailored to the specific classes of interest enhances the model's ability to capture intricate details in the MRI scans. The code also features visualization tools, such as GIF representations of 3D volumes and segmentation masks. Overall, this implementation provides a solid foundation for tackling the challenging task of glioma segmentation in medical imaging datasets.






Intelligent MRI Machine: Disease Prediction and Screening
General Presentation of the Project
Following the absence of medication for certain diseases, it is essential to detect them at an early stage to increase the chances of recovery. This project aims to create a detection and screening model using MRI imaging. For example, if a patient consults a rheumatologist for a skull fracture and the latter recommends an MRI, our program can detect a brain tumor if it exists.

Moreover, MRIs do not generally provide all the information sufficient for diagnosis. Our program assists in:

Helping radiologists recommend a specialist for better diagnosis.
Supporting medical practitioners in making more accurate diagnoses.
Providing patients with early detection of illnesses.
We collected a dataset from several sources, including brain tumors, Alzheimer’s, COVID-19, and chest tumors. Due to time constraints, we focused on MRI images of these four diseases. However, our algorithm has shown excellent performance, and we can expand it to include a broader range of diseases. This way, a patient can receive a comprehensive diagnosis without a doctor's intervention in just a few minutes.

We developed a deep learning model based on Convolutional Neural Networks (CNNs) and built a human-machine interface to be implemented on the MRI scanner.

Market Research
Our research showed that existing algorithms typically focus on detecting a single type of disease (e.g., brain cancer). We developed an algorithm that encompasses multiple diseases detectable by MRI.

Steps Followed in the Code
I. Creation of the Dataset
Collection of datasets of diseases detectable by MRI.
Creation of a global dataset combining all collected datasets.
Cleaning of the global dataset.
Resizing the images.
Visualization of the dataset.
II. Creation of the Machine Learning Model
Training the deep learning model.
Evaluation of the model.
Manual testing of the model and visualization of the images.
Saving the model.
III. Creation of the Human-Machine Interface
Development of the interface using PyCharm, with the model integrated.
Testing and validation of the application.
Note: All code is included in the notebook for clarity.
Dataset Resources in kaggle : 
Alzheimer's MRI Dataset
Chest CT Scan Images
COVID-19 CT Scans
Lung Cancer Dataset

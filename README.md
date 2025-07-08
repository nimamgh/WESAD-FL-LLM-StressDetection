# WESAD-FL-LLM-StressDetection
Multimodal Stress Detection using Deep Learning, Federated Learning, and LLM-enhanced insights on WESAD dataset








## ⚠️ WESAD Dataset

Due to size and license limitations, the WESAD dataset is **not included** in this repository.

To run the code, please follow these steps:

1. Download the dataset manually from the official source:  
   [WESAD UCI Repo](https://ubi29.informatik.uni-siegen.de/usi/data_wesad.html)

2. Extract the dataset and place the folder **outside this project directory**, one level above the project root.

3. Your folder structure should look like this:

project-root/
├── WESAD/ # <-- Place the extracted dataset here
├── WESAD-FL-LLM-StressDetection/ # <-- This GitHub project
│ ├── notebooks/
│ ├── utils/
│ └── ...

4. The code will reference the dataset using relative paths like `../WESAD/S2/S2.pkl`.

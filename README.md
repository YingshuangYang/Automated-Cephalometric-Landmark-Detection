# Automated-Cephalometric-Landmark-Detection
Programming language: The project is implemented entirely in Python 3, utilizing libraries such as PyTorch, Torchvision, NumPy, Pandas, scikit-learn, and Matplotlib.

How to run the code: 
We recommend using Google Colab to run the project, as it provides free access to GPU acceleration, simplifies library setup, and uses Google Drive for data 
management. It can also be run as a Jupyter Notebook locally.
Instructions for running with Google Colab:
1.	Upload the dataset and Advanced-ML-Project.ipynb file into Google Drive. Alternatively, you can already access the code file here: https://colab.research.google.com/drive/1O54duCvhP6V4fRzbMQqAjjNLSpXF6CkS?usp=drive_link. The data folder is here: https://drive.google.com/drive/folders/1M37O953x2967TNIrlQHACGGfeafixpPJ?usp=sharing.
2.	Adjust any file paths in the code if necessary. This step should not be necessary if you use the Drive links, but might be necessary if you upload the files to drive yourself. The data should organized as follows:
/AML/data/
    ├── landmarks.csv
    └── cepha400/
        └── cepha400/
            ├── image1.png
            ├── image2.png
            ├── …..  
3.	Change Runtime → Change runtime type → Select T4 GPU
4.	Run the script cells step by step (make sure runs the first code “drive.mount”) to 
connect to Google Drive

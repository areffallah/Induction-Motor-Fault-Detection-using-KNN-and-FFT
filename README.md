# Induction-Motor-Fault-Detection-using-KNN-and-FFT
electric motors are critical components of a modern system. Their failure causes sever impacts on operation. Monitoring of the electric motors using vibration sensors has become a popular method in predictive analysis. Any slight imbalances, bearing defect, Rotor defect, changes in load, loose feet, and etc. can result in the failure of the motor. In this project, experimental data recorded through 8 sensors of acceleration, rotation, and sound are used to identify faulty induction motor.

# Instruction
Dataset is downloaded from kaggle: https://www.kaggle.com/datasets/uysalserkan/fault-induction-motor-dataset
Fast Fourier Transformation (FFT) is used to filter out noisesn and cleanout the dataset. Then these data are used for training and testing of a KNN sklearn classifier. At the end, test data are classified to identify the faulty signals.

KNN classifier 

Details about dataset can be found in the following link:

http://www02.smt.ufrj.br/~offshore/mfs/page_01.html

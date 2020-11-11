# remote-HR-estimation (ECSE 2020 Project)
This project was made for the final year project of 2020 for Monash University Electrical Engineering. Implementation of the rPPG and rBCG methods are completed by Jerry Li and Emily Pha.

The code implements the 2SR [1] rPPG algorithm for heart rate estimation, alongside using OpticalFlow to do local motion estimation in order to track head motion for rBCG.

This repository only contains the refined solutions, if further information is required as to the entire commit history, please visit: https://github.com/Sangeo/ECE-2020-FYP.

This solution requires the installation of the following dependencies:
- OpenCV (https://opencv.org/)
- FFTW (http://www.fftw.org/)
- Python 3.8 (https://www.python.org/downloads/release/python-380/)
- Matplotlib C++ (https://github.com/lava/matplotlib-cpp)

[1] W. Wang, S. Stuijk, and G. de Haan, “A novel algorithm for remote photoplethysmography : spatial subspace rotation,” IEEE Transactions on Biomedical Engineering, vol. 63, no. 9, pp. 1974–1984, Sept. 2016.

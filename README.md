# LicencePlateRecognition

This project is created for Introduction to Machine Learning class on FESB (Faculty of Electrical Engineering, Mechanical Engineering and Naval Architecture in Split). It was worked on in collaboration with Katarina Vuknić and can be found on her profile (https://github.com/katarinavuknic/licensePlates/tree/master) too.

The project was made using code from [quangnhat185](https://github.com/quangnhat185/Plate_detect_and_recognize) and following the steps with later changing some values to better recognise Croatian licences plates, however for our plates it still lackes precision.

The libraries and tools used are mostly the same and are listed here:
    Python      3.7.9
    Kerass      2.3.1
    Tensorflow  1.14.0
    Numpy       1.17.4
    Matplotlib  3.3.4
    OpenCV      4.5.1.48
    sklearn

DetectLicencePlate file detectes licence plate on a picture while segmentRecogniseCharacters file recognises characters from a picture od a plate.
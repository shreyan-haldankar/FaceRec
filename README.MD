# Facial Recognition Based Attendance System

## Prerequisites
- [x] CMake, Dlib
- [x] Python 3.9
### Windows
Install Microsoft C++ build tools from here - https://visualstudio.microsoft.com/downloads/?q=build+tools
### Linux
```sudo apt install cmake```

The first thing to do is to clone the repository:

```sh
$ git clone https://github.com/shreyan-haldankar/FaceRec.git
$ cd FaceRec
```

Create a virtual environment
```shell
python -m venv env
```
Activate the virtual environment
```shell
.\env\Scripts\activate
```

Install dependencies using pip:

```shell
pip install -r requirements.txt
```

Once `pip` has finished installing the dependencies:
<br>
Run the ``` mainwindow.py``` file 

In order to test the Face Recognition System, insert a photo of a person in the Images Attendance Folder, and then run the ```
mainwindow.py ``` file and scan the face of the person and Clock In. Then Open the Attendance.csv file to check whether the person has Clocked In.


# Resources

* [Adam Geitgey](https://medium.com/@ageitgey/machine-learning-is-fun-part-4-modern-face-recognition-with-deep-learning-c3cffc121d78) : How Face Recognition works

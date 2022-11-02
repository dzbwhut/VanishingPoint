# VanishingPoint

This project aims to find the vanishing point of the images.
Code is available in Python and C++.

You can find complete explaination of the logic and documentation of the code [here](https://www.scribd.com/document/510883652/Vanishing-Point).


### Installation

Clone this repository and follow the steps below to run the code.

##### Python
* Install the following dependencies.
    * `opencv-python`
    * `numpy`
* Set the path of the folder containing input images in the file `main.py` at line 141.
* Run the code using terminal
    * Navigate to the cwd.
    * Run: `$ python main.py`
    
#### C++
* Make sure you have OpenCV binaries installed.
* Set the path of the folder containing input images in the file `main.cpp` at line 199.
* Run the file `main.cpp`. For CMake users, `CMakeLists.txt` is also created.

#### references
* [Calabrition of vanishing-points](https://wenku.baidu.com/view/4c2f0e46bb4ae45c3b3567ec102de2bd9605de33.html?_wkts_=1667347905086&bdQuery=%E6%B6%88%E5%BD%B1%E7%82%B9%E6%A0%87%E5%AE%9A%E6%B3%95): Error of reprojection: 0.0043 pix/7 checkerboard image.
* [Calabrition of orthogonal vanishing-points](https://max.book118.com/html/2018/1218/7032060015001165.shtm): natural scene, f,v0,v0, 0.8 pix/1 image.

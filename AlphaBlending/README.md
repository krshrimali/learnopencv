Please see the following [blog post](https://www.learnopencv.com/alpha-blending-using-opencv-cpp-python/) for more details about this code

<img src="https://www.learnopencv.com/wp-content/uploads/2017/04/alpha-blending-using-opencv-1024x721.jpg"></img>

[Alpha Blending using OpenCV (C++ / Python)](https://www.learnopencv.com/alpha-blending-using-opencv-cpp-python/)

## Usage 

Files used for inputs are hard-coded and can be changed by editing the filenames used in `imread()` functions in respective files. 

**Python**

`python3 alphaBlend.py`

**C++**

```bash
g++ alphaBlend.cpp `pkg-config opencv --cflags --libs -o alphaBlend
./alphaBlend
```

A tony demo of human detection using HOG

## Requirements:
* cmake
download from the [officer website](https://cmake.org/download/)
> 
    sudo ./bootstrap
    sudo make
    sudo make install
    cmake --version
* opencv,any version is OK
download from the [officer website](https://opencv.org/)
> 
    unzip opencv-2.4.12.zip
    cd opencv-2.4.12
    mkdir  build
    cd build
    cmake..
    make -j8
    make install
    pkg-config --modversion opencv


## Start:
    sh run.sh

## result:
|  Red:Hog+svm  |Green:Hog+cascade|
|---------------|-----------------|
|      461ms    |       24ms      |
<div>
<img width="400" height="400" src="https://github.com/watersink/hog/raw/master/img/1.jpg"/>
<img width="400" height="400" src="https://github.com/watersink/hog/raw/master/img/result.jpg"/>
</div>

## details:
can be found [here](http://blog.csdn.net/qq_14845119/article/details/52187774)

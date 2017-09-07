# xfOpenCV/examples
Each of the folders inside examples folder aims to evaluate at least one of the xfOpenCV kernels.

Each example folder consists of an include folder and a data folder, which contain the xfOpenCV header files and the test images respectively. Additionally, each example contains the following files -

| File Name | Description |
| :------------- | :------------- |
| xf_headers.h | Contains the headers required for host code (the code that runs on ARM) |
| xf_<example_name>_config.h, xf_config_params.h | Contains the hardware kernel configuration information and includes the kernel headers |
| xf_<example_name>_tb.cpp | Contains the main() function and evaluation code for each of the xfOpenCV kernels |
| description.json | Contains the project configuration information for the SDx GUI |
| Makefile | Makefile to build the example in commandline |


The following table lists which xfOpenCV kernel(s) each example aims to evaluate -

| Example | Function Name |
| :------------- | :------------- |
| accumulate | accumulate |
| accumulatesquared | accumulateSquare |
| accumulateweighted | accumulateWeighted |
| arithm | absdiff, add, subtract, bitwise_and, bitwise_or, bitwise_not, bitwise_xor |
| bilateralfilter | bilateralFilter |
| boxfilter | boxFilter |
| canny | Canny |
| channelcombine | merge |
| channelextract | extractChannel |
| convertbitdepth | convertTo |
| customconv | filter2D |
| cvtcolor | iyuv2nv12, iyuv2rgba, iyuv2yuv4, nv122iyuv, nv122rgba, nv122yuv4, nv212iyuv, nv212rgba, nv212yuv4, rgba2yuv4, rgba2iyuv, rgba2nv12, rgba2nv21, uyvy2iyuv, uyvy2nv12, uyvy2rgba, yuyv2iyuv, yuyv2nv12, yuyv2rgba |
| dilation | dilate |
| erosion | erode |
| fast | fast |
| gaussianfilter | GaussianBlur |
| harris | cornerHarris |
| histogram | calcHist |
| histequialize | equalizeHist |
| hog | HOGDescriptor |
| integralimg | integral |
| lkdensepyrof | DensePyrOpticalFlow |
| lknpyroflow | DenseNonPyrLKOpticalFlow |
| lut | LUT |
| magnitude | magnitude |
| meanshifttracking | MeanShift |
| meanstddev | meanStdDev |
| medianblur | medianBlur |
| minmaxloc | minMaxLoc |
| otsuthreshold | OtsuThreshold |
| phase | phase |
| pyrdown | pyrDown |
| pyrup | pyrUp |
| remap | remap |
| resize | resize |
| scharrfilter | Scharr |
| sobelfilter | Sobel |
| stereopipeline | StereoPipeline |
| stereolbm | StereoBM |
| svm | SVM |
| threshold | Threshold |
| warpaffine | warpAffine |
| warpperspective | warpPerspective |
| warptransform | warpTransform |

# Yolov3

Nos permite detectar y predecir objetos en una imagen o video en tiempo real, basado en aprendizaje profundo, requiere observar la imagen una sola vez para realizar la predicción, siendo un algoritmo más rápido en detección de objetos en imágenes y videos.

A continuación se muestra un ejemplo del uso de Yolov3

[![Imagen 1](/readme_image/prediccion1.PNG)](readme_image/prediccion1.PNG)

[![Imagen 2](/readme_image/prediccion2.PNG)](readme_image/prediccion2.PNG)


# Teconolgias usadas
Windows or Linux
CMake >= 3.12: https://cmake.org/download/
CUDA 10.0: https://developer.nvidia.com/cuda-toolkit-archive (on Linux do Post-installation Actions)
OpenCV >= 2.4: use your preferred package manager (brew, apt), build from source using vcpkg or download from OpenCV official site (on Windows set system variable OpenCV_DIR = C:\opencv\build - where are the include and x64 folders image)
cuDNN >= 7.0 for CUDA 10.0 https://developer.nvidia.com/rdp/cudnn-archive (on Linux copy cudnn.h,libcudnn.so... as desribed here https://docs.nvidia.com/deeplearning/sdk/cudnn-install/index.html#installlinux-tar , on Windows copy cudnn.h,cudnn64_7.dll, cudnn64_7.lib as desribed here https://docs.nvidia.com/deeplearning/sdk/cudnn-install/index.html#installwindows )
GPU with CC >= 3.0: https://en.wikipedia.org/wiki/CUDA#GPUs_supported
on Linux GCC or Clang, on Windows MSVC 2015/2017/2019 https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=Community


# Versiones

	Yolov3 

# Sitios para descargar SVG

En los ejemplos de este repositorio han sido descargados de los sitios siguientes:
https://pjreddie.com/darknet/yolo/
https://pjreddie.com/darknet/install/
https://github.com/AlexeyAB/darknet
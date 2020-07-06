# nrf-tensorflow
Tensorflow on nRF5340
Use NCS to include [Tensroflow Lite Micro](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/lite/micro) as a library.

## Operating system
As far as I know, Tensorflow Lite Micro is made for use with Linux. 

### Windows
If you are using Windows, you are mostly on your own. However, [this](https://www.wikihow.com/Install-Ubuntu-on-VirtualBox) might be a good place to begin.

## Install
After you clone this repository you need to load the tensorflow submodule>
```
git submodule init
git submodule update
```

You also need to install the [NCS](https://developer.nordicsemi.com/nRF_Connect_SDK/doc/latest/nrf/gs_installing.html) repository.




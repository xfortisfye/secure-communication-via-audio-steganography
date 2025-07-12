# secure-communication-via-audio-steganography

## Description
A secure communication application that is able to perform audio steganography as [seen here](https://www.youtube.com/watch?v=c1NPYY3F3tM).

## Setting Up
### Install Dependencies
1. Install PyQt5
```bash
> cd \Path\to\root-folder
> pip install PyQt5
```
2. Install pycryptodome
```bash
> cd \Path\to\root-folder
> pip install pycryptodome
```
If above doesn't work, uninstall the following and try again.
```bash
> pip uninstall pycrypto
> pip uninstall crypto
> pip uninstall pycryptodome
> pip uninstall pycryptodomex
```
3. Install cryptography
```bash
> cd \Path\to\root-folder
> pip install cryptography
```
4. Install PyAudio
```bash
> cd \Path\to\root-folder
> pip install wheel
> pip install PyAudio
```
If above doesn't work, [Install](https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio) your respective wheel version to `\Path\to\ict2205-calltography`
Checking of python version: `> python`
```bash
> pip install PyAudio-0.2.11-cp39-cp39-win_amd64.whl
```
5. Install [codecs](https://files3.codecguide.com/K-Lite_Codec_Pack_1610_Full.exe)
6. Install [make](https://github.com/xfortisfye/303-see-other/blob/main/dependencies.md#make) (Optional)

## Running the Project
### Option 1: Using Python
1. Run server.py (currently is set to localhost)
```bash
> cd \Path\to\root-folder
> py server.py
```
2. Run main.py
```bash
> cd \Path\to\root-folder
> py main.py
```

### Option 2: Using GNU Make (For main.py only)
1. To run the program
```bash
> cd \Path\to\root-folder
> make
```
2. To clean compiled files (.pyc)
```bash
> make clean
```


## Collaborators
| Name                        | GitHub                                         |
| --------------------------- | ---------------------------------------------- | 
| **Ong Tiong Poh**           | [@Swipaaar](https://github.com/Swipaaar)       |
| **Poh Xiang Bin**           | [@xenbon](https://github.com/xenbon)           |
| **Dylan Yong Kenn Litt**    | [@milosaur](https://github.com/milosaur)       | 
| **Nicholas Poon Keet Hoe**  | [@roodysfun](https://github.com/roodysfun)     |
| **Chua Chiang Sheng, Andy** | [@xfortisfye](https://github.com/xfortisfye)   |

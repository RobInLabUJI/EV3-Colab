# EV3-Colab

Colab notebooks for programming LEGO Mindstorms EV3 in Python 3.

The code consists of [Jupyter notebooks](http://jupyter.org/) 
hosted in [Google Colaboratory](https://research.google.com/colaboratory/faq.html)
but running locally in a laptop or desktop computer with Ubuntu Linux 20.04 
that communicates with the robots via Bluetooth.

The EV3 is running its standard firmware, no need to use a SD card.

## Prerequisites - Ubuntu 20.04

* Python 3.x
* [Jupyter notebook](http://jupyter.readthedocs.io/en/latest/install.html)
* [PyBluez](https://github.com/karulis/pybluez)
* [ev3-python3](https://github.com/ChristophGaukel/ev3-python3)

## Setup

Run the install script:

`./script/install.bash`

Activate Bluetooth and pair your robot and computer:

`./script/pair.bash`

The script launches [`bluetoothctl`](https://www.makeuseof.com/manage-bluetooth-linux-with-bluetoothctl/).
Use the command `scan on` for finding your device, then use `pair <mac_address>` for pairing it.

## Usage

### EV3

Switch it on, that's all!

### Computer

Run the script `./script/run.bash` in the root folder, and enjoy!

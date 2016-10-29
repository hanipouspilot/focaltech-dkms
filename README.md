# focaltech-dkms
Focaltech DKMS driver for kernel 3.19

Install the driver by

sudo cp -R . /usr/src/focaltech-1.5

sudo dkms add -m focaltech -v 1.5

sudo dkms install -m focaltech -v 1.5

Installation of opencv dependeincies

METHOD 1:
The following are the dependencies required for the installation of opencv installation

sudo apt-get install build-essential
sudo apt-get install cmake git libgtk2.0-dev pkg-config libavcodec-dev libavformat-dev libswscale-dev
sudo apt-get install python-dev python-numpy libtbb2 libtbb-dev libjpeg-dev libpng-dev libtiff-dev libjasper-dev libdc1394-22-dev

Run the above commands in terminal

METHOD -2: 
git clone github.com/PrasannaIITH/opencv-dep
cd opencv-dep
sudo chmod a+x opencv-dep.sh
sudo ./opencv-dep.sh


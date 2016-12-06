# swift_install_instruction on ubuntu 

step 1: sudo apt-get install clang libpython2.7 

step 2: Add this to /etc/apt/sources.list
deb http://cz.archive.ubuntu.com/ubuntu xenial main

step 3: sudo apt-get update

step 4: apt-get install libicu-dev libicu55

step 5: Download the source of swift from swift.org

step 6: Use tar to extract

step 7: export PATH=/usr/local/src/swift-3.0.1-RELEASE-ubuntu16.04/usr/bin/:"${PATH}"

step 8: run swift command

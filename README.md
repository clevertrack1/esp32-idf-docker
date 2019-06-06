# esp32-idf-docker [![Build Status](https://travis-ci.com/cranphin/esp32-idf-docker.svg?branch=master)](https://travis-ci.com/cranphin/esp32-idf-docker)
My esp32-idf building docker file

This is a very basic Docker file + Travis build configuration which builds a esp32-idf Docker image.
I use it by volume mounting my source folder into the container, and then running any commands,
but that's just one option.

Flashing is a bit harder, on Linux you can mount the USB dev into the container,
on Windows I use some fancy scripts and tricks to flash over TCP :)

A new image should be built daily, and available as [cranphin/esp32-idf](https://hub.docker.com/r/cranphin/esp32-idf) on Docker hub.

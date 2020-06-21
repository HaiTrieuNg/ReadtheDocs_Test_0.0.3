Getting Started
===============

In this chapter, our aim would be to get our development setup functional, and also to get an understanding for the development tools and repositories available around ESP32.

Development Overview
^^^^^^^^^^^^^^^^^^^^

The following diagram depicts the typical developer setup for development with ESP32.

.. image:: pic1.png
     :width: 400px
     :align: center
     :height: 200px
     :alt: alternate text

The PC, or the Development Host can be any of Linux, Windows or Mac. The ESP32 based development board is connected to the Development Host over a USB cable. The Development Host has the ESP-IDF (Espressif’s SDK), the compiler toolchain and the code for your project. The development host builds this code and generates the executable firmware image. The tools on the Development Host then download the generated firmware image on to the development board. As the firmware executes on the development board, the logs from the firmware can be monitored from the Development Host.

ESP-IDF
^^^^^^^

ESP-IDF is Espressif’s IoT Development Framework for ESP32.
ESP-IDF is a collection of libraries and header files that provides the core software components that are required to build any software projects on ESP32.
ESP-IDF also provides tools and utilities that are required for typical developer and production usecases, like build, flash, debug and measure.
ESP32-PCD8544
=============

Overview
--------

ESP32-PCD8544 is dedicated driver implementation of PCD8544 LCD controller (a.k.a `Nokia 5110 LCD <https://www.google.co.jp/search?q=nokia5110+lcd&tbm=isch>`_) for `Espressif IoT Development Framework <https://github.com/espressif/esp-idf>`_.

Application Examples
--------------------

* "Hello world" example - :example:`hello_pcd8544`
* Draw lines via frame buffer - :example:`draw_lines`
* Positioning and formatting texts - :example:`print_texts`
* Drawing bitmap images - :example:`draw_bitmaps`
* Miscellaneous mode controls - :example:`control_modes`
* Plotting touch sensor values - :example:`plot_touch_sensor`
* Plotting high frequency analog microphone input with DMA - :example:`plot_microphone_input`

( more example projects will be written here )

API Reference
-------------

.. include:: /_build/inc/pcd8544.inc

.. include:: /_build/inc/pcd8544_pin.inc

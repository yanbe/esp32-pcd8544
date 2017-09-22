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
* Plotting Touch sensor values - :example:`plot_touch_sensor`

( more example projects will be written here )

.. See :example:`get-started` directory of ESP32-PCD8544 examples that contains the following applications:
   * Using contrast control - :example:`contrast`
   * Using power-down mode - :example:`power-down`
   * Using display-mode - :example:`display-mode`
   * Using all features to plot graph with small battry use :example:`graph`
   * Using animated graph from ADC signal :example:`signal`
   * Free memory and SPI bus / device for other use :example:`free-mem`
   * Benchmark code for DMA enabled/disabled and native SPI pins enabled/ disabled configuration :example:`benchmark`

API Reference
-------------

.. include:: /_build/inc/pcd8544.inc

.. include:: /_build/inc/pcd8544_pin.inc

***********
Get Started
***********

This document is intended to introduce Nokia 5110 LCD as cheap graphic LCD for ESP-IDF users.

Introduction
============

PCD8544 is a model name of graphic controller integrated into `Nokia 5110 <https://en.wikipedia.org/wiki/Nokia_5110>`_'s  LCD. Nokia 5110 is old-style GSM mobile phones that was available in 1998-2001.

Nokia 5110 seems widely sold over the world in GSM era. But people were already upgraded from them to smartphones now 2010s. Recent years, aimed at DIY electronics developers (a.k.a. makers), some Chinese manufacturers started disassemble no-more-used Nokia 5110's LCD with controllers, then hand-assembled modules with dedicated PCB + LED. From the surrrounding background, we can get these types of LCD module in very cheap cost (around $2 in Aliexpress.com) comparing with general graphic LCD's price (around $7-$15).

`Wholesale nokia 5110 Gallery - Buy Low Price nokia 5110 Lots on Aliexpress.com <https://www.aliexpress.com/w/wholesale-nokia-5110.html?SortType=price_asc>`_

As far as I know, this is the cheapest graphic LCD generally availble in the world. It have small monochrome 84x48 pixels. But we can still expect that it works and enjoyable for electronic DIY projects: we can display sensor values plot them to small graphs, render monochrome raster graphics, etc by integrating an Nokia 5110 LCD to our project.

The problem was there were no available libraries dedicated to `ESP-IDF <https://github.com/espressif/esp-idf>`_ (Espressif IoT Devlopment Framework) is . I could found some libraries works in Arduino framework, but nor ESP-IDF native SPI support or efficient implementation. That's why I started to developing ESP32-PCD8544 library.

Warning: Assemble Quality of Nokia 5110 LCD
===============================================

Though Nokia 5110 LCD is very cheap graphic LCD, I exprienced around 50% failure rate based on 4 orders from different shops. There are two type of PCB (red one and blue one), and some manufacturers are behind shops. There are variations on assemble quality by manufacturers but we cannot choose manufacterer directory. As far as I know, I recommend (but of cource no guarantee) following shops because I could purchese working indivisuals.

`LCD Module LCD5110 Board Blue Screen Backlight Display Module 5110 Wholesale-in LCD Modules from Electronic Components & Supplies on Aliexpress.com | Alibaba Group <https://www.aliexpress.com/item/LCD-Module-LCD5110-Board-Blue-Screen-Backlight-Display-Module-5110-For-Arduino-Wholesale/32456107295.html>`_

`LCD Module Display Monitor White backlight adapter PCB 84*48 84x84 5110 Screen For Arduino-in LCD Modules from Electronic Components & Supplies on Aliexpress.com | Alibaba Group <https://www.aliexpress.com/item/84-48-LCD-Module-White-backlight-adapter-pcb-for-Nokia-5110/1859113549.html>`_

Note that in Aliexpress.com allow us to open dispute to the shop which we purchesed items. If delivered Nokia 5110 LCD was are not working individual, you can open dispute with evidence (photos) and then Aliexpress will judge that it should be refunded.


Related Links
=================

* `Zero Cost 84×48 Graphical LCD for the Freedom Board | MCU on Eclipse <https://mcuoneclipse.com/2012/12/16/zero-cost-84x48-graphical-lcd-for-the-freedom-board/>`_ (external site)
* `How to use the Nokia 5110 LCD Module at Arduino <http://www.avdweb.nl/arduino/hardware-interfacing/nokia-5110-lcd.html>`_ (external site)


.. toctree::
   :maxdepth: 1

* :ref:`genindex`

Configuration Options
*********************

Introduction
============

ESP-IDF uses Kconfig_ system to provide a compile-time configuration mechanism. Kconfig is based around options of several types: integer, string, boolean. Kconfig files specify dependencies between options, default values of the options, the way the options are grouped together, etc.

Applications developers can use ``make menuconfig`` build target to edit components' configuration. This configuration is saved inside ``sdkconfig`` file in the project root directory. Based on ``sdkconfig``, application build targets will generate ``sdkconfig.h`` file in the build directory, and will make sdkconfig options available to component makefiles.

Configuration Options Reference
===============================

Subsequent sections contain the list of available ESP32-PCD8544 options, automatically generated from Kconfig files. Note that depending on the options selected, some options listed here may not be visible by default in the interface of menuconfig.

By convention, all option names are upper case with underscores. When Kconfig generates sdkconfig and sdkconfig.h files, option names are prefixed with ``CONFIG_``. So if an option ``ENABLE_FOO`` is defined in a Kconfig file and selected in menuconfig, then sdkconfig and sdkconfig.h files will have ``CONFIG_ENABLE_FOO`` defined. In this reference, option names are also prefixed with ``CONFIG_``, same as in the source code.

.. include:: /_build/inc/kconfig.inc

.. _Kconfig: https://www.kernel.org/doc/Documentation/kbuild/kconfig-language.txt

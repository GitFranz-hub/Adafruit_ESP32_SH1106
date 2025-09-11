# Adafruit_ESP32_SH1106
Adafruit SH1106 GFX Library

This is the core graphics library for all our displays, providing a common set of graphics primitives (points, lines, circles, etc.). It needs to be paired with a hardware-specific library for each display device we carry (to handle the lower-level functions).

Adafruit invests time and resources providing this open source code, please support Adafruit and open-source hardware by purchasing products from Adafruit!

Written by Limor Fried/Ladyada for Adafruit Industries. BSD license, check license.txt for more information. All text above must be included in any redistribution.

Recent Arduino IDE releases include the Library Manager for easy installation. Otherwise, to download, click the DOWNLOAD ZIP button, uncompress and rename the uncompressed folder Adafruit_GFX. Confirm that the Adafruit_GFX folder contains Adafruit_GFX.cpp and Adafruit_GFX.h. Place the Adafruit_GFX library folder your ArduinoSketchFolder/Libraries/ folder. You may need to create the Libraries subfolder if its your first library. Restart the IDE.

You will also need to install the latest Adafruit BusIO library. Search for "Adafruit BusIO" in the library manager, or install by hand from https://github.com/adafruit/Adafruit_BusIO

Roadmap

The PRIME DIRECTIVE is to maintain backward compatibility with existing Arduino sketches -- many are hosted elsewhere and don't track changes here, some are in print and can never be changed! This "little" library has grown organically over time and sometimes we paint ourselves into a design corner and just have to live with it or add progressively more ungainly workarounds.

If you must have one of these features, consider creating a fork with the features required for your project...it's easy to keep synced with the upstream code.

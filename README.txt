
                   _   _ _ ___ _
                  | | | | | __/ \
                  | |_| U | _| o | - The Lightweight USB
                  |___|___|_||_n_|    Framework for AVRs
                =========================================
                          Written by Dean Camera
                  dean [at] fourwalledcubicle [dot] com

                         http://www.lufa-lib.org
                =========================================

               LUFA is donation supported. To support LUFA,
             please donate at http://www.lufa-lib.org/donate

               Released under a modified MIT license - see
                  LUFA/License.txt for license details.

                For Commercial Licensing information, see
                     http://www.lufa-lib.org/license


LUFA library with autotools support.
This fork excludes all documentation and demos, please check the original abcminiuser/lufa github repo for that.

Example usage:

../configure --host=avr --prefix=/usr/local/avr-gcc/ CFLAGS='-mmcu=atmega32u4 -DBOARD=MICRO -DF_CPU=16000000UL -DF_USB=16000000UL -Os -ffunction-sections'

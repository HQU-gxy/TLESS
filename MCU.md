# MCU 

## Hub

- [W806](https://www.cnx-software.com/2021/11/08/winnermicro-w806-240-mhz-mcu-2-development-board/)/[Air103](https://wiki.luatos.org/chips/air103/index.html) (XT804) w/o RF
- [STM32F103C8T6](https://www.st.com/en/microcontrollers-microprocessors/stm32f103c8.html) clone. e.g. [Air32F103CBT6](https://wiki.luatos.org/chips/air32f103/index.html) (Cortex M3)
- [Air105](https://wiki.luatos.org/chips/air105/mcu.html?highlight=air105) (Cortex M4)
- Espressif [ESP32](https://www.espressif.com/en/products/socs/esp32)/[ESP32-C3](https://www.espressif.com/en/products/socs/esp32-c3) w/o RF
- [CH32V307](https://www.wch-ic.com/products/CH32V307.html) (Qingke V4F) 

### Real-time OS

- [FreeRTOS](https://www.freertos.org/) only include task scheduler, no hardware abstraction layer, come natively with ESP-IDF
- [Zephyr](https://www.zephyrproject.org/)
- [ThreadX](https://github.com/eclipse-threadx/threadx)
- [RT-Thread](https://www.rt-thread.org/)

### Note

- XT804 require a special build of gcc (see [c-sky/toolchain-build](https://github.com/c-sky/toolchain-build))
- There's a bunch of STM32 clone to choose from

## Helmet

- [Air001](https://wiki.luatos.org/chips/air001/index.html) (Cortex M0+)
- [CH32V203](https://www.wch-ic.com/products/CH32V203.html) (Qingke V4B)
- [CH32V003](https://www.wch-ic.com/products/CH32V003.html) (QingKe RISC-V2A)

Bare-metal due to simplicity and limited resources.

- [intel/compile-time-init-build](https://github.com/intel/compile-time-init-build)
- [Coroutines (C++20)](https://en.cppreference.com/w/cpp/language/coroutines)
- [[Boost::ext].SML](https://boost-ext.github.io/sml/index.html)

## Pistol

Stick with [STM32G031G8](https://www.st.com/en/microcontrollers-microprocessors/stm32g031g8.html) Series for now since we're using this.

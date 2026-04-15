\# STM32 DHT22 HAL Library



A lightweight and robust C library for reading the DHT22 (AM2302) temperature and humidity sensor using STM32 HAL (Hardware Abstraction Layer). 



\## 📁 Repository Structure

\* `inc/`: Contains the header file `DHT22.h`

\* `src/`: Contains the source file `DHT22.c`

\* `examples/`: Contains `main\_example.c` showing basic initialization and reading data.



\## ⚙️ Requirements

\* STM32 Microcontroller (Tested on STM32F4 series).

\* STM32CubeIDE or any IDE supporting STM32 HAL.

\* A Hardware Timer (e.g., TIM11) configured to generate a \*\*1-microsecond delay\*\* (crucial for sensor communication).



\## 🚀 How to Use

1\. Clone this repository or download the ZIP file.

2\. Copy `DHT22.h` to your project's `Core/Inc` folder.

3\. Copy `DHT22.c` to your project's `Core/Src` folder.

4\. Open `examples/main\_example.c` to see how to initialize the timer and read the temperature/humidity data.



\## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.


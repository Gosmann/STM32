# STM32
STM32 peripheral examples with HAL

Most of these example codes are based the STM32L432 Nucleo-32 board, but since HAL makes programs rather generic it has compatibility with most STM32 nucleo boards. Important to say that in order to configure the registers accourdingly it uses the CubeMX software, which files are also available in the projects.

TIM2_IT: configures TIMER 2 to generate an interrupt on overflow. Blinks the board default LED on this interrupt for testing purposes.

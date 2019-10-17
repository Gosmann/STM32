# STM32
STM32 peripheral examples with HAL

Most of theses example codes are based the STM32L432 Nucleo-32 board, but since HAL makes programs rather generic it has compatibility with most STM32 nucleo boards. Important to say that in order to configure the registers accourdingly it was used the CubeMX software, which files are also available in the project.

TIM2_IT: configures TIM2 to generate and interrupt on overflow. Blinks the board default LED on this interrupt for testing purposes.

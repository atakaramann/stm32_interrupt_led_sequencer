## STM32 Interrupt-Driven LED Sequencer

**Board:** STM32 Nucleo F413ZH  
**IDE:** STM32CubeIDE  
**Library:** HAL  

### What it does
Button press cycles through 3 on-board LEDs via external interrupt.

### Key concepts
- EXTI external interrupt
- 50ms debounce filter via HAL_GetTick()
- Volatile shared variables between main.c and stm32f4xx_it.c
- Extern variable declarations across multiple source files

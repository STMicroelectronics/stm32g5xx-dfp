

# Release Notes for
# <mark>STM32G5xx DFP Software Pack</mark>


# Purpose

STM32Cube enables developers to achieve design success. With a comprehensive suite of professional development tools and embedded software components, STM32Cube allows developers to differentiate products, streamline design cycles, and reduce costs. STM32Cube ecosystem supports all design steps, including selection, configuration, development, debugging, programming, and monitoring.

The STM32Cube embedded software offer provides ready-to-use software components that can be added to a project. It includes STM32 peripheral driver APIs with two levels of abstraction, middleware, board drivers, and examples. There are several distribution channels, including the STM32CubeMX2 tool, the ST website, and GitHub. All embedded software comes with enhanced online documentation, with flowcharts and user sequences.

More detailed documentation is available at [STM32G5xx DFP online documentation](https://dev.st.com/stm32cube-docs/stm32g5xx-dfp/latest/en/index.html).


![DFP Components](_htmresc/dfp-components.svg)



# **Update History**

<label for="collapse-v-2-0-0" aria-hidden="true">**2.0.0 /  25-September-2026**</label>
<div>

## First Official release of STM32G5xx DFP

### Supported Devices

- STM32G534xx, STM32G544xx devices
- STM32G553xx, STM32G554xx, STM32G563xx and STM32G564xx devices

## Contents

### CMSIS-Core Device Files

- Device C Startup files
- Device system configuration files
- Device header and System View Description (SVD) files, supporting
  - **System**: CRS, DBGMCU, DCACHE, DLYB, DMA, ICACHE, IWDG, PWR, RCC, RTC, SBS, WWDG
  - **Analog**: ADC, COMP, DAC, DTS, OPAMP, POSENC, VREFBUF
  - **Timers**: HRTIM, LPTIM, TIM
  - **Logic Array**: PLAY
  - **Connectivity**: FDCAN, I2C, I3C, SPI, UCPD, USART, USB
  - **Security**: AES, CCB, GTZC, HASH, OTFDEC, PKA, RNG, TAMP
  - **Computing**: CORDIC, CRC, FMAC
  - **I/O**: EXTI, GPIO
  - **Memory**: FLASH, RAMCFG, XSPI
- Device linker configuration template files

### Integrated Development Environment and Tools Support Files

- Flash Programming Algorithms for erasing and downloading code into on-chip Flash
- System View Description (SVD) files
- Device descriptor files for bus, clock, peripherals and pinout

## Supported Integrated Development Environment and Compilers

- IAR Embedded Workbench for ARM (EWARM) toolchain V9.60.3 + ST-LINK (Patch available in `IDEs_patches/EWARM`)
- MDK-ARM Keil uVision V5.42
- STM32CubeIDE for Visual Studio Code (GCC13 compiler)

## Known Limitations

- UCPD trim fields `TRIM_CC1_RP3A0` and `TRIM_CC2_RP3A0` correspond to the reference manual fields
  `TRIM_CC1_RP` and `TRIM_CC2_RP`, respectively.
- The following device variants (STM32G563xB, STM32G563xC, STM32G554xB, STM32G554xC) are not supported in this release.

## Dependencies

- CMSIS Core V6.3.0

</div>


For complete documentation on STM32 Microcontrollers </mark> ,
visit: http://www.st.com/stm32
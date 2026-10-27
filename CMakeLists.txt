# origin-pack: STMicroelectronics::stm32g5xx_dfp@2.0.0
# file-format: 1.0.0
project(STMicroelectronics_stm32g5xx_dfp_2_0_0)
cmake_minimum_required(VERSION 3.30)
add_library(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE)

# List of all CMSIS properties that influence conditions for this package
if(NOT DEFINED CMSIS_Dname)
  set(CMSIS_Dname "CMSIS_Dname not set")
  message(DEBUG "CMSIS_Dname is not set to any value")
endif()

if(NOT DEFINED CMSIS_Dsecure)
  set(CMSIS_Dsecure "CMSIS_Dsecure not set")
  message(DEBUG "CMSIS_Dsecure is not set to any value")
endif()

if(NOT DEFINED CMSIS_Dvendor)
  set(CMSIS_Dvendor "CMSIS_Dvendor not set")
  message(DEBUG "CMSIS_Dvendor is not set to any value")
endif()

if(NOT DEFINED CMSIS_Tcompiler)
  set(CMSIS_Tcompiler "CMSIS_Tcompiler not set")
  message(DEBUG "CMSIS_Tcompiler is not set to any value")
endif()


# Device specific defined symbols
if(CMSIS_Dname STREQUAL "STM32G553CBT3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553CBT6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553CBT7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553CBU3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553CBU6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553CBU7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553CBZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553CCT3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553CCT6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553CCT7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553CCU3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553CCU6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553CCU7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553CCZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553CET3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553CET6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553CET7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553CEU3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553CEU6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553CEU7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553CEZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553HBU3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553HBU6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553HBU7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553HCU3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553HCU6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553HCU7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553HEU3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553HEU6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553HEU7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553MBT3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553MBT6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553MBT7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553MBZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553MCT3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553MCT6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553MCT7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553MCZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553MET3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553MET6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553MET7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553MEZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553PBI3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553PBI6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553PBI7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553PCI3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553PCI6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553PCI7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553PEI3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553PEI6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553PEI7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553QBT3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553QBT6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553QBT7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553QBZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553QCT3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553QCT6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553QCT7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553QCZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553QET3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553QET3Q")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553QET6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553QET7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553QEZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553RBT3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553RBT6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553RBT7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553RBZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553RCT3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553RCT6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553RCT7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553RCZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553RET3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553RET6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553RET7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553REZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553VBT3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553VBT6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553VBT7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553VBZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553VCT3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553VCT6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553VCT7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553VCZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553VET3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553VET6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553VET7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G553VEZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G553xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G563CET3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G563xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G563CET6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G563xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G563CET7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G563xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G563CEU3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G563xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G563CEU6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G563xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G563CEU7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G563xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G563CEZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G563xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G563HEU3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G563xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G563HEU6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G563xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G563HEU7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G563xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G563MET3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G563xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G563MET6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G563xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G563MET7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G563xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G563MEZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G563xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G563PEI3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G563xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G563PEI6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G563xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G563PEI7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G563xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G563QET3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G563xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G563QET3Q")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G563xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G563QET6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G563xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G563QET7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G563xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G563QEZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G563xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G563RET3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G563xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G563RET6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G563xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G563RET7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G563xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G563REZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G563xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G563VET3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G563xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G563VET6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G563xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G563VET7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G563xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G563VEZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G563xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534C8T3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534C8T6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534C8U3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534C8U6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534CBT3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534CBT6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534CBU3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534CBU6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534CCT3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534CCT6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534CCU3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534CCU6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534CCZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534H8U3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534H8U6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534HBU3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534HBU6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534HCU3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534HCU6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534K8U3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534K8U6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534KBU3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534KBU6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534KCU3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534KCU6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534M8T3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534M8T6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534MBT3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534MBT6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534MCT3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534MCT6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534MCZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534R8T3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534R8T6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534RBT3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534RBT6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534RCT3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534RCT6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G534RCZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G534xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544C8T3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544C8T6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544C8U3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544C8U6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544C8Z3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544CBT3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544CBT3Z")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544CBT6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544CBU3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544CBU6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544CBZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544CCT3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544CCT3Z")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544CCT6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544CCU3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544CCU6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544CCZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544H8U3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544H8U6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544HBU3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544HBU6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544HCU3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544HCU6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544K8U3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544K8U6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544KBU3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544KBU6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544KCU3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544KCU6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544M8T3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544M8T6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544M8Z3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544MBT3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544MBT6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544MBZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544MCT3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544MCT6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544MCZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544R8T3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544R8T6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544R8Z3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544RBT3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544RBT3Z")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544RBT6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544RBZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544RCT3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544RCT3Z")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544RCT6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G544RCZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G544xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G554CET3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G554xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G554CET6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G554xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G554CET7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G554xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G554CEU3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G554xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G554CEU7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G554xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G554CEZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G554xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G554HEU3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G554xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G554HEU7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G554xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G554MET3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G554xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G554MET6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G554xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G554MET7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G554xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G554MEZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G554xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G554PEI3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G554xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G554PEI7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G554xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G554QET3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G554xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G554QET3Q")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G554xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G554QET6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G554xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G554QET7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G554xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G554QEZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G554xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G554RET3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G554xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G554RET6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G554xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G554RET7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G554xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G554REZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G554xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G554VET3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G554xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G554VET6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G554xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G554VET7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G554xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G554VEZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G554xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564CBT3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564CBT6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564CBT7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564CBU3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564CBU7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564CBZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564CCT3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564CCT6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564CCT7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564CCU3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564CCU7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564CCZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564CET3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564CET3Z")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564CET6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564CET7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564CEU3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564CEU7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564CEZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564HBU3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564HBU7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564HCU3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564HCU7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564HEU3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564HEU7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564MBT3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564MBT6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564MBT7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564MBZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564MCT3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564MCT6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564MCT7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564MCZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564MET3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564MET6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564MET7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564MEZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564PBI3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564PBI7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564PCI3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564PCI7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564PEI3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564PEI7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564QBT3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564QBT6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564QBT7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564QBZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564QCT3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564QCT6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564QCT7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564QCZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564QET3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564QET3Q")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564QET3Z")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564QET6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564QET7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564QEZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564RBT3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564RBT6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564RBT7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564RBZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564RCT3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564RCT6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564RCT7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564RCZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564RET3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564RET3Z")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564RET6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564RET7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564REZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564VBT3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564VBT6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564VBT7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564VBZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564VCT3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564VCT6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564VCT7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564VCZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564VET3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564VET6")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564VET7")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()
if(CMSIS_Dname STREQUAL "STM32G564VEZ3")
    target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE STM32G564xx)
endif()


# Include RTE_Components.h globally if needed
if(CMSIS_Tcompiler STREQUAL "IAR")
    target_compile_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "SHELL:--preinclude $<QUOTE>${CMAKE_CURRENT_LIST_DIR}/RTE_Components.h$<QUOTE>")
else()
    target_compile_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "SHELL:-include $<QUOTE>${CMAKE_CURRENT_LIST_DIR}/RTE_Components.h$<QUOTE>")
endif()





# Enable all components in this package
if(CMSIS_ENTIRE_STMicroelectronics_stm32g5xx_dfp_2_0_0)
  list(APPEND CMSIS_COMPONENTS_LIST "Cvendor:STMicroelectronics#Cclass:Device#Cgroup:Startup#Cversion:2.0.0")
  list(APPEND CMSIS_COMPONENTS_LIST "Cvendor:STMicroelectronics#Cclass:Device#Cgroup:Startup#Cvariant:SRAM#Cversion:2.0.0")
endif()

# All conditions used by this package

# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G534
# description: 
if((CMSIS_Dname MATCHES "STM32G534.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534 "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534 enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G534x8 ARMCC Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G534.8.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534x8_ARMCC_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534x8_ARMCC_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534x8_ARMCC_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G534x8 ARMCC Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G534.8.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534x8_ARMCC_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534x8_ARMCC_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534x8_ARMCC_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G534x8 ARMCC TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G534.8.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534x8_ARMCC_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534x8_ARMCC_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534x8_ARMCC_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G534x8 GCC Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G534.8.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534x8_GCC_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534x8_GCC_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534x8_GCC_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G534x8 GCC Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G534.8.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534x8_GCC_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534x8_GCC_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534x8_GCC_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G534x8 GCC TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G534.8.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534x8_GCC_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534x8_GCC_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534x8_GCC_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G534x8 IAR Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G534.8.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534x8_IAR_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534x8_IAR_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534x8_IAR_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G534x8 IAR Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G534.8.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534x8_IAR_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534x8_IAR_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534x8_IAR_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G534x8 IAR TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G534.8.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534x8_IAR_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534x8_IAR_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534x8_IAR_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G534xB ARMCC Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G534.B.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xB_ARMCC_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xB_ARMCC_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xB_ARMCC_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G534xB ARMCC Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G534.B.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xB_ARMCC_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xB_ARMCC_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xB_ARMCC_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G534xB ARMCC TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G534.B.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xB_ARMCC_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xB_ARMCC_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xB_ARMCC_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G534xB GCC Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G534.B.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xB_GCC_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xB_GCC_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xB_GCC_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G534xB GCC Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G534.B.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xB_GCC_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xB_GCC_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xB_GCC_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G534xB GCC TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G534.B.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xB_GCC_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xB_GCC_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xB_GCC_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G534xB IAR Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G534.B.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xB_IAR_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xB_IAR_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xB_IAR_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G534xB IAR Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G534.B.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xB_IAR_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xB_IAR_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xB_IAR_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G534xB IAR TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G534.B.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xB_IAR_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xB_IAR_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xB_IAR_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G534xC ARMCC Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G534.C.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xC_ARMCC_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xC_ARMCC_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xC_ARMCC_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G534xC ARMCC Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G534.C.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xC_ARMCC_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xC_ARMCC_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xC_ARMCC_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G534xC ARMCC TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G534.C.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xC_ARMCC_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xC_ARMCC_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xC_ARMCC_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G534xC GCC Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G534.C.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xC_GCC_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xC_GCC_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xC_GCC_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G534xC GCC Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G534.C.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xC_GCC_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xC_GCC_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xC_GCC_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G534xC GCC TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G534.C.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xC_GCC_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xC_GCC_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xC_GCC_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G534xC IAR Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G534.C.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xC_IAR_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xC_IAR_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xC_IAR_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G534xC IAR Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G534.C.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xC_IAR_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xC_IAR_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xC_IAR_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G534xC IAR TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G534.C.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xC_IAR_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xC_IAR_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xC_IAR_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G534xx ARMCC Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G534...*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xx_ARMCC_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xx_ARMCC_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xx_ARMCC_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G534xx ARMCC Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G534...*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xx_ARMCC_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xx_ARMCC_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xx_ARMCC_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G534xx ARMCC TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G534...*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xx_ARMCC_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xx_ARMCC_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xx_ARMCC_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G534xx GCC Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G534...*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xx_GCC_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xx_GCC_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xx_GCC_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G534xx GCC Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G534...*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xx_GCC_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xx_GCC_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xx_GCC_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G534xx GCC TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G534...*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xx_GCC_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xx_GCC_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xx_GCC_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G534xx IAR Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G534...*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xx_IAR_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xx_IAR_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xx_IAR_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G534xx IAR Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G534...*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xx_IAR_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xx_IAR_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xx_IAR_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G534xx IAR TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G534...*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xx_IAR_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xx_IAR_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xx_IAR_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G544
# description: 
if((CMSIS_Dname MATCHES "STM32G544.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544 "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544 enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G544x8 ARMCC Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G544.8.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544x8_ARMCC_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544x8_ARMCC_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544x8_ARMCC_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G544x8 ARMCC Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G544.8.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544x8_ARMCC_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544x8_ARMCC_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544x8_ARMCC_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G544x8 ARMCC TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G544.8.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544x8_ARMCC_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544x8_ARMCC_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544x8_ARMCC_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G544x8 GCC Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G544.8.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544x8_GCC_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544x8_GCC_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544x8_GCC_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G544x8 GCC Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G544.8.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544x8_GCC_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544x8_GCC_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544x8_GCC_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G544x8 GCC TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G544.8.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544x8_GCC_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544x8_GCC_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544x8_GCC_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G544x8 IAR Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G544.8.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544x8_IAR_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544x8_IAR_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544x8_IAR_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G544x8 IAR Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G544.8.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544x8_IAR_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544x8_IAR_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544x8_IAR_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G544x8 IAR TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G544.8.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544x8_IAR_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544x8_IAR_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544x8_IAR_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G544xB ARMCC Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G544.B.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xB_ARMCC_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xB_ARMCC_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xB_ARMCC_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G544xB ARMCC Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G544.B.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xB_ARMCC_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xB_ARMCC_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xB_ARMCC_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G544xB ARMCC TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G544.B.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xB_ARMCC_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xB_ARMCC_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xB_ARMCC_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G544xB GCC Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G544.B.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xB_GCC_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xB_GCC_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xB_GCC_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G544xB GCC Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G544.B.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xB_GCC_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xB_GCC_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xB_GCC_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G544xB GCC TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G544.B.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xB_GCC_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xB_GCC_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xB_GCC_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G544xB IAR Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G544.B.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xB_IAR_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xB_IAR_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xB_IAR_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G544xB IAR Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G544.B.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xB_IAR_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xB_IAR_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xB_IAR_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G544xB IAR TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G544.B.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xB_IAR_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xB_IAR_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xB_IAR_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G544xC ARMCC Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G544.C.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xC_ARMCC_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xC_ARMCC_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xC_ARMCC_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G544xC ARMCC Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G544.C.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xC_ARMCC_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xC_ARMCC_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xC_ARMCC_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G544xC ARMCC TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G544.C.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xC_ARMCC_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xC_ARMCC_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xC_ARMCC_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G544xC GCC Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G544.C.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xC_GCC_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xC_GCC_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xC_GCC_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G544xC GCC Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G544.C.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xC_GCC_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xC_GCC_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xC_GCC_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G544xC GCC TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G544.C.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xC_GCC_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xC_GCC_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xC_GCC_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G544xC IAR Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G544.C.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xC_IAR_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xC_IAR_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xC_IAR_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G544xC IAR Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G544.C.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xC_IAR_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xC_IAR_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xC_IAR_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G544xC IAR TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G544.C.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xC_IAR_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xC_IAR_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xC_IAR_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G544xx ARMCC Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G544...*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xx_ARMCC_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xx_ARMCC_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xx_ARMCC_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G544xx ARMCC Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G544...*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xx_ARMCC_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xx_ARMCC_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xx_ARMCC_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G544xx ARMCC TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G544...*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xx_ARMCC_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xx_ARMCC_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xx_ARMCC_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G544xx GCC Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G544...*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xx_GCC_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xx_GCC_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xx_GCC_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G544xx GCC Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G544...*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xx_GCC_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xx_GCC_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xx_GCC_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G544xx GCC TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G544...*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xx_GCC_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xx_GCC_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xx_GCC_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G544xx IAR Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G544...*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xx_IAR_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xx_IAR_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xx_IAR_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G544xx IAR Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G544...*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xx_IAR_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xx_IAR_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xx_IAR_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G544xx IAR TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G544...*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xx_IAR_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xx_IAR_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xx_IAR_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G553
# description: 
if((CMSIS_Dname MATCHES "STM32G553.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553 "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553 enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G553xB ARMCC Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G553.B.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xB_ARMCC_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xB_ARMCC_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xB_ARMCC_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G553xB ARMCC Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G553.B.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xB_ARMCC_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xB_ARMCC_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xB_ARMCC_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G553xB ARMCC TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G553.B.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xB_ARMCC_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xB_ARMCC_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xB_ARMCC_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G553xB GCC Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G553.B.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xB_GCC_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xB_GCC_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xB_GCC_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G553xB GCC Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G553.B.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xB_GCC_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xB_GCC_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xB_GCC_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G553xB GCC TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G553.B.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xB_GCC_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xB_GCC_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xB_GCC_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G553xB IAR Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G553.B.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xB_IAR_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xB_IAR_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xB_IAR_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G553xB IAR Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G553.B.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xB_IAR_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xB_IAR_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xB_IAR_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G553xB IAR TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G553.B.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xB_IAR_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xB_IAR_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xB_IAR_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G553xC ARMCC Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G553.C.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xC_ARMCC_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xC_ARMCC_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xC_ARMCC_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G553xC ARMCC Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G553.C.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xC_ARMCC_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xC_ARMCC_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xC_ARMCC_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G553xC ARMCC TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G553.C.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xC_ARMCC_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xC_ARMCC_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xC_ARMCC_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G553xC GCC Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G553.C.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xC_GCC_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xC_GCC_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xC_GCC_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G553xC GCC Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G553.C.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xC_GCC_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xC_GCC_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xC_GCC_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G553xC GCC TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G553.C.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xC_GCC_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xC_GCC_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xC_GCC_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G553xC IAR Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G553.C.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xC_IAR_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xC_IAR_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xC_IAR_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G553xC IAR Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G553.C.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xC_IAR_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xC_IAR_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xC_IAR_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G553xC IAR TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G553.C.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xC_IAR_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xC_IAR_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xC_IAR_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G553xE ARMCC Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G553.E.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xE_ARMCC_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xE_ARMCC_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xE_ARMCC_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G553xE ARMCC Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G553.E.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xE_ARMCC_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xE_ARMCC_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xE_ARMCC_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G553xE ARMCC TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G553.E.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xE_ARMCC_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xE_ARMCC_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xE_ARMCC_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G553xE GCC Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G553.E.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xE_GCC_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xE_GCC_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xE_GCC_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G553xE GCC Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G553.E.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xE_GCC_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xE_GCC_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xE_GCC_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G553xE GCC TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G553.E.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xE_GCC_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xE_GCC_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xE_GCC_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G553xE IAR Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G553.E.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xE_IAR_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xE_IAR_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xE_IAR_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G553xE IAR Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G553.E.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xE_IAR_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xE_IAR_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xE_IAR_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G553xE IAR TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G553.E.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xE_IAR_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xE_IAR_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xE_IAR_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G553xx ARMCC Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G553...*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xx_ARMCC_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xx_ARMCC_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xx_ARMCC_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G553xx ARMCC Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G553...*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xx_ARMCC_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xx_ARMCC_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xx_ARMCC_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G553xx ARMCC TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G553...*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xx_ARMCC_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xx_ARMCC_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xx_ARMCC_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G553xx GCC Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G553...*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xx_GCC_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xx_GCC_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xx_GCC_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G553xx GCC Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G553...*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xx_GCC_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xx_GCC_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xx_GCC_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G553xx GCC TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G553...*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xx_GCC_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xx_GCC_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xx_GCC_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G553xx IAR Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G553...*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xx_IAR_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xx_IAR_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xx_IAR_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G553xx IAR Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G553...*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xx_IAR_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xx_IAR_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xx_IAR_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G553xx IAR TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G553...*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xx_IAR_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xx_IAR_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xx_IAR_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G554
# description: 
if((CMSIS_Dname MATCHES "STM32G554.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554 "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554 enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G554xE ARMCC Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G554.E.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_ARMCC_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_ARMCC_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_ARMCC_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G554xE ARMCC Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G554.E.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_ARMCC_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_ARMCC_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_ARMCC_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G554xE ARMCC TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G554.E.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_ARMCC_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_ARMCC_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_ARMCC_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G554xE GCC Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G554.E.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_GCC_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_GCC_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_GCC_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G554xE GCC Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G554.E.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_GCC_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_GCC_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_GCC_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G554xE GCC TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G554.E.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_GCC_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_GCC_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_GCC_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G554xE IAR Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G554.E.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_IAR_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_IAR_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_IAR_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G554xE IAR Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G554.E.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_IAR_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_IAR_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_IAR_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G554xE IAR TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G554.E.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_IAR_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_IAR_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_IAR_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G563
# description: 
if((CMSIS_Dname MATCHES "STM32G563.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563 "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563 enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G563xE ARMCC Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G563.E.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_ARMCC_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_ARMCC_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_ARMCC_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G563xE ARMCC Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G563.E.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_ARMCC_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_ARMCC_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_ARMCC_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G563xE ARMCC TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G563.E.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_ARMCC_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_ARMCC_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_ARMCC_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G563xE GCC Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G563.E.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_GCC_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_GCC_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_GCC_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G563xE GCC Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G563.E.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_GCC_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_GCC_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_GCC_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G563xE GCC TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G563.E.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_GCC_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_GCC_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_GCC_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G563xE IAR Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G563.E.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_IAR_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_IAR_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_IAR_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G563xE IAR Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G563.E.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_IAR_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_IAR_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_IAR_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G563xE IAR TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G563.E.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_IAR_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_IAR_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_IAR_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G564
# description: 
if((CMSIS_Dname MATCHES "STM32G564.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564 "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564 enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G564xB ARMCC Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G564.B.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xB_ARMCC_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xB_ARMCC_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xB_ARMCC_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G564xB ARMCC Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G564.B.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xB_ARMCC_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xB_ARMCC_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xB_ARMCC_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G564xB ARMCC TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G564.B.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xB_ARMCC_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xB_ARMCC_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xB_ARMCC_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G564xB GCC Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G564.B.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xB_GCC_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xB_GCC_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xB_GCC_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G564xB GCC Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G564.B.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xB_GCC_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xB_GCC_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xB_GCC_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G564xB GCC TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G564.B.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xB_GCC_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xB_GCC_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xB_GCC_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G564xB IAR Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G564.B.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xB_IAR_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xB_IAR_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xB_IAR_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G564xB IAR Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G564.B.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xB_IAR_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xB_IAR_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xB_IAR_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G564xB IAR TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G564.B.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xB_IAR_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xB_IAR_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xB_IAR_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G564xC ARMCC Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G564.C.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xC_ARMCC_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xC_ARMCC_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xC_ARMCC_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G564xC ARMCC Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G564.C.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xC_ARMCC_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xC_ARMCC_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xC_ARMCC_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G564xC ARMCC TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G564.C.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xC_ARMCC_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xC_ARMCC_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xC_ARMCC_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G564xC GCC Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G564.C.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xC_GCC_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xC_GCC_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xC_GCC_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G564xC GCC Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G564.C.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xC_GCC_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xC_GCC_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xC_GCC_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G564xC GCC TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G564.C.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xC_GCC_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xC_GCC_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xC_GCC_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G564xC IAR Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G564.C.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xC_IAR_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xC_IAR_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xC_IAR_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G564xC IAR Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G564.C.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xC_IAR_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xC_IAR_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xC_IAR_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G564xC IAR TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G564.C.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xC_IAR_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xC_IAR_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xC_IAR_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G564xE ARMCC Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G564.E.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xE_ARMCC_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xE_ARMCC_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xE_ARMCC_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G564xE ARMCC Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G564.E.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xE_ARMCC_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xE_ARMCC_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xE_ARMCC_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G564xE ARMCC TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G564.E.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xE_ARMCC_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xE_ARMCC_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xE_ARMCC_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G564xE GCC Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G564.E.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xE_GCC_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xE_GCC_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xE_GCC_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G564xE GCC Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G564.E.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xE_GCC_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xE_GCC_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xE_GCC_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G564xE GCC TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G564.E.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xE_GCC_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xE_GCC_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xE_GCC_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G564xE IAR Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G564.E.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xE_IAR_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xE_IAR_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xE_IAR_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G564xE IAR Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G564.E.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xE_IAR_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xE_IAR_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xE_IAR_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G564xE IAR TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G564.E.*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xE_IAR_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xE_IAR_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xE_IAR_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G564xx ARMCC Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G564...*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xx_ARMCC_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xx_ARMCC_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xx_ARMCC_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G564xx ARMCC Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G564...*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xx_ARMCC_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xx_ARMCC_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xx_ARMCC_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G564xx ARMCC TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G564...*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "ARMCC" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xx_ARMCC_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xx_ARMCC_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xx_ARMCC_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G564xx GCC Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G564...*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xx_GCC_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xx_GCC_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xx_GCC_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G564xx GCC Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G564...*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xx_GCC_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xx_GCC_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xx_GCC_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G564xx GCC TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G564...*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "GCC" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xx_GCC_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xx_GCC_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xx_GCC_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G564xx IAR Non-secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G564...*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "Non-secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xx_IAR_Non-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xx_IAR_Non-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xx_IAR_Non-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G564xx IAR Secure
# description: 
if(((CMSIS_Dname MATCHES "STM32G564...*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "Secure"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xx_IAR_Secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xx_IAR_Secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xx_IAR_Secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G564xx IAR TZ-disabled
# description: 
if(((CMSIS_Dname MATCHES "STM32G564...*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13") AND CMSIS_Tcompiler STREQUAL "IAR" AND CMSIS_Dsecure STREQUAL "TZ-disabled"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xx_IAR_TZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xx_IAR_TZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xx_IAR_TZ-disabled 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:STM32G5[3456]
# description: 
if((CMSIS_Dname MATCHES "STM32G5[3456].*" AND CMSIS_Dvendor STREQUAL "STMicroelectronics:13"))
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_ "$<NOT:$<STREQUAL:$<FILTER:${CMSIS_COMPONENTS_LIST},INCLUDE,.*Cclass:CMSIS#.*Cgroup:CORE(#.*|$)>,>>")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_ enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_ 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:isNon-secure
# description: 
if(CMSIS_Dsecure STREQUAL "Non-secure")
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_isNon-secure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_isNon-secure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_isNon-secure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:isSecure
# description: 
if(CMSIS_Dsecure STREQUAL "Secure")
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_isSecure "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_isSecure enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_isSecure 0)
endif()


# condition: STMicroelectronics.stm32g5xx_dfp.2.0.0:isTZ-disabled
# description: 
if(CMSIS_Dsecure STREQUAL "TZ-disabled")
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_isTZ-disabled "1")
  message(DEBUG "CMSIS condition STMicroelectronics.stm32g5xx_dfp.2.0.0_isTZ-disabled enabled")
else()
  set(STMicroelectronics.stm32g5xx_dfp.2.0.0_isTZ-disabled 0)
endif()

# Files and components in this package
if("Cvendor:STMicroelectronics#Cclass:Device#Cgroup:Startup#Cversion:2.0.0" IN_LIST CMSIS_COMPONENTS_LIST)  # System Startup for STMicroelectronics STM32G5 Series
  message(DEBUG "Using component Device_Startup_2_0_0")
  target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_}:-DCMSIS_USE_Device_Startup_2_0_0=1>")
  target_include_directories(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_}:${CMAKE_CURRENT_LIST_DIR}/Include>")
  target_include_directories(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_}:${CMAKE_CURRENT_LIST_DIR}/Include/>")
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/startup_stm32g534xx.c)
    target_sources(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534}>:${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/startup_stm32g534xx.c>")
  else()
    target_sources(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534}>:${CMAKE_CURRENT_LIST_DIR}/Source/startup_stm32g534xx.c>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g534x8_flash_ns.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534x8_GCC_Non-secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g534x8_flash_ns.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534x8_GCC_Non-secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g534x8_flash_ns.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g534x8_flash_s.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534x8_GCC_Secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g534x8_flash_s.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534x8_GCC_Secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g534x8_flash_s.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g534x8_flash.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534x8_GCC_TZ-disabled}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g534x8_flash.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534x8_GCC_TZ-disabled}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g534x8_flash.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g534xb_flash_ns.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xB_GCC_Non-secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g534xb_flash_ns.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xB_GCC_Non-secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g534xb_flash_ns.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g534xb_flash_s.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xB_GCC_Secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g534xb_flash_s.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xB_GCC_Secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g534xb_flash_s.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g534xb_flash.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xB_GCC_TZ-disabled}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g534xb_flash.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xB_GCC_TZ-disabled}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g534xb_flash.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g534xc_flash_ns.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xC_GCC_Non-secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g534xc_flash_ns.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xC_GCC_Non-secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g534xc_flash_ns.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g534xc_flash_s.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xC_GCC_Secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g534xc_flash_s.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xC_GCC_Secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g534xc_flash_s.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g534xc_flash.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xC_GCC_TZ-disabled}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g534xc_flash.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xC_GCC_TZ-disabled}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g534xc_flash.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/startup_stm32g544xx.c)
    target_sources(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544}>:${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/startup_stm32g544xx.c>")
  else()
    target_sources(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544}>:${CMAKE_CURRENT_LIST_DIR}/Source/startup_stm32g544xx.c>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g544x8_flash_ns.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544x8_GCC_Non-secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g544x8_flash_ns.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544x8_GCC_Non-secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g544x8_flash_ns.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g544x8_flash_s.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544x8_GCC_Secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g544x8_flash_s.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544x8_GCC_Secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g544x8_flash_s.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g544x8_flash.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544x8_GCC_TZ-disabled}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g544x8_flash.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544x8_GCC_TZ-disabled}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g544x8_flash.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g544xb_flash_ns.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xB_GCC_Non-secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g544xb_flash_ns.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xB_GCC_Non-secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g544xb_flash_ns.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g544xb_flash_s.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xB_GCC_Secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g544xb_flash_s.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xB_GCC_Secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g544xb_flash_s.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g544xb_flash.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xB_GCC_TZ-disabled}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g544xb_flash.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xB_GCC_TZ-disabled}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g544xb_flash.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g544xc_flash_ns.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xC_GCC_Non-secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g544xc_flash_ns.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xC_GCC_Non-secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g544xc_flash_ns.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g544xc_flash_s.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xC_GCC_Secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g544xc_flash_s.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xC_GCC_Secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g544xc_flash_s.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g544xc_flash.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xC_GCC_TZ-disabled}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g544xc_flash.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xC_GCC_TZ-disabled}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g544xc_flash.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/startup_stm32g553xx.c)
    target_sources(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553}>:${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/startup_stm32g553xx.c>")
  else()
    target_sources(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553}>:${CMAKE_CURRENT_LIST_DIR}/Source/startup_stm32g553xx.c>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g553xb_flash_ns.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xB_GCC_Non-secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g553xb_flash_ns.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xB_GCC_Non-secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g553xb_flash_ns.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g553xb_flash_s.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xB_GCC_Secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g553xb_flash_s.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xB_GCC_Secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g553xb_flash_s.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g553xb_flash.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xB_GCC_TZ-disabled}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g553xb_flash.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xB_GCC_TZ-disabled}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g553xb_flash.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g553xc_flash_ns.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xC_GCC_Non-secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g553xc_flash_ns.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xC_GCC_Non-secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g553xc_flash_ns.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g553xc_flash_s.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xC_GCC_Secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g553xc_flash_s.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xC_GCC_Secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g553xc_flash_s.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g553xc_flash.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xC_GCC_TZ-disabled}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g553xc_flash.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xC_GCC_TZ-disabled}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g553xc_flash.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g553xe_flash_ns.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xE_GCC_Non-secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g553xe_flash_ns.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xE_GCC_Non-secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g553xe_flash_ns.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g553xe_flash_s.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xE_GCC_Secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g553xe_flash_s.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xE_GCC_Secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g553xe_flash_s.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g553xe_flash.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xE_GCC_TZ-disabled}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g553xe_flash.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xE_GCC_TZ-disabled}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g553xe_flash.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/startup_stm32g554xx.c)
    target_sources(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554}>:${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/startup_stm32g554xx.c>")
  else()
    target_sources(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554}>:${CMAKE_CURRENT_LIST_DIR}/Source/startup_stm32g554xx.c>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g554xe_flash_ns.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_GCC_Non-secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g554xe_flash_ns.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_GCC_Non-secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g554xe_flash_ns.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g554xe_flash_s.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_GCC_Secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g554xe_flash_s.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_GCC_Secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g554xe_flash_s.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g554xe_flash.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_GCC_TZ-disabled}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g554xe_flash.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_GCC_TZ-disabled}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g554xe_flash.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/startup_stm32g563xx.c)
    target_sources(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563}>:${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/startup_stm32g563xx.c>")
  else()
    target_sources(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563}>:${CMAKE_CURRENT_LIST_DIR}/Source/startup_stm32g563xx.c>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g563xe_flash_ns.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_GCC_Non-secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g563xe_flash_ns.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_GCC_Non-secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g563xe_flash_ns.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g563xe_flash_s.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_GCC_Secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g563xe_flash_s.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_GCC_Secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g563xe_flash_s.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g563xe_flash.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_GCC_TZ-disabled}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g563xe_flash.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_GCC_TZ-disabled}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g563xe_flash.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/startup_stm32g564xx.c)
    target_sources(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564}>:${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/startup_stm32g564xx.c>")
  else()
    target_sources(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564}>:${CMAKE_CURRENT_LIST_DIR}/Source/startup_stm32g564xx.c>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g564xb_flash_ns.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xB_GCC_Non-secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g564xb_flash_ns.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xB_GCC_Non-secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g564xb_flash_ns.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g564xb_flash_s.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xB_GCC_Secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g564xb_flash_s.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xB_GCC_Secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g564xb_flash_s.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g564xb_flash.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xB_GCC_TZ-disabled}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g564xb_flash.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xB_GCC_TZ-disabled}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g564xb_flash.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g564xc_flash_ns.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xC_GCC_Non-secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g564xc_flash_ns.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xC_GCC_Non-secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g564xc_flash_ns.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g564xc_flash_s.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xC_GCC_Secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g564xc_flash_s.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xC_GCC_Secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g564xc_flash_s.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g564xc_flash.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xC_GCC_TZ-disabled}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g564xc_flash.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xC_GCC_TZ-disabled}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g564xc_flash.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g564xe_flash_ns.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xE_GCC_Non-secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g564xe_flash_ns.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xE_GCC_Non-secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g564xe_flash_ns.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g564xe_flash_s.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xE_GCC_Secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g564xe_flash_s.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xE_GCC_Secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g564xe_flash_s.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g564xe_flash.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xE_GCC_TZ-disabled}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g564xe_flash.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xE_GCC_TZ-disabled}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g564xe_flash.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/system_stm32g5xx_ns.c)
    target_sources(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_isNon-secure}>:${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/system_stm32g5xx_ns.c>")
  else()
    target_sources(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_isNon-secure}>:${CMAKE_CURRENT_LIST_DIR}/Source/Templates/system_stm32g5xx_ns.c>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/system_stm32g5xx_s.c)
    target_sources(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_isSecure}>:${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/system_stm32g5xx_s.c>")
  else()
    target_sources(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_isSecure}>:${CMAKE_CURRENT_LIST_DIR}/Source/Templates/system_stm32g5xx_s.c>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/system_stm32g5xx.c)
    target_sources(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_isTZ-disabled}>:${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/system_stm32g5xx.c>")
  else()
    target_sources(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_isTZ-disabled}>:${CMAKE_CURRENT_LIST_DIR}/Source/Templates/system_stm32g5xx.c>")
  endif()
endif()

if("Cvendor:STMicroelectronics#Cclass:Device#Cgroup:Startup#Cvariant:SRAM#Cversion:2.0.0" IN_LIST CMSIS_COMPONENTS_LIST)  # System Startup for STMicroelectronics STM32G5 Series
  message(DEBUG "Using component Device_Startup_SRAM_2_0_0")
  target_compile_definitions(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_}:-DCMSIS_USE_Device_Startup_SRAM_2_0_0=1>")
  target_include_directories(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_}:${CMAKE_CURRENT_LIST_DIR}/Include>")
  target_include_directories(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_}:${CMAKE_CURRENT_LIST_DIR}/Include/>")
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/startup_stm32g534xx.c)
    target_sources(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534}>:${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/startup_stm32g534xx.c>")
  else()
    target_sources(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534}>:${CMAKE_CURRENT_LIST_DIR}/Source/startup_stm32g534xx.c>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g534xx_sram_ns.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xx_GCC_Non-secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g534xx_sram_ns.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xx_GCC_Non-secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g534xx_sram_ns.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g534xx_sram_s.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xx_GCC_Secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g534xx_sram_s.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xx_GCC_Secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g534xx_sram_s.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g534xx_sram.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xx_GCC_TZ-disabled}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g534xx_sram.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G534xx_GCC_TZ-disabled}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g534xx_sram.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/startup_stm32g544xx.c)
    target_sources(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544}>:${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/startup_stm32g544xx.c>")
  else()
    target_sources(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544}>:${CMAKE_CURRENT_LIST_DIR}/Source/startup_stm32g544xx.c>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g544xx_sram_ns.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xx_GCC_Non-secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g544xx_sram_ns.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xx_GCC_Non-secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g544xx_sram_ns.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g544xx_sram_s.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xx_GCC_Secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g544xx_sram_s.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xx_GCC_Secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g544xx_sram_s.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g544xx_sram.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xx_GCC_TZ-disabled}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g544xx_sram.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G544xx_GCC_TZ-disabled}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g544xx_sram.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/startup_stm32g553xx.c)
    target_sources(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553}>:${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/startup_stm32g553xx.c>")
  else()
    target_sources(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553}>:${CMAKE_CURRENT_LIST_DIR}/Source/startup_stm32g553xx.c>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g553xx_sram_ns.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xx_GCC_Non-secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g553xx_sram_ns.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xx_GCC_Non-secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g553xx_sram_ns.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g553xx_sram_s.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xx_GCC_Secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g553xx_sram_s.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xx_GCC_Secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g553xx_sram_s.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g553xx_sram.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xx_GCC_TZ-disabled}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g553xx_sram.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G553xx_GCC_TZ-disabled}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g553xx_sram.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/startup_stm32g554xx.c)
    target_sources(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554}>:${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/startup_stm32g554xx.c>")
  else()
    target_sources(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554}>:${CMAKE_CURRENT_LIST_DIR}/Source/startup_stm32g554xx.c>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g554xe_sram_ns.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_GCC_Non-secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g554xe_sram_ns.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_GCC_Non-secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g554xe_sram_ns.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g554xe_sram_s.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_GCC_Secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g554xe_sram_s.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_GCC_Secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g554xe_sram_s.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g554xe_sram.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_GCC_TZ-disabled}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g554xe_sram.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G554xE_GCC_TZ-disabled}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g554xe_sram.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/startup_stm32g563xx.c)
    target_sources(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563}>:${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/startup_stm32g563xx.c>")
  else()
    target_sources(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563}>:${CMAKE_CURRENT_LIST_DIR}/Source/startup_stm32g563xx.c>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g563xe_sram_ns.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_GCC_Non-secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g563xe_sram_ns.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_GCC_Non-secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g563xe_sram_ns.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g563xe_sram_s.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_GCC_Secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g563xe_sram_s.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_GCC_Secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g563xe_sram_s.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g563xe_sram.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_GCC_TZ-disabled}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g563xe_sram.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G563xE_GCC_TZ-disabled}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g563xe_sram.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/startup_stm32g564xx.c)
    target_sources(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564}>:${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/startup_stm32g564xx.c>")
  else()
    target_sources(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564}>:${CMAKE_CURRENT_LIST_DIR}/Source/startup_stm32g564xx.c>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g564xx_sram_ns.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xx_GCC_Non-secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g564xx_sram_ns.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xx_GCC_Non-secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g564xx_sram_ns.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g564xx_sram_s.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xx_GCC_Secure}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g564xx_sram_s.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xx_GCC_Secure}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g564xx_sram_s.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g564xx_sram.ld)
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xx_GCC_TZ-disabled}>:-T${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/stm32g564xx_sram.ld>")
  else()
    target_link_options(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G564xx_GCC_TZ-disabled}>:-T${CMAKE_CURRENT_LIST_DIR}/Source/Templates/gcc/linker/stm32g564xx_sram.ld>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/system_stm32g5xx_ns.c)
    target_sources(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_isNon-secure}>:${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/system_stm32g5xx_ns.c>")
  else()
    target_sources(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_isNon-secure}>:${CMAKE_CURRENT_LIST_DIR}/Source/Templates/system_stm32g5xx_ns.c>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/system_stm32g5xx_s.c)
    target_sources(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_isSecure}>:${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/system_stm32g5xx_s.c>")
  else()
    target_sources(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_isSecure}>:${CMAKE_CURRENT_LIST_DIR}/Source/Templates/system_stm32g5xx_s.c>")
  endif()
  if(EXISTS ${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/system_stm32g5xx.c)
    target_sources(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_isTZ-disabled}>:${CMSIS_RTE_FOLDER}/Device/${CMSIS_Dname}/system_stm32g5xx.c>")
  else()
    target_sources(STMicroelectronics_stm32g5xx_dfp_2_0_0 INTERFACE "$<$<AND:${STMicroelectronics.stm32g5xx_dfp.2.0.0_STM32G5_3456_},${STMicroelectronics.stm32g5xx_dfp.2.0.0_isTZ-disabled}>:${CMAKE_CURRENT_LIST_DIR}/Source/Templates/system_stm32g5xx.c>")
  endif()
endif()



#INCLUDE DIR FOR "stm32f103vet6_fire"
CINCLUDE_FILE += catOS/bsp/stm32f103vet6_fire/Libraries/CMSIS/Include
CINCLUDE_FILE += catOS/bsp/stm32f103vet6_fire/Libraries/CMSIS/Device/ST/STM32F1xx/Include
CINCLUDE_FILE += catOS/bsp/stm32f103vet6_fire/Libraries/STM32F1xx_HAL_Driver/Inc

CINCLUDE_FILE += catOS/bsp/stm32f103vet6_fire/drivers/uart
CINCLUDE_FILE += catOS/bsp/interface
CINCLUDE_FILE += catOS/include
CINCLUDE_FILE += catOS/src/core/interrupt
CINCLUDE_FILE += catOS/src/core/schedule

CINCLUDE_FILE += user

#subdir
subdir-y += drivers
subdir-y += Libraries
subdir-y += port

include $(RULE_DIR)/rules.mk

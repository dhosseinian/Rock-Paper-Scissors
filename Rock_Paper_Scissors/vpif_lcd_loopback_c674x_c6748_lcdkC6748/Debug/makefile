################################################################################
# Automatically-generated file. Do not edit!
################################################################################

SHELL = cmd.exe

CG_TOOL_ROOT := C:/ti/ccsv5/tools/compiler/c6000_7.4.4

ORDERED_OBJS += \
$(GEN_CMDS__FLAG) \
"./vpif_lcd_loopback.obj" \
"./tvp5147.obj" \
"./i2cgpio.obj" \
"./codecif.obj" \
"./cdce913.obj" \
"./cbcr422sp_to_rgb565_dsp.obj" \
"./adv7343.obj" \
"../vpif_lcd_loopback.cmd" \
-l"libc.a" \
-ldrivers.lib \
-lutils.lib \
-lplatform.lib \
-lsystem_config.lib \

-include ../makefile.init

RM := DEL /F
RMDIR := RMDIR /S/Q

# All of the sources participating in the build are defined here
-include sources.mk
-include subdir_vars.mk
-include subdir_rules.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(S_DEPS)),)
-include $(S_DEPS)
endif
ifneq ($(strip $(S_UPPER_DEPS)),)
-include $(S_UPPER_DEPS)
endif
ifneq ($(strip $(S62_DEPS)),)
-include $(S62_DEPS)
endif
ifneq ($(strip $(C64_DEPS)),)
-include $(C64_DEPS)
endif
ifneq ($(strip $(ASM_DEPS)),)
-include $(ASM_DEPS)
endif
ifneq ($(strip $(CC_DEPS)),)
-include $(CC_DEPS)
endif
ifneq ($(strip $(S55_DEPS)),)
-include $(S55_DEPS)
endif
ifneq ($(strip $(C67_DEPS)),)
-include $(C67_DEPS)
endif
ifneq ($(strip $(C??_DEPS)),)
-include $(C??_DEPS)
endif
ifneq ($(strip $(CLA_DEPS)),)
-include $(CLA_DEPS)
endif
ifneq ($(strip $(CPP_DEPS)),)
-include $(CPP_DEPS)
endif
ifneq ($(strip $(S??_DEPS)),)
-include $(S??_DEPS)
endif
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
ifneq ($(strip $(C62_DEPS)),)
-include $(C62_DEPS)
endif
ifneq ($(strip $(CXX_DEPS)),)
-include $(CXX_DEPS)
endif
ifneq ($(strip $(C++_DEPS)),)
-include $(C++_DEPS)
endif
ifneq ($(strip $(ASM_UPPER_DEPS)),)
-include $(ASM_UPPER_DEPS)
endif
ifneq ($(strip $(K_DEPS)),)
-include $(K_DEPS)
endif
ifneq ($(strip $(C43_DEPS)),)
-include $(C43_DEPS)
endif
ifneq ($(strip $(S67_DEPS)),)
-include $(S67_DEPS)
endif
ifneq ($(strip $(SA_DEPS)),)
-include $(SA_DEPS)
endif
ifneq ($(strip $(S43_DEPS)),)
-include $(S43_DEPS)
endif
ifneq ($(strip $(OPT_DEPS)),)
-include $(OPT_DEPS)
endif
ifneq ($(strip $(S64_DEPS)),)
-include $(S64_DEPS)
endif
ifneq ($(strip $(C_UPPER_DEPS)),)
-include $(C_UPPER_DEPS)
endif
ifneq ($(strip $(C55_DEPS)),)
-include $(C55_DEPS)
endif
endif

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 

# All Target
all: vpif_lcd_loopback.out

# Tool invocations
vpif_lcd_loopback.out: $(OBJS) $(CMD_SRCS) $(GEN_CMDS)
	@echo 'Building target: $@'
	@echo 'Invoking: C6000 Linker'
	"C:/ti/ccsv5/tools/compiler/c6000_7.4.4/bin/cl6x" -mv6740 -g --gcc --define=c6748 --diag_warning=225 --abi=eabi -z -m"vpif_lcd_loopback_c674x_c6748_lcdkC6748.map" --warn_sections -i"C:/ti/ccsv5/tools/compiler/c6000_7.4.4/lib" -i"C:/ti/ccsv5/tools/compiler/c6000_7.4.4/include" -i"../../../../../../../binary/c674x/cgt_ccs/c6748/drivers/Debug" -i"../../../../../../../binary/c674x/cgt_ccs/c6748/lcdkC6748/platform/Debug" -i"../../../../../../../binary/c674x/cgt_ccs/c6748/system_config/Debug" -i"../../../../../../../binary/c674x/cgt_ccs/c6748/ipclib/Debug" -i"../../../../../../../binary/c674x/cgt_ccs/c6748/usblib/Debug" -i"../../../../../../../binary/c674x/cgt_ccs/utils/Debug" -i"../../../../../../../binary/c674x/cgt_ccs/grlib/Debug" -i"../../../../../../../binary/c674x/cgt_ccs/nandlib/Debug" --reread_libs --xml_link_info="vpif_lcd_loopback_linkInfo.xml" --rom_model -o "vpif_lcd_loopback.out" $(ORDERED_OBJS)
	@echo 'Finished building target: $@'
	@echo ' '
	@$(MAKE) --no-print-directory post-build

# Other Targets
clean:
	-$(RM) $(C6000_EXECUTABLE_OUTPUTS__QUOTED) "vpif_lcd_loopback.out"
	-$(RM) "adv7343.pp" "cbcr422sp_to_rgb565_dsp.pp" "cdce913.pp" "codecif.pp" "i2cgpio.pp" "tvp5147.pp" "vpif_lcd_loopback.pp" 
	-$(RM) "adv7343.obj" "cbcr422sp_to_rgb565_dsp.obj" "cdce913.obj" "codecif.obj" "i2cgpio.obj" "tvp5147.obj" "vpif_lcd_loopback.obj" 
	-@echo 'Finished clean'
	-@echo ' '

post-build:
	-@mkdir ..\..\..\..\..\..\..\binary\c674x\cgt_ccs\c6748\lcdkC6748\vpif_lcd_loopback\Debug & copy *.out ..\..\..\..\..\..\..\binary\c674x\cgt_ccs\c6748\lcdkC6748\vpif_lcd_loopback\Debug
	-@echo ' '

.PHONY: all clean dependents
.SECONDARY: post-build

-include ../makefile.targets


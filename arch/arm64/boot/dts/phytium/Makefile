# SPDX-License-Identifier: GPL-2.0

## pe220x general demo development board series.
dtb-$(CONFIG_ARCH_PHYTIUM) += pe2204-demo-ddr4.dtb
dtb-$(CONFIG_ARCH_PHYTIUM) += pe2202-demo-ddr4.dtb
dtb-$(CONFIG_ARCH_PHYTIUM) += pe2201-demo-ddr4.dtb

## pe220x specific industry development board series.
dtb-$(CONFIG_ARCH_PHYTIUM) += pe2204-miniitx-board.dtb
dtb-$(CONFIG_ARCH_PHYTIUM) += pe2202-miniitx-board.dtb
dtb-$(CONFIG_ARCH_PHYTIUM) += pe2204-vpx-board.dtb
dtb-$(CONFIG_ARCH_PHYTIUM) += pe2204-edu-board.dtb
dtb-$(CONFIG_ARCH_PHYTIUM) += pe2204-come-board.dtb
dtb-$(CONFIG_ARCH_PHYTIUM) += pe2202-power-board.dtb
dtb-$(CONFIG_ARCH_PHYTIUM) += pe2204-hanwei-board.dtb
dtb-$(CONFIG_ARCH_PHYTIUM) += phytiumpi_firefly.dtb
dtb-$(CONFIG_ARCH_PHYTIUM) += pe2202-chillipi-edu-board.dtb

dtbo-$(CONFIG_ARCH_PHYTIUM) += px210.dtbo
dtbo-$(CONFIG_ARCH_PHYTIUM) += usb2_host_for_pe220x.dtbo

#Enable support for device-tree overlay
DTC_FLAGS += -@

targets += dtbs dtbs_install
targets += $(dtbo-y)

always-y := $(dtbo-y)

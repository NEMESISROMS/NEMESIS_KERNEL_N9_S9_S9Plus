obj-$(CONFIG_USE_DIRECT_IS_CONTROL)	+= fimc-is-interface-sensor.o \
				       fimc-is-interface-actuator.o \
				       fimc-is-control-sensor.o \
				       fimc-is-control-actuator.o \
				       fimc-is-device-sensor-peri.o

EXTRA_CFLAGS += -Idrivers/media/platform/exynos/fimc-is2_star
EXTRA_CFLAGS += -Idrivers/media/platform/exynos/fimc-is2_star/include
ifeq ($(CONFIG_COMPANION_DIRECT_USE),y)
EXTRA_CFLAGS += -Idrivers/media/platform/exynos/fimc-is2_star/vendor/mcd/preprocessor
endif

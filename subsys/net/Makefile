obj-$(CONFIG_NET_BUF) += buf.o
obj-$(CONFIG_NET_HOSTNAME_ENABLE) += hostname.o

ifeq ($(CONFIG_NETWORKING),y)
ifeq ($(CONFIG_NET_L2_RAW_CHANNEL),y)
obj-y += ip/net_pkt.o
else
obj-y += ip/
endif

endif

include lib/Makefile
obj-y += lib/

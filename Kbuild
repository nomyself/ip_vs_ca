ip_vs_ca-objs := ca_core.o ca_conn.o ca_ctl.o ca_proto.o utils.o
obj-m += ip_vs_ca.o

hostprogs-y := udpd
always := $(hostprogs-y)
HOSTCFLAGS_udpd.o += -I$(objtree)/usr/include

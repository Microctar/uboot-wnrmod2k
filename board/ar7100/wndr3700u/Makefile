include $(TOPDIR)/config.mk

LIB	= lib$(BOARD).a

OBJS	= $(BOARD).o ../common/ar7100_flash.o rtl8366s_phy.o wndr3700u_pci.o ../common/generic_spi.o
SOBJS	= lowlevel_init.o

$(LIB):	.depend $(OBJS) $(SOBJS)
	$(AR) crv $@ $(OBJS) $(SOBJS)

#########################################################################

.depend:	Makefile $(SOBJS:.o=.S) $(OBJS:.o=.c)
		$(CC) -M $(CFLAGS) $(SOBJS:.o=.S) $(OBJS:.o=.c) > $@

sinclude .depend

#########################################################################

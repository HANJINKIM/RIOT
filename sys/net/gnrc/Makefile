ifneq (,$(filter gnrc_icmpv6,$(USEMODULE)))
  DIRS += network_layer/icmpv6
endif
ifneq (,$(filter gnrc_icmpv6_echo,$(USEMODULE)))
  DIRS += network_layer/icmpv6/echo
endif
ifneq (,$(filter gnrc_icmpv6_error,$(USEMODULE)))
  DIRS += network_layer/icmpv6/error
endif
ifneq (,$(filter gnrc_ipv6,$(USEMODULE)))
  DIRS += network_layer/ipv6
endif
ifneq (,$(filter gnrc_ipv6_ext,$(USEMODULE)))
  DIRS += network_layer/ipv6/ext
endif
ifneq (,$(filter gnrc_ipv6_hdr,$(USEMODULE)))
  DIRS += network_layer/ipv6/hdr
endif
ifneq (,$(filter gnrc_ipv6_nc,$(USEMODULE)))
  DIRS += network_layer/ipv6/nc
endif
ifneq (,$(filter gnrc_ipv6_netif,$(USEMODULE)))
  DIRS += network_layer/ipv6/netif
endif
ifneq (,$(filter gnrc_ipv6_nib,$(USEMODULE)))
  DIRS += network_layer/ipv6/nib
endif
ifneq (,$(filter gnrc_ipv6_whitelist,$(USEMODULE)))
  DIRS += network_layer/ipv6/whitelist
endif
ifneq (,$(filter gnrc_ipv6_blacklist,$(USEMODULE)))
  DIRS += network_layer/ipv6/blacklist
endif
ifneq (,$(filter gnrc_ndp,$(USEMODULE)))
  DIRS += network_layer/ndp
endif
ifneq (,$(filter gnrc_ndp_internal,$(USEMODULE)))
  DIRS += network_layer/ndp/internal
endif
ifneq (,$(filter gnrc_ndp_host,$(USEMODULE)))
  DIRS += network_layer/ndp/host
endif
ifneq (,$(filter gnrc_ndp_node,$(USEMODULE)))
  DIRS += network_layer/ndp/node
endif
ifneq (,$(filter gnrc_ndp_router,$(USEMODULE)))
  DIRS += network_layer/ndp/router
endif
ifneq (,$(filter gnrc_ndp2,$(USEMODULE)))
    DIRS += network_layer/ndp2
endif
ifneq (,$(filter gnrc_netapi,$(USEMODULE)))
  DIRS += netapi
endif
ifneq (,$(filter gnrc_netif,$(USEMODULE)))
  DIRS += netif
endif
ifneq (,$(filter gnrc_netif_hdr,$(USEMODULE)))
  DIRS += netif/hdr
endif
ifneq (,$(filter gnrc_netreg,$(USEMODULE)))
  DIRS += netreg
endif
ifneq (,$(filter gnrc_nettest,$(USEMODULE)))
  DIRS += nettest
endif
ifneq (,$(filter gnrc_mac,$(USEMODULE)))
  DIRS += link_layer/gnrc_mac
endif
ifneq (,$(filter gnrc_pkt,$(USEMODULE)))
  DIRS += pkt
endif
ifneq (,$(filter gnrc_lwmac,$(USEMODULE)))
  DIRS += link_layer/lwmac
endif
ifneq (,$(filter gnrc_pktbuf_static,$(USEMODULE)))
  DIRS += pktbuf_static
endif
ifneq (,$(filter gnrc_pktbuf,$(USEMODULE)))
  DIRS += pktbuf
endif
ifneq (,$(filter gnrc_priority_pktqueue,$(USEMODULE)))
  DIRS += priority_pktqueue
endif
ifneq (,$(filter gnrc_pktdump,$(USEMODULE)))
  DIRS += pktdump
endif
ifneq (,$(filter gnrc_rpl,$(USEMODULE)))
  DIRS += routing/rpl
endif
ifneq (,$(filter gnrc_rpl_srh,$(USEMODULE)))
  DIRS += routing/rpl/srh
endif
ifneq (,$(filter gnrc_rpl_p2p,$(USEMODULE)))
  DIRS += routing/rpl/p2p
endif
ifneq (,$(filter gnrc_sixlowpan,$(USEMODULE)))
  DIRS += network_layer/sixlowpan
endif
ifneq (,$(filter gnrc_sixlowpan_ctx,$(USEMODULE)))
  DIRS += network_layer/sixlowpan/ctx
endif
ifneq (,$(filter gnrc_sixlowpan_frag,$(USEMODULE)))
  DIRS += network_layer/sixlowpan/frag
endif
ifneq (,$(filter gnrc_sixlowpan_iphc,$(USEMODULE)))
  DIRS += network_layer/sixlowpan/iphc
endif
ifneq (,$(filter gnrc_sixlowpan_nd,$(USEMODULE)))
  DIRS += network_layer/sixlowpan/nd
endif
ifneq (,$(filter gnrc_sixlowpan_nd_router,$(USEMODULE)))
  DIRS += network_layer/sixlowpan/nd/router
endif
ifneq (,$(filter gnrc_sixlowpan_netif,$(USEMODULE)))
  DIRS += network_layer/sixlowpan/netif
endif
ifneq (,$(filter gnrc_slip,$(USEMODULE)))
  DIRS += link_layer/slip
endif
ifneq (,$(filter gnrc_sock,$(USEMODULE)))
  DIRS += sock
endif
ifneq (,$(filter gnrc_sock_ip,$(USEMODULE)))
  DIRS += sock/ip
endif
ifneq (,$(filter gnrc_sock_udp,$(USEMODULE)))
  DIRS += sock/udp
endif
ifneq (,$(filter gnrc_udp,$(USEMODULE)))
  DIRS += transport_layer/udp
endif
ifneq (,$(filter gnrc_tcp,$(USEMODULE)))
  DIRS += transport_layer/tcp
endif
ifneq (,$(filter gnrc_tftp,$(USEMODULE)))
  DIRS += application_layer/tftp
endif

include $(RIOTBASE)/Makefile.base

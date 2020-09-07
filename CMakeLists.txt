project(util-lorawan-packets)

add_library("${PROJECT_NAME}"
        crypto/aes.c
        crypto/cmac.c
        crypto/lw_crypto.c
        lw_packets.c
        aux.h)

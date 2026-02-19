file(GLOB SRCS "Fusion/*.c")

idf_component_register(SRCS ${SRCS}
    INCLUDE_DIRS "Fusion"
    REQUIRES driver kestech_lsm9ds1 kes_gps esp_event u8g2)


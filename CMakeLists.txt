set(edgehog_srcs "src/edgehog_device.c")

idf_component_register(SRCS "${edgehog_srcs}"
        INCLUDE_DIRS "include"
        REQUIRES astarte-device-sdk-esp32 nvs_flash)

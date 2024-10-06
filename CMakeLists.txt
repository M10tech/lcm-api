idf_component_register(SRCS "lcm_api.c"
                    INCLUDE_DIRS "."
                    PRIV_REQUIRES esp_partition nvs_flash esp32-homekit esp_driver_gpio)
#TODO: make the esp32-homekit requirement conditional somehow

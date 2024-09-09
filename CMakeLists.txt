idf_component_register(SRCS "lcm_api.c"
                    INCLUDE_DIRS "."
                    PRIV_REQUIRES esp_partition esp32-homekit)
#TODO: make the homekit reuirement conditional somehow

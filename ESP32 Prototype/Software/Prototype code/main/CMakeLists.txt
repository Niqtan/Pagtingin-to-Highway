idf_component_register(SRCS "main.c"
                       INCLUDE_DIRS "."
                       REQUIRES driver esp_timer mqtt esp_wifi
                       PRIV_REQUIRES driver esp_timer mqtt esp_wifi)

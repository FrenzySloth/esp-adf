set(COMPONENT_SRCS "fatfs_stream.c"
                    "i2s_stream.c"
                    "http_stream.c"
                    "hls_playlist.c"
                    "raw_stream.c"
                    "spiffs_stream.c"
                    "tone_stream.c"
                    "algorithm_stream.c")
set(COMPONENT_ADD_INCLUDEDIRS "include")


set(COMPONENT_REQUIRES audio_pipeline audio_sal esp_http_client spiffs esp-adf-libs audio_board esp-sr bootloader_support)

register_component()

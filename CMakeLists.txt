set(srcs "shox96_0_2.c"
        "sqlite3.c"
        "esp32.c" )
		
set(COMPONENT_ADD_INCLUDEDIRS "include")
set(COMPONENT_REQUIRES spi_flash)
 

register_component()



generate_arduino_library(RF24MeshLib
        BOARD ${BOARD}
        SRCS RF24Mesh.cpp
        HDRS RF24Mesh_config.h RF24Mesh.h
        LIBS SPILib RF24NetworkLib
        )



generate_arduino_library(RF24MeshLib
        BOARD nano
        SRCS RF24Mesh.cpp
        HDRS RF24Mesh_config.h RF24Mesh.h
        LIBS RF24NetworkLib
        )

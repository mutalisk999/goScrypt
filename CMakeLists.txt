# cmake -G "MinGW Makefiles" . && make

cmake_minimum_required(VERSION 3.10)

add_definitions()

set(SCRYPT_SRC
    scrypt.cpp
)

add_library(scrypt STATIC ${SCRYPT_SRC})
target_link_libraries(scrypt)


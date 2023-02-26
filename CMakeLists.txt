# Adafruit Bus IO Library
# https://github.com/adafruit/Adafruit_BusIO
# MIT License

cmake_minimum_required(VERSION 3.5)

idf_component_register(SRCS "./src/SFE_MicroOLED.cpp" "./src/hardware.cpp" 
                       INCLUDE_DIRS "./src/"
                       REQUIRES "arduino")

project(SparkFun_Micro_OLED_Arduino_Library)

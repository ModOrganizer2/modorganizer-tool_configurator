cmake_minimum_required(VERSION 3.16)

find_package(mo2-cmake CONFIG REQUIRED)

add_custom_target(pyCfg ALL)

mo2_configure_python(pyCfg SIMPLE)

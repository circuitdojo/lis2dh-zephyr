#
# Copyright (c) 2022 Circuit Dojo LLC
#

# Subdirectories
add_subdirectory_ifdef(CONFIG_LIS2DH_ENHANCED driver)

# Include headers
zephyr_include_directories(include)
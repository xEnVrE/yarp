# SPDX-FileCopyrightText: 2006-2021 Istituto Italiano di Tecnologia (IIT)
# SPDX-FileCopyrightText: 2006-2010 RobotCub Consortium
# SPDX-License-Identifier: BSD-3-Clause

cmake_minimum_required(VERSION 3.16)

find_package(YARP REQUIRED)

yarp_begin_plugin_library(baz)
add_subdirectory(bazBot)
add_subdirectory(bazDevice)
yarp_end_plugin_library(baz)

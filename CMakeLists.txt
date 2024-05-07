cmake_minimum_required(VERSION 3.23)
project(NIIALG)

set(CMAKE_CXX_STANDARD 14)


add_executable(NIIALG
        source/main.cpp
        Source/nifti_clib/nifti1_io.c Source/nifti_clib/nifti1_io.c Source/nifti_clib/nifti1.h Source/nifti_clib/nifti1_io_version.h
        Source/znzlib/znzlib.c Source/znzlib/znzlib.h Source/znzlib/znzlib_version.h)

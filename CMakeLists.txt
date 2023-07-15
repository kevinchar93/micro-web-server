cmake_minimum_required(VERSION 3.10)

project(micro-web-server
                VERSION 0.1.0
                DESCRIPTION "a simple web server written in C17"
                LANGUAGES C)

add_executable(micro-web-server
                        src/main.c)

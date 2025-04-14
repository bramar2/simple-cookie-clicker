cmake_minimum_required(VERSION 3.27)
project(CookieClicker)

find_package(SDL3 REQUIRED)
add_executable(CookieClicker CookieClicker.c CookieBmp.c CookieBmp.h Counter.c Counter.h Screen.h Utils.c Utils.h Cookie.c Cookie.h Cursor.c Cursor.h)
target_link_libraries(CookieClicker SDL3::SDL3)

cmake_minimum_required(VERSION 3.1...3.28)

project(
	Hitscanner
	VERSION 0.0
	LANGUAGES CXX
)

add_executable(hitscanner_server main.cxx)
set_property(TARGET hitscanner_server PROPERTY CXX_STANDARD 20)

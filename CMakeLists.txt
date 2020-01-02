cmake_minimum_required(VERSION 3.0)

project(main)
#代码路径
aux_source_directory（. DIR_TOOT_SRCS）
#debug模式
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -g")
#生成可执行文件
add_executable(main ${DIR_TOOT_SRCS})
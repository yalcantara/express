cmake_minimum_required(VERSION 3.10)
project(main C CXX)

set(CMAKE_CXX_STANDARD 17)


include_directories(include)
add_executable(main main.cpp)

#Uncomment the following line if dl lib is needed
#target_link_libraries(main ${CMAKE_DL_LIBS})



#Example to add boost and other system libraries
#find_package(Boost REQUIRED COMPONENTS system)
#find_package(OpenSSL 1.0.0 REQUIRED)


#target_link_libraries(main
#        -L/opt/mongo-cxx-driver/lib -lbsoncxx
#        -L/opt/mongo-cxx-driver/lib -lmongocxx
#        cpprest
#        Boost::boost
#        Boost::system
#        OpenSSL::SSL)

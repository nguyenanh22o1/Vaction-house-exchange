cmake_minimum_required(VERSION 3.21)
project(group-project-one-file)

set(CMAKE_CXX_STANDARD 14)

add_executable(group-project-one-file

        Constant.h
        DataType/Date/Date.h
        Object/User/User.h
        Object/Request/Request.h
        Object/Review/Review.h
        Object/HouseOccupy/HouseOccupy.h
        Object/MemberOccupy/MemberOccupy.h
        Object/House/House.h
        Object/Member/Member.h
        Object/Admin/Admin.h
        Helper/Helper.h
        System/System.h
        StorageManager/InputStorageManager/InputStorageManager.h
        StorageManager/OutputStorageManager/OutputStorageManager.h
        Validation/Validation.h

        DataType/Date/Date.cpp
        Object/User/User.cpp
        Object/Request/Request.cpp
        Object/Review/Review.cpp
        Object/HouseOccupy/HouseOccupy.cpp
        Object/MemberOccupy/MemberOccupy.cpp
        Object/House/House.cpp
        Object/Member/Member.cpp
        Object/Admin/Admin.cpp
        Helper/Helper.cpp
        System/System.cpp
        StorageManager/InputStorageManager/InputStorageManager.cpp
        StorageManager/OutputStorageManager/OutputStorageManager.cpp
        Validation/Validation.cpp

        main.cpp
        )






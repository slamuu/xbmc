set(SOURCES WebSocket.cpp
            WebSocketManager.cpp
            WebSocketV13.cpp
            WebSocketV8.cpp)

set(HEADERS sha1.hpp
            WebSocket.h
            WebSocketManager.h
            WebSocketV13.h
            WebSocketV8.h)

core_add_library(network_websockets)

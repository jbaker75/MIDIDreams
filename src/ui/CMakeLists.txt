qt_add_executable(MIDIDreams
    main.cpp
    mainwindow.cpp
    mainwindow.ui
)
target_link_libraries(MIDIDreams PRIVATE Qt6::Widgets core)
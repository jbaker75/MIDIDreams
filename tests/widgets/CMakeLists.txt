qt_add_executable(test_widgets
    test_mygaugewidget.cpp
)
target_link_libraries(test_widgets PRIVATE Qt6::Test custom_widgets)
add_test(NAME WidgetTests COMMAND test_widgets)
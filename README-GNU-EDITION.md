### GNU edition features:

* customizable `make install` and `make uninstall` Makefile targets
* implicit default install and uninstall Makefile rules
* Makefile references DESTDIR and PREFIX for INSTALLDIR ('/usr' default)
* "Makefile" build directory matches the GUI Target name
* "($(CONFIG))" indicator beside each "Compiling ..." console trace
* global "Extra library search paths"
* customizable license header added to each source file
* avoids pkg-config check for libcurl when unused (JUCE_USE_CURL unset or false)


### GNU edition modified files:

* extras/Projucer/Source/ComponentEditor/jucer_GeneratedCode.cpp
* extras/Projucer/Source/Project Saving/jucer_ProjectExport_Make.h
* extras/Projucer/Source/Project Saving/jucer_ProjectExporter.cpp
* extras/Projucer/Source/Project Saving/jucer_ProjectExporter.h
* extras/Projucer/Source/Project Saving/jucer_ProjectSaver.h
* extras/Projucer/Source/Project/jucer_Module.cpp
* extras/Projucer/Source/Project/jucer_Project.cpp
* extras/Projucer/Source/Project/jucer_Project.h
* extras/Projucer/Source/Utility/jucer_CodeHelpers.cpp
* extras/Projucer/Source/Utility/jucer_PresetIDs.h

* kludges
* * modules/juce_gui_basics/native/juce_linux_Windowing.cpp

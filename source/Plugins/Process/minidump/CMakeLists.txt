include_directories(../Utility)

add_lldb_library(lldbPluginProcessMinidump
  MinidumpTypes.cpp
  MinidumpParser.cpp
  RegisterContextMinidump_x86_64.cpp
  )

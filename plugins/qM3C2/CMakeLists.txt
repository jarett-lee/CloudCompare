cmake_minimum_required(VERSION 2.8)

option( INSTALL_QM3C2_PLUGIN "Check to install qM3C2 plugin" OFF )

if (INSTALL_QM3C2_PLUGIN)

#CloudCompare 'M3C2' plugin
project( QM3C2_PLUGIN_DLL )

include( ../CMakePluginTpl.cmake )

endif()

add_library(
   EcuAb
   ./CanIf/LATEST/CanIf.cpp
   ./CryIf/LATEST/CryIf.cpp
   ./Ea/LATEST/Ea.cpp
   ./EthIf/LATEST/EthIf.cpp
   ./Fee/LATEST/Fee.cpp
   ./FrIf/LATEST/FrIf.cpp
   ./LinIf/LATEST/LinIf.cpp
   ./LinTp/LATEST/LinTp.cpp
   ./MemIf/LATEST/MemIf.cpp
   ./WdgIf/LATEST/WdgIf.cpp
)

include_directories(
   ../../common/LATEST
   ../../common/LATEST/Compiler_Abstraction_GNU/LATEST
   ../../AUTOSAR_Bsw/LATEST/Swc_EcuM/LATEST
)


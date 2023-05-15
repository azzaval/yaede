# CMakeList.txt: projekt CMake dla elementu yaede-base-cli-cmk, dołącz źródło i zdefiniuj
# tutaj logikę specyficzną dla projektu.
#

# Dodaj źródło do pliku wykonywalnego tego projektu.
add_executable (yaede-base-cli-cmk "yaede-base-cli-cmk.cpp" "yaede-base-cli-cmk.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET yaede-base-cli-cmk PROPERTY CXX_STANDARD 20)
endif()

# TODO: Dodaj testy i zainstaluj elementy docelowe w razie potrzeby.

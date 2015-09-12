#--------------------------------------------------------
# The CMakeLists.txt for:               lib/documentation
# Author(s):                                  Simon Rohou
#--------------------------------------------------------

SET(SRC
  MOOSAppDocumentation.cpp
  tinyxml2.cpp
)

SET(HEADERS
  MOOSAppDocumentation.h
  tinyxml2.h
)

ADD_LIBRARY(xml-documentation ${SRC})

TARGET_LINK_LIBRARIES(xml-documentation
  mbutil
  )

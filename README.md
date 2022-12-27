How to use precompiled headers
- Enable precompiled headers in all configurations for all *.cpp files. It can be done on the “Precompiled Header” tab:
  Set the value “Use (/Yu)” for the “Precompiled Header” option.
  Set “stdafx.h” for the “Precompiled Header File” option.
  Set “$(IntDir)$(TargetName).pch” for the “Precompiled Header Output File” option.

- Create an stdafx.h file, and add it into the project. We will include those headers we want to be preprocessed in advance into this file.
- Create an stdafx.cpp file, and add it into the project. This file has only one line: #include “stdafx.h”.
- Change the settings for the stdafx.cpp file in all configurations; set the value “Create (/Yc)” for the “Precompiled Header” option.

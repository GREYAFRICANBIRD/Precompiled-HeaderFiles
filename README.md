> HOW TO USE PRECOMPILED HEADERS 
- Create 2 files: stdafx.h, stdafx.cpp  (file i'm uploaded above)

>> SET-UP IN MICROSOFT VISUAL STUDIO 
- Project / properties / C/C++ / Precompiled Headers 
- Precompiled Header:               Use (/Yu)
- Precompiled Header File:          stdafx.h
- Precompiled Header Output File    $(IntDir)$(TargetName).pch
- Configuration:                    All Configurations

  

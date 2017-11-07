# OpenGLES2.0在windows平台的实现

接口是OpenGLES的，真正的实现是d3d    
windows平台最后调用的是：    
xp:   d3dcompiler_43.dll    
win7: d3dcompiler_46.dll/d3dcompiler_47.dll

- # Version 1.0
```
EGL version 1.0, approved on July 23, 2003, is the original version of EGL. EGL
was loosely based on GLX 1.3, generalized to be implementable on many different 
operating systems and window systems and simplified to reflect the needs of
embedded devices running OpenGL ES .
```

- # Version 1.1
```
EGL version 1.1, approved on August 5, 2004, is the second release of EGL. It
adds power management and swap control functionality based on vendor extensions 
from Imagination Technologies, and optional render-to-texture functionality
based on the WGL_ARB_render_texture extension defined by the OpenGL
ARB for desktop OpenGL.
B.1 Revision 1.1.2
EGL version 1.1.2 (revision 2 of EGL 1.1), approved on November 10, 2004, clarified 
that vertex buffer objects are shared among contexts in the same fashion as
texture objects
```

- # Version 1.2
```
EGL version 1.2, approved on July 8, 2005, is the third release of EGL. It adds
support for the OpenVG 2D client API, in addition to support for OpenGL ES, and
generalizes EGL concepts to enable supporting other client APIs in the future.
```

- # Version 1.3
```
EGL version 1.3 was voted out of the OpenKODE Working Group on December
4, 2006, and formally approval by the Khronos Board of Promoters on February 8,
2007. EGL 1.3 is the fourth release of EGL.
```

- # Version 1.4
```
EGL version 1.4 was voted out of the Khronos Technical Working Group on March
25, 2008, and formally approved by the Khronos Board of Promoters on May 29,
2008.
```

- # Version 1.5
```
EGL version 1.5 was voted out of the Khronos Technical Working Group on January 31, 2014, 
and formally approved by the Khronos Board of Promoters on
March 14, 2014.
```

- # vs2015 Community  
vs2015社区版，功能全但是不能是商业用途。  
URL:   
https://www.visualstudio.com/downloads/download-visual-studio-vs  

Visual Studio 2015 Community ISO 文件实际的下载地址为：  
http://download.microsoft.com/download/0/B/C/0BC321A4-013F-479C-84E6-4A2F90B11269/vs2015.com_enu.iso  

新建项目（控制台应用程序）时，新建空项目，就不会生成一些和windows平台相关的代码，更利于跨平台的开发。

# webcam_capture
Just webcam capture

## Tips
https://wiki.archlinux.org/index.php/webcam_setup

http://www.linuxintro.org/wiki/Set_up_a_Webcam_with_Linux

# 
1 He fet un fork del repository webcam_capture de beta-tools
2 He clonat el meu repository webcam_capture
3 He creat la carpeta build
4 He posat llibreries amb "cmake .."
5 He compilat amb "make"
6 He executat amb "./webcam_capture

# 
sergi@optimus:~/Documentos/MASTER/SESSIO1$ cd webcam
sergi@optimus:~/Documentos/MASTER/SESSIO1/webcam$ git clone https://github.com/sescude/webcam_capture.git
Clonando en 'webcam_capture'...
remote: Enumerating objects: 62, done.
remote: Total 62 (delta 0), reused 0 (delta 0), pack-reused 62
Desempaquetando objetos: 100% (62/62), listo.
sergi@optimus:~/Documentos/MASTER/SESSIO1/webcam$ ls
webcam_capture
sergi@optimus:~/Documentos/MASTER/SESSIO1/webcam$ cd webcam_capture
sergi@optimus:~/Documentos/MASTER/SESSIO1/webcam/webcam_capture$ ls
CMakeLists.txt  commands  LICENSE  README.md  src
sergi@optimus:~/Documentos/MASTER/SESSIO1/webcam/webcam_capture$ mkdir build && cd build
sergi@optimus:~/Documentos/MASTER/SESSIO1/webcam/webcam_capture/build$ cmake..
cmake..: orden no encontrada
sergi@optimus:~/Documentos/MASTER/SESSIO1/webcam/webcam_capture/build$ cmake ..
-- The C compiler identification is GNU 7.3.0
-- The CXX compiler identification is GNU 7.3.0
-- Check for working C compiler: /usr/bin/cc
-- Check for working C compiler: /usr/bin/cc -- works
-- Detecting C compiler ABI info
-- Detecting C compiler ABI info - done
-- Detecting C compile features
-- Detecting C compile features - done
-- Check for working CXX compiler: /usr/bin/c++
-- Check for working CXX compiler: /usr/bin/c++ -- works
-- Detecting CXX compiler ABI info
-- Detecting CXX compiler ABI info - done
-- Detecting CXX compile features
-- Detecting CXX compile features - done
-- Found OpenCV: /usr (found version "3.2.0") 
-- Configuring done
-- Generating done
-- Build files have been written to: /home/sergi/Documentos/MASTER/SESSIO1/webcam/webcam_capture/build
sergi@optimus:~/Documentos/MASTER/SESSIO1/webcam/webcam_capture/build$ make
Scanning dependencies of target webcam_capture
[ 50%] Building CXX object CMakeFiles/webcam_capture.dir/src/webcam_capture.cpp.o
[100%] Linking CXX executable webcam_capture
[100%] Built target webcam_capture
sergi@optimus:~/Documentos/MASTER/SESSIO1/webcam/webcam_capture/build$ ./web_campture
bash: ./web_campture: No existe el archivo o el directorio
sergi@optimus:~/Documentos/MASTER/SESSIO1/webcam/webcam_capture/build$ ls
CMakeCache.txt  CMakeFiles  cmake_install.cmake  Makefile  webcam_capture
sergi@optimus:~/Documentos/MASTER/SESSIO1/webcam/webcam_capture/build$ ./webcam_capture
Opening video device 0


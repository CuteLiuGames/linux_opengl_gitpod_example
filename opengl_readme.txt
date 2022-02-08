//  CodingCoffee  OpenGL Gitpod Template more courses: www.codingcoffee.org 

 g++ triangle.cpp -lglut -lGL -o a.out 

//  glfw windows init and triangle Examples
g++ glfw_windows.cpp glad.c -o a.out -lglfw -lGL -lm -lXrandr -lXi -lX11 -lXxf86vm -lpthread -ldl -lXinerama -lXcursor

 g++ -pthread -o a.out test_glfw_triangle.cpp glad.c -lglfw -lGLU -lGL -lXrandr -lXxf86vm -lXi -lXinerama -lX11 -lrt -ldl

 g++ -pthread -o a.out test_glfw.cpp -lglfw -lGLU -lGL -lXrandr -lXxf86vm -lXi -lXinerama -lX11 -lrt -ldl
 
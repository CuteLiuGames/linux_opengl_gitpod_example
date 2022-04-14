//  CodingCoffee  OpenGL Gitpod Template more courses: www.codingcoffee.org 

//  CodingCoffee GLFW Basic Example 
sudo apt-get install libglfw3 && sudo apt-get install libglfw3-dev


g++ -pthread -o test_window test_glfw.cpp -lglfw -lGLU -lGL -lXrandr -lXxf86vm -lXi -lXinerama -lX11 -lrt -ldl

//  ----- glfw hello windows ----------
g++ glfw_windows.cpp glad.c -o hello_window -lglfw -lGL -lm -lXrandr -lXi -lX11 -lXxf86vm -lpthread -ldl -lXinerama -lXcursor


//  ----- glfw triangle example ------ 
g++ -pthread -o glfw_tri test_glfw_triangle.cpp ./libglad.a  -lglfw  -lGLU -lGL -lXrandr -lXxf86vm -lXi -lXinerama -lX11 -lrt -ldl


//   OpenGL reference
https://learnopengl.com/Getting-started/OpenGL
g++ -pthread -o glfw_sha hello_shader.cpp ./libglad.a  -lglfw  -lGLU -lGL -lXrandr -lXxf86vm -lXi -lXinerama -lX11 -lrt -ldl
g++ -pthread -o glfw_sha_2 hello_shader_2.cpp ./libglad.a  -lglfw  -lGLU -lGL -lXrandr -lXxf86vm -lXi -lXinerama -lX11 -lrt -ldl

g++ checkerboard.cpp   -lglut -lGL -lGLU -o a.out

gitpod /workspace/linux_opengl_gitpod_example (master) $ g++ checkerboard2.cpp   -lglut -lGL -lGLU -o a.out
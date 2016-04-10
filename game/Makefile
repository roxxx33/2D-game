all: try

#try: Sample_GL3_3D.cpp glad.c
#	g++ `pkg-config --cflags glfw3` -o sample3D Sample_GL3_3D.cpp glad.c `pkg-config --static --libs glfw3`
#	g++ -o sample3D Sample_GL3.cpp glad.c -lGL -lglfw
#g++ -o sample2D Sample_GL3_2D.cpp glad.c -lGL -lglfw -ldl
try: Sample_GL3_2D.cpp glad.c
	g++ `pkg-config --cflags glfw3` -o try try.cpp glad.c `pkg-config --static --libs glfw3`
clean:
	 try

sayhello:main.c libhello.so hello.h
	gcc main.c -I /home/duanqin/zuopin/C -L. -lhello -o sayhello
libhello.so:hello.c
	gcc -fPIC -shared hello.c -I /home/duanqin/zuopin/C -o libhello.so
clean:
	rm *so* *.o sayhello

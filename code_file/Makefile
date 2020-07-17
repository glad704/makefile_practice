execute_file:	main.o sum.o sub.o mul.o div.o
		gcc -o execute_file main.c sum.c sub.c mul.c div.c

main.o:	main.c
	gcc -c main.c

sum.o:	sum.c
	gcc -c sum.c

sub.o:	sub.c
	gcc -c sub.c

mul.o:	mul.c
	gcc -c mul.c

div.o:	div.c
	gcc -c div.c

clean:	
	rm -rf execute_file 
	rm -rf /home/gladson/C/makefile_practice/obj_file/*.o 

putobj:	
	mv *.o /home/gladson/C/makefile_practice/obj_file

TARGET: exe
exe: evaluation.o dll.o diff.o
	gcc -g evaluation.o dll.o diff.o -o exe
evaluation.o: evaluation.c
	gcc -g -c evaluation.c -o evaluation.o
dll.o: dll.c
	gcc -g -c dll.c -o dll.o
diff.o: diff.c
	gcc -g -c diff.c -o diff.o
clean:
	rm -rf *o exe
run:
	./exe
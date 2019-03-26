all: prog

prog: arquivo.o arquivocomplementar.o
	gcc -o binario arquivo.o arquivocomplementar.o

arquivo.o: arquivo.c
		gcc -c arquivo.c

arquivocomplementar.o: arquivocomplementar.c
					gcc -c arquivocomplementar.c

clean:
	rm -rf *.o

rmproper: clean
	rm -rf binario

run: prog
		./binario
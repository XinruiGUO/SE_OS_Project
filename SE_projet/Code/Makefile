default: cliser

cliser: client_se.c serveur_se.c CreatBankImage.o targa_image.o
	gcc  -g client_se.c  CreatBankImage.o targa_image.o  -o c
	gcc  -g serveur_se.c CreatBankImage.o targa_image.o  -o s

CreatBankImage.o: CreatBankImage.c targa_image.o
	gcc -g -c CreatBankImage.c targa_image.o -o CreatBankImage.o

targa_image.o: targa_image.c
	gcc -g -c targa_image.c -o targa_image.o

clean:
	rm *.o, c, s

all: tcompute compute manage report

tcompute: tcompute.o 
	gcc -g -o tcompute tcompute.o

tcompute.o: hw4.h tcompute.c
	gcc -g -c tcompute.c

compute: compute.o 
	gcc -g -o compute compute.o

compute.o: hw4.h compute.c
	gcc -g -c compute.c

manage: manage.o
	gcc -g -o manage manage.o

manage.o: hw4.h manage.c
	gcc -g -c manage.c

report: report.o
	gcc -g -o report report.o

report.o: hw4.h report.c
	gcc -g -c report.c

clean: 
	rm tcompute tcompute.o compute compute.o manage manage.o report report.o

# Name of the project
PROJECT_NAME = Parking_Management_System



# All source code files
SRC = project_main.c\
src/parking.c


INC = inc
all.exe : $(SRC) 
	gcc $^ -I$(INC) -o $@

run : all.exe
	./all.exe

clean:
	del all.exe



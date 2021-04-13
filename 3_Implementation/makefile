PROJECT_NAME = Bank
SRC = src/PrintDetails.c \
src/RegisterAccount.c \
src/SearchAccount.c \
src/SortAccount.c \
src/Transaction.c \
src/WriteFile.c \
src/menu.c

INC_H = inc

$(PROJECT_NAME).exe : $(SRC) main.c
	gcc -I $(INC_H) $(SRC) main.c -o $(PROJECT_NAME).exe

run :
	$(PROJECT_NAME).exe

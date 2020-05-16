FC = gfortran -g
SOURCE = dungeon.o game.o gdt.o objects.o parser.o rooms.o subr.o timefnc.o verbs.o
EXE = dungeon

all : dungeon

dist : dungeon
	strip $(EXE)

dungeon : $(SOURCE)
	$(FC) -o $(EXE) $^


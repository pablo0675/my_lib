##
## EPITECH PROJECT, 2022
## Makefile
## File description:
## Makefile
##

CPPFLAGS += -I ../include
CPPFLAGS +=	-lcsfml-graphics
CPPFLAGS +=	-lcsfml-audio
CPPFLAGS += -lcsfml-system
CPPFLAGS += -lcsfml-window

SRC                     +=      close_programm.c
SRC                     +=      my_create_text.c
SRC                     +=      my_create_window.c
SRC                     +=      sprite_create.c
SRC                     +=      sprite_rect.c

OBJ	=	$(SRC:.c=.o)

NAME	=	libcsfml.a

all:	$(NAME)

$(NAME):	$(OBJ)
	ar rc $(NAME) $(OBJ)

clean:
	rm -f *.o

fclean:
	rm -f $(NAME)

.PHONY: all clean fclean
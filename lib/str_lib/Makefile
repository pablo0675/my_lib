##
## EPITECH PROJECT, 2022
## Makefile
## File description:
## Makefile
##

CPPFLAGS = -I ../include

SRC	+=	my_strcat.c
SRC	+=	my_strcmp.c
SRC	+=	my_strcpy.c
SRC	+=	my_strlen.c

OBJ	=	$(SRC:.c=.o)

NAME	=	libstring.a

all:	$(NAME)

$(NAME):	$(OBJ)
	ar rc $(NAME) $(OBJ)
	rm $(OBJ)
clean:
	rm -f $(OBJ)

fclean:
	rm $(NAME)

re: fclean all

.PHONY: fclean all clean

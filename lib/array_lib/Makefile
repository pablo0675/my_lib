##
## EPITECH PROJECT, 2022
## Makefile
## File description:
## Makefile
##

CPPFLAGS = -I ../include

SRC	+=	free_array.c
SRC	+=	print_array.c
SRC	+=	array_cat.c

OBJ	=	$(SRC:.c=.o)

NAME	=	libarray.a

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

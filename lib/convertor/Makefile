##
## EPITECH PROJECT, 2022
## Makefile
## File description:
## Makefile
##

CPPFLAGS = -I ../include

SRC	+=	my_atoi.c
SRC	+=	my_str_to_array.c

OBJ	=	$(SRC:.c=.o)

NAME	=	libconvertor.a

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

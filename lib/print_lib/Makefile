##
## EPITECH PROJECT, 2022
## Makefile
## File description:
## Makefile
##

CPPFLAGS = -I ../include

SRC	+=	my_print_free.c
SRC	+=	my_printf.c
SRC	+=	my_put_nbr.c
SRC	+=	my_putchar.c
SRC	+=	my_putstr.c

OBJ	=	$(SRC:.c=.o)

NAME	=	libprint.a

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

##
## Makefile for  in /home/zitouni/rendu/haha
## 
## Made by Yassine Zitouni
## Login   <zitoun_y@epitech.net>
## 
## Started on  Fri Jan 16 16:53:07 2015 Yassine Zitouni
## Last update Sun Mar 22 20:19:20 2015 Yassine Zitouni
##

CC	=	gcc

RM	=	rm -f

CFLAGS +=	-I./include

NAME	=	server

NAME2	=	client

SRCS	=	server.c	\


SRCS2	=	client.c	\
		get_next_line.c	\


OBJS	=	$(SRCS:.c=.o)

OBJS2	=	$(SRCS2:.c=.o)

all:		$(NAME) $(NAME2)

$(NAME):	$(OBJS)
		$(CC) $(OBJS) -o $(NAME)

$(NAME2):	$(OBJS2)
		$(CC) $(OBJS2) -o $(NAME2)

clean:
		$(RM) $(OBJS) $(OBJS2)

fclean:		clean
		$(RM) $(NAME) $(NAME2)

re:	fclean all

ice_tee :	fclean all
		$(RM) *~ *#

.PHONY:		all clean fclean re

# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: yxie <marvin@42.fr>                        +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2019/07/15 10:11:06 by yxie              #+#    #+#              #
#    Updated: 2019/09/12 09:57:50 by yxie             ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME = test

CC = gcc
CC_FLAGS = -Wall -Wextra -Werror -g -fsanitize=address
LFT_FLAGS = -L $(LFT_PATH) -lftprintf

LFT_PATH = .././

SRCS = *.c

all: $(NAME)

$(NAME):
	@make re -C .././
	@gcc $(SRCS)  -o $(NAME) $(LFT_FLAGS)

fclean:
	@rm -f $(NAME)

re: fclean all

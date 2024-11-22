all:
	vagrant up


reload:
	vagrant reload

clean:
	vagrant down

status:
	vagrant box list
	vagrant status

fclean:
	vagrant destroy
	@rm -rf .vagrant

delete:
	-vagrant box remove debian/bullseye64

re: fclean all

.Phony: all clean status delete reload fclean%
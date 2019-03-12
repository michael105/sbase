
.PHONY: README.md

README.md: 
	cp README.in README.md
	ls -lh | grep -oE '\s*(\S*\s*){6}$$' >> README.md
	echo '```'>> README.md


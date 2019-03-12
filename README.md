### suckless linux tools


This is my fork of github.com/nee-san/sbase

Working on a port to minilib,
in order to get tiny and statical linked binaries.


Seems quite useful, linked static with minilib on linux x64
"cat" now is 3K.

	same system, 
	linked dynamic with gcc: 15K (18K)
	linked static with gcc: 747K
	dynamic with musl: 17K
	static with musl: 26K (or even 32K)


Michael (misc) Myer, misc.myer@zoho.com, 2019


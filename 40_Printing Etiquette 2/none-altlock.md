-- 7 Billion Humans (2059) --
-- 40: Printing Etiquette 2 --

mem2 = nearest printer
a:
mem1 = calc mem1 + 1
if mem1 < 6:
	takefrom mem2
	b:
	if c == nothing:
		write mem1
		drop
	else:
		step nw,w,sw,n,s,ne,e,se
		jump b
	endif
else:
	end
endif
jump a




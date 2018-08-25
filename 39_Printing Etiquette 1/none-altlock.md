-- 7 Billion Humans (2059) --
-- 39: Printing Etiquette 1 --

mem2 = nearest printer
a:
if mem1 < 5:
	takefrom mem2
	b:
	if c == nothing:
		drop
	else:
		step nw,w,sw,n,s,ne,e,se
		jump b
	endif
else:
	end
endif
mem1 = calc mem1 + 1
jump a




-- 7 Billion Humans (2087) --
-- 6: Little Exterminator 1 --

a:
pickup c
if s == hole and
 w != hole:
	step w
else:
	b:
	if s == hole and
	 e != hole:
		step e
		jump b
	endif
	step s
endif
jump a



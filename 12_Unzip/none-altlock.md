-- 7 Billion Humans (2059) --
-- 12: Unzip --

pickup c
if w == wall:
	step n
	drop
endif
a:
if nw == datacube:
	step s
	drop
endif
if sw == datacube:
	step n
	drop
endif
jump a




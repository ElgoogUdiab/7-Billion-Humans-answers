-- 7 Billion Humans (2059) --
-- 41: Image Decrypter --

step w
pickup c
mem1 = set myitem
a:
if mem1 != 0:
	step w
	mem1 = calc mem1 - 1
	jump a
endif
drop
b:
step s
jump b




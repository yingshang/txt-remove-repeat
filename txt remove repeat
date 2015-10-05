#encoding:utf-8
obuff = []
repeat = 0
path = raw_input('please input your path:  ')
for ln in open(path):
    if ln in obuff:
    	repeat+=1
        continue
    obuff.append(ln)
print "repeat columns is %s"  %repeat
with open(path, 'w') as handle:
    handle.writelines(obuff)

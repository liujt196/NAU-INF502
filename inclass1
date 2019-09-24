import csv

afile = open('names', 'r')
bfile = open('city', 'r')
cfile = open('age', 'r')
dfile = open('phone', 'r')
efile = open('state', 'r')

a = list()
b = list()
c = list()
d = list()
e = list()

for line in afile:
    a.append(line)
for line in bfile:
    b.append(line)
for line in cfile:
    c.append(line)
for line in dfile:
    d.append(line)
for line in efile:
    e.append(line)

with open('inclass1.csv', 'w') as csvfile:
    fieldnames = ['names', 'city',  'age', 'phone', 'state']
    writer = csv.DictWriter(csvfile, fieldnames=fieldnames)

    writer.writeheader()
    writer.writerow({'names': a[0], 'city': b[0], 'age': c[0], 'phone': d[0], 'state': e[0]})
    writer.writerow({'names': a[1], 'city': b[1], 'age': c[1], 'phone': d[1], 'state': e[1]})
    writer.writerow({'names': a[2], 'city': b[2], 'age': c[2], 'phone': d[2], 'state': e[2]})
    writer.writerow({'names': a[3], 'city': b[3], 'age': c[3], 'phone': d[3], 'state': e[3]})
    writer.writerow({'names': a[4], 'city': b[4], 'age': c[4], 'phone': d[4], 'state': e[4]})
    writer.writerow({'names': a[5], 'city': b[5], 'age': c[5], 'phone': d[5], 'state': e[5]})
    writer.writerow({'names': a[6], 'city': b[6], 'age': c[6], 'phone': d[6], 'state': e[6]})
    writer.writerow({'names': a[7], 'city': b[7], 'age': c[7], 'phone': d[7], 'state': e[7]})
    writer.writerow({'names': a[8], 'city': b[8], 'age': c[8], 'phone': d[8], 'state': e[8]})
    writer.writerow({'names': a[9], 'city': b[9], 'age': c[9], 'phone': d[9], 'state': e[9]})
    writer.writerow({'names': a[10], 'city': b[10], 'age': c[10], 'phone': d[10], 'state': e[10]})
    writer.writerow({'names': a[11], 'city': b[11], 'age': c[11], 'phone': d[11], 'state': e[11]})


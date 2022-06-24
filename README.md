divis = []
for i in range (1,101):
  if i % 5 == 0:
    divis.append (i)
print (divis)
cubes = [divi ** 3 for divi in divis]
print (cubes)

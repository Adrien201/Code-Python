Total = 0
#n = 12729492194

for n in range(1, 1000):
  if n%3 == 0 or n%5 == 0:
    Total += n

print(Total)

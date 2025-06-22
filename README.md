l = [10, 20, 30, 40, 50]
n = len(l)
mid = n // 2

if n % 2 == 0:
    l = l[:mid-1] + l[mid+1:]
else:
    l = l[:mid] + l[mid+1:]

print(l)

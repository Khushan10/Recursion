total_elements = int(input())
lis = []
for x in range(total_elements):
	a = int(input())
	lis.append(a)
def recursive(lis):
	if (len(lis)==1):
		print(lis[0])
	else:
		lis.sort()
		remove1 = lis[0]
		remove2 = lis[1]
		lis.remove(remove1)
		lis.remove(remove2)
		add = (3*remove1 + 2*remove2)%100
		lis.append(add)
		recursive(lis)
recursive(lis)

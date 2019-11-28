# algorithm-_orderedlistornot


ages = [23, 45, 62, 27]

is_sorted = True
length = len(ages)

for i in range(1, length):
    if ages[i] <= ages[i-1]:
        is_sorted = False
        break

if is_sorted:
    print("the listed is sorted")
else:
    print("the list is not sorted")
    


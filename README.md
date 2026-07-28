# Follydee-
Learners are Leaders....
#BUBBLE SORT

def bubble_sort (lis):
    size = len(lis)

    for i in range (size):
        for j in range (size-i-1):
            if lis[j] < lis [j+1]:
                lis[j], lis[j+1] = lis[j+1],lis[j]
    return lis

list = [64,34,25,12,22,11,90]

print(bubble_sort(list))

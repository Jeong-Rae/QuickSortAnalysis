import random
import time


def quick_sort(array):
    if len(array) <= 1:
        return array
    pivot = array[len(array) // 2]
    left_array, equal_array, right_array = [], [], []
    for num in array:
        if num < pivot:
            left_array.append(num)
        elif num > pivot:
            right_array.append(num)
        else:
            equal_array.append(num)
    return quick_sort(left_array) + equal_array + quick_sort(right_array)



arr=[]

for j in range(5,21): #정렬배열로 인코딩
    for i in range(2**j):
        arr.append(i)

    #random.shuffle(arr) #랜덤배열시
    #arr.reverse() #역배열시
    start_time = time.time()

    quick_sort(arr)

    print(str(2**j), "개 인코딩시간: {:.4f}sec".format((time.time() - start_time)))
    arr.clear()

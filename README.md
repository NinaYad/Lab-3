# №1
# Сортировка пузырьком
A = input().split()
n = len(A)
for i in range (n - 1):
    for j in range(n - 2, i - 1, -1):
        if A[j+1]<A[j]:
            A[j], A[j+1] = A[j+1], A[j]
print (A)
# sort
A = input().split()
A.sort()
print(A)

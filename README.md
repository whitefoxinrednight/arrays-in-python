# arrays-in-python
#simple program in arrays to find largest number
import array as arr
a=arr.array('i',[10,2,31,6,19])
print(a)
largest=a[0]
for i in range(1,len(a)):
  if a[i]>largest:
    largest=a[i]
print("largest number:",largest)

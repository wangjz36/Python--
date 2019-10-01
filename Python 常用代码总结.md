
#1. sort() vs. sorted()
sort()与sorted()的不同在于，sort是在原位重新排列列表，而sorted()是产生一个新的列表： a.sort()与b=sorted(a)

#2. lambda
key=lambda x:x[1],数组排序时常用，调用第二个位置为排序依据。如b=sorted(enumerate(a), key=lambda x:x[1])，可以取出排序的位置。

#3. 取 unique value
list(set())

4. map函数+list函数，转字符串到数组
    inp='9 6 4 2 1 3 5 7 0 1 8'
    list(map(int,li))
    li=inp.split()

5.

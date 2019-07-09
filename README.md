# yin-shiu-fang
print("hello python")   # 『#』為單行註解

#變數不用宣告,直接使用
name="艾呆玩"
age=20
height=180.5
weight=80.5

#多個變數,同時指定相同的值
x=y=z=100

#多個變數,分別指定不同的值
empNo,empName,empSalary,empDept="001","Bill",23100.5,"MIS"

i,j,k=10,3,0

b=False #bool 型別

print("姓名：",name)
print("年齡：",age)
print("身高：",height)
print("體重：",weight)

print("x=",x)
print("y=",y)
print("z=",z)

print("empNo:",empNo)
print("empName:",empName)
print("empSalary:",empSalary)
print("empDept:",empDept)

del empDept
#print("empDept:",empDept)  #Error,因為empDept 已被刪除


#算術運算
k=i+j
print("%d + %d = %d"%(i,j,k))

k=i-j
print("%d - %d = %d"%(i,j,k))

k=i*j
print("%d x %d = %d"%(i,j,k))

k=i/j
print("%d / %d = %.2f"%(i,j,k))

k=i//j
print("%d // %d = %d"%(i,j,k))

print("%d的3次方為%d"%(k,k**3))

k=i%j
print("%d / %d的餘數為 %d"%(i,j,k))

#指定運算
k+=2
print("k=",k)

k**=3
print("k的3次方為",k)

#比較運算
print("%d > %d : %d"%(i,j,i>j)) #1,成立
print("%d < %d : %d"%(i,j,i<j)) #0,不成立

b=i>j
print("%d > %d : %d"%(i,j,b))

#邏輯運算
b=i>j and k<0 #不成立
print("b=",b)

b=i>j or k<0 #成立
print("b=",b)

print("b=",not b) #成立的相反

#查看變數的資料
print(type(name)) #str
print(type(empNo)) #str
print(type(empSalary)) #float
print(type(k)) #int
print(type(b)) #bool



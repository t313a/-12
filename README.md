name = input("what is your name !: ")
age = input("what your age dear ❤️: ")
num1 = input("number 1, pleas 🧐 : ")
num2 = input("number 2, pleas 🧐 : ")

# تحويل أنواع البيانات
name1 = str(name)
age1 = int(age)
num11 = float(num1)
num22 = float(num2)

# طباعة أنواع المتغيرات للتأكد
print(type(name1))
print(type(age1))
print(type(num11))
print(type(num22))

# المعادلة
result = num11 + num22 * 2 - (age1 / 2)

# الطباعة والتكرار
print("Your name :", name1)
for i in range(age1):
    print(name1)

print("ناتج المعادلة : ", result)

# فكرة القسمة والشرط
if num22 != 0: # للتأكد من عدم القسمة على صفر
    n = num11 / num22
    if n >= 50:
        print(" ناتج او نتيجة اكبر ")
    else:
        print(" راسب او نتيجة اصغر ")
else:
    print("لا يمكن القسمة على صفر")


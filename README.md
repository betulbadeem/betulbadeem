#Bir kullanıcıdan bir sayı girişi alın ve 
#1'den başlayarak bu sayıya kadar olan tüm tam sayıları
#ekrana yazdıran bir Python programı yazın.

number=int(input("enter number:"))

for number in range(1, number+1):
    print(number)

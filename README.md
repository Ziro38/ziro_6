# ziro_6
سله المشتريات#
print("اهلا بك في سله المشتريات:")
wpe=[]
wpe1=[]
bop=int(input("كم عدد العناصر:"))
if bop>0:
    for v in range(0,bop):
        lax=input("ادخل العناصر:\n")
        wpe.append(lax)
        don=float(input("ادخل سعر المنتج::\n"))
        wpe1.append(don)
    xx=input("هل تريد رايه جميع العناصر")
    if xx=="yes" or xx=="نعم":
        print(wpe)
        dd=input("هل تريد رايه اجمالي السعر")
        if dd=="yes" or dd=="نعم":
            print(wpe1)
            
        else:
            print("تخطا با انتر")
    else:
        print("تخطا با انتر")
   
else:
    print("انت لا تريد الشراء")
Sku = int(input ("Enter SKU : "))
Product = input ("Enter Product Name : ")
Qt = int(input ("Enter Product QT : "))
One_price = int(input (f"Enter single {Product} price : ") )
Dict = {}
Dict[Sku]=({"Product":Product, "Qt":Qt ,"One_price":One_price })

Addmore = input ("\nDo you want to add more employee data ? [Y/N] : ")

while True:
  if Addmore == "Y" or Addmore == "y":
    Sku = int(input ("\nEnter SKU : "))
    Product = input ("Enter Product Name : ")
    Qt = int(input ("Enter Product QT : "))
    One_price = int(input (f"Enter single {Product} price : ") )
    # Dict[Sku]=({"Product Name : ":Product, "QT : ":Qt ,"single price : ":One_price })
    Addmore = input ("\nDo you want to add more employee data ? [Y/N] : ")
  else:
    print("\n-----------Output section-----------")
    input("\nEnter product item from SKU No. : ")
    for i in Dict:
      print(f"Total cost :  {Dict[i]['Qt']*Dict[i]['One_price']}")
      print(f"Product Name : {Dict[i]['Product']}")
      print(f"QT : {Dict[i]['Qt']}")
      print(f"single price : {Dict[i]['One_price']}")
      break
    break

# python
Dars
# rule True agar 0 dan boshqa har qanday holatda
bool(1.5)
# comparision --- >,>=<,<=,==,!=
4 > 5
a = 3
a == 3
True
a = 2
a == 3
False
a = 5
a != 3
True
if 2 < 5:
    print('Success')
    if 2 == 2:
    print('Success')
    age = int(input("yoshingni kirit"))
if age>=18:
    print("san pravo olishing mumkin")
else:
    print('yoshing yetarli emas')
    city = input("qayerda yashaysan?  ")
if city == 'Tashkent':
    print('Seni ishga olamiz')
else:
    print('uzur, propiska kerak ukam')
    city = input("qayerda yashaysan?  ")
if city == 'Tashkent':
    print('Seni ishga olamiz')
else:
    print('uzur, propiska kerak ukam')
    ilts = int(input("ilts balingni kirit"))
if ilts>=7:
    print ('senga pul beramiz')
else:
    print('uzur kechirasan baling kam ekan')
    ilts = int(input("ilts balingni kirit"))
if ilts>=7:
    print ('senga pul beramiz')
else:
    print('uzur kechirasan baling kam ekan')
    products = ['Laptop','Monitor','mouse']
product_sold = input("Nima sotib olding")
if product_sold in products:
        print('senga skidka bor ukam')
else:
        print('Ukam damini ol puling yetmadi')
        products = ['Laptop','Monitor','mouse']
product_sold = input("Nima sotib olding")
if product_sold not in products:
        print('senga skidka bor ukam')
else:
        print('Ukam damini ol puling yetmadi')
        # IFUTS = ['5','39']
IFUT_sold = int(input("kerakli faoliyat turi kodini kiriting"))
if IFUT_sold >=5 and IFUT_sold <=39:
    print('Sanoat tarmogiga tegishli')
else:
    print('Boshqa tarmoqga tegishli kod')
    age = int(input("Yoshingni kirit"))

if age>=18:
    yes_pravo = input("Haydochilik guvohnomang bormi: Ha or Yoq")
    if yes_pravo == 'Ha':
        print('Oq yul')
    else:
        print('Siz haydovchilik guvohnomasini olishingiz kerak')
else:
    print('Uzur,sizga mashina bera olmaymiz')

print("Siz dasturda karra jadavalini bilishingini tekshirishingiz mumkin")
table=int(input("istalgan karra(raqamini) kirting:"))
for i in range(1,10):
    print(table,'x',i,'= ?')
    pup=input()
    if pup=='Bilmayman':
        break
    if pup=='Keyingisi:':
        print('keyingi savol:')
        continue
    res=table*i
    if int(pup)==res:
        print('Barakalla!')
    else:
        print("Nato\'gri,   javob:",res)
print('Tugadi')
    

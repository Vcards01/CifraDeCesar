print("\n\t--------------------------------------------------------------\n\tSISTEMA DE CRIPTOGRAFIA DE MENSGENS COM O ALGORITIMO DE CESAR\n\t--------------------------------------------------------------\n")
crip=[]
descrip=[]
cod=int
menu=-1
v=int(input("Qual valor de codificação deseja utilizar?\nR:"))
d=str(input("Deseja criptografar para a Direita(D) ou para Esquerda(E)?\nR:")).upper()
while(menu!=0):
    crip.clear()
    descrip.clear()
    print("\n\n---O que deseja fazer---")
    print("\n[1]Criptografar")
    print("\n[2]Desriptografar")
    print("\n[3]Alterar configurações")
    print("\n[0]Sair\n")
    menu=int(input("R:"))
    if(menu==1):
        msg=str(input("\nDigite a mensagem a ser criptografada:\n"))
        if(d=="D"):
            for i in range(0,len(msg)):
               cod=ord(msg[i])
               cod+=v
               crip.append(chr(cod))
            print("\nA mensagem criptografada é :")
            for x in crip:
               print(x,end="")
            option=str(input("\n\nDeseja descriptografar a mensagem novamente?[S|N]\n")).upper()
            if(option=="S"):
               for i in crip:
                   cod=ord(i)
                   cod-=v
                   descrip.append(chr(cod))
               print("\nA mensagem Descriptografada é :")
               for x in descrip:
                   print(x,end="")
        elif(d=="E"):
           for i in range(0,len(msg)):
               cod=ord(msg[i])
               cod-=v
               crip.append(chr(cod))
           print("\nA mensagem criptografada é :")
           for x in crip:
               print(x,end="")
           option=str(input("\n\nDeseja descriptografar a mensagem novamente?[S|N]\n")).upper()
           if(option=="S"):
               for i in crip:
                   cod=ord(i)
                   cod+=v
                   descrip.append(chr(cod))
               print("\nA mensagem Descriptografada é :")
               for x in descrip:
                   print(x,end="")
    elif(menu==2):
        msg=str(input("\nDigite a mensagem a ser Descriptografada:\n"))
        if(d=="D"):
             for i in range(0,len(msg)):
                cod=ord(msg[i])
                cod-=v
                descrip.append(chr(cod))
             print("\nA mensagem Descriptografada é :")
             for x in descrip:
                print(x,end="")
             option=str(input("\n\nDeseja Criptografar a mensagem novamente?[S|N]")).upper()
             if(option=="S"):
               for i in descrip:
                   cod=ord(i)
                   cod+=v
                   crip.append(chr(cod))
               print("\nA mensagem criptografada é :")
               for x in crip:
                   print(x,end="")
        elif(d=="E"):
            for i in range(0,len(msg)):
                cod=ord(msg[i])
                cod+=v
                descrip.append(chr(cod))
            print("\nA mensagem Descriptografada é :")
            for x in descrip:
                print(x,end="")
            option=str(input("\n\nDeseja Criptografar a mensagem novamente?[S|N]")).upper()
            if(option=="S"):
               for i in descrip:
                   cod=ord(i)
                   cod-=v
                   crip.append(chr(cod))
            print("\nA mensagem criptografada é :")
            for x in crip:
               print(x,end="")
    elif(menu==3):
        v=int(input("Qual valor de codificação deseja utilizar?\nR:"))
        d=str(input("Deseja criptografar para a Direita(D) ou para Esquerda(E)?\nR:")).upper()
    
exit()



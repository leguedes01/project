🎁 _Isto que vocês estão observando são um sistema básico que desenvolvi.
Ele é um sistema de cardápio, parecido como aquele do famoso "MacDonald`s."
É claro que falta alguns ajustes, posso dizer abertamente sobre isso,más, venho 
cada dia aprendendo e testando coisas novas. Isso faz com que estimulle meu conhe-
cimento. Espero que vocês testem e espero feedback de vocês. OBRIGADO !!!😁😜_
  
def atendimento():
     print("O que você deseja, comer ou beber?")
     escolha01 = int(input("Digte 1 para comer, Digite 2 para beber ->"))
     if escolha01 == 1:
          escolha_prato()
     else:
        escolha_drinks()





def escolha_drinks():
  escolha_drink =int(input("Digite 1 para Refri, Digite 2 para Suco"))
  if escolha_drink == 1:
      print("Opa você escolheu Refri")
  else:
      print("Você escolheu suco")




def escolha_prato():
  escolha = input("Escolha uma opção: a -salada, b - churrasco, c - Pizza ->")
  if escolha =='a':
     print("Sua salada está a caminho")
  elif escolha == 'b':
     print('Poxa, sensacional, já foi pedido seu Churrasco')
  elif escolha  == 'c':
      print('Show, sua Pizza já esta no forno *.*')
  else:
    print("Não temos essa")



atendimento()


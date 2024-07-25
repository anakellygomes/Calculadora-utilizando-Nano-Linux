op= ''
while op != 's' :
 op = input('''Qual a opção desejada? Escolha dentre as seguintes opções:
    '+' para soma      '/' para divisão
    '-' para subtração '*' para multiplicação
    's' para sair/encerrar o programa

     Operação = ''')

  try:
   n1= int(input('1 número: '))
   n2= int(input('2 número: '))


  except:
    print('Entrar com números inteiros!')

  else:
   if op == '+' :
    print(f'{n1} + {n2} = {n1 + n2}')

 elif op == '-' :
   print (f' {n1} - {n2} = {n1 - n2} ')

 elif op == '*' :
  print (f' {n1} * {n2} = {n1 * n2} ')

 else :
  try:
    print(f' {n1} / {n2} =  {n1 / n2} ')

  except :
   print( 'divisão por zero não permitido!')
    print('..................\n')

   print(' Programa finalizado!')


# validacao

def faixa_int(pergunta, minimo, maximo):
  while True:
    v = int(input(pergunta))
    if v < minimo or v > maximo:
      print(f"Valor invalido, digite um valor entre {minimo} e {maximo}")
    else:
      return v

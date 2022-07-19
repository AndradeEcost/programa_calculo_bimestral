# programas-b-sico_c-lculo_media_bimestral
Programa básico para leitura de notas bimestrais 
print('''  
 ESCOLA HORIZONTE 

''')
print('')
print('Leitura de notas')

nome=input('Digite qual o ano do aluno: ')
turma=input('Digite a turma do aluno: ')
turno= input('Digite  o turno do aluno: ')
print ('Nome: ',nome)
print ('Turma: ',turma)
print ('Turno: ',turno)

t1=float(input('Digite a nota do 1° bimestre: '))
t2=float(input('Digite a nota do 2° bimestre: '))
t3=float(input('Digite a nota do 3° bimestre: '))
t4=float(input('Digite a nota do 4° bimestre: '))
d=(t1+t2+t3+t4)/4
print('Media = {}'.format(d))

if d>= 7.0:
 print(nome, 'foi aprovado')
else:
  print(nome,'foi reprovado')

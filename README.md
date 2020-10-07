# Remote-Classes-Automation
## Automatically opens the Google Meet/Zoom/Jitsi or any other conference room at the time of the class

## PT-BR

OBS: A sala de reunião será aberta no seu browser padrão no Windows

# Requerimentos do sistema:
°Windows 10 ( em versoões anteriores do Windows, ao invés de .bat, é .cmd)
°Python instalado

## Passo 1:
Adaptar o código de "Link_constante.py", isto é, colocar o link da sua aula entre o ' '

## Passo 2:
Salvar esse código no seu computador como .py

## Passo 3: Transformando .py em batch file
Criar um arquivo de texto e colar o seguinte código

"Caminho do arquivo .py no seu computador"
pause

Por exemplo, o meu ficou assim:
"C:\Users\erica\Documents\PLE_Automation\Modelagem.py"
pause

## Passo 4:
Salvar esse arquivo com a terminação .bat

## Passo 5:
Abrir o Agendador de Tarefas do Windows ( já vem pré instalado) 
e clicar em "Criar tarefa básica"( lado superior direito da tela)

## Passo 6: 
A partir daí é bem intuitivo (até a parte da ação) , 
é só digitar o nome da ação ( você escolhe)
escolher a frequência e horário que a ação vai acontecer

## Passo 7:
Na ação, escolher "abrir programa",
Depois irá aparecer uma caixa escrito "Procurar",
ao clicar, você deve selecionar o seu arquivo criado no Passo 4 ( arquivo com terminação .bat)

Depois é só clicar em "Concluir"
Pronto, você acabou de agendar uma tarefa no Windows

Você pode fazer isso para cada matéria, 

qualquer dúvida, pode me contatar em: erica.ferreira@poli.ufrj.br






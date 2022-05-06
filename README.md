# Projeto-Automacao-Python-Email
Projeto de automação de envio de e-mail (Outlook) com Python.

Digamos que no trabalha sou responsável pela área de inteligência de negócio.

Todos os dias,  a equipe ou até mesmo um programa, gera um report diferente para cada área da empresa:

Financeiro<br>
Logística<br>
Manutenção<br>
Marketing<br>
Operações<br>
Produção<br>
Vendas<br>

Cada um desses reports deve ser enviado por e-mail para o Gerente de cada Área.

Criamos um programa que faça isso automaticamente. A relação de Gerentes (com seus respectivos e-mails) e áreas está no arquivo 'Enviar E-mails.xlsx'.

É necessário modificar os email na planilha 'Enviar E-mails.xlsx' para emails válidos.

Utilizaremos o pandas para interagir com as planilhas excel, caso em outras situções estas bases de dados estejam em outras extenções, segue o link com a ducumentação do pandas:
[Documentação 'pandas'](https://pandas.pydata.org/docs/index.html)

Utilizaremos o modulo 'win32com.client' para realizar a integração com o outlook
[Documentação 'win32com.client'](https://pbpython.com/windows-com.html)


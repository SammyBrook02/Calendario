📅 Calendário em Python

Um script simples em Python que exibe o calendário de um mês específico, a partir do ano e do mês informados pelo usuário.

📋 Descrição

Este projeto utiliza o módulo calendar da biblioteca padrão do Python para gerar e imprimir no terminal o calendário de um mês escolhido pelo usuário.

🚀 Como executar
Certifique-se de ter o Python instalado (versão 3.x).
Salve o código em um arquivo, por exemplo calendario.py.
Execute o script pelo terminal:
bash
python calendario.py
Informe o ano e o mês quando solicitado.
💻 Código
python
import calendar

ano = int(input("Digite o ano: "))
mes = int(input("Digite o mês: "))

print("\n", calendar.month(ano, mes))
📖 Exemplo de uso
Digite o ano: 2026
Digite o mês: 9

     September 2026
Mo Tu We Th Fr Sa Su
    1  2  3  4  5  6
 7  8  9 10 11 12 13
14 15 16 17 18 19 20
21 22 23 24 25 26 27
28 29 30
🛠️ Tecnologias utilizadas
Python 3
Módulo calendar (biblioteca padrão)
⚠️ Observações
O mês deve ser informado como um número inteiro entre 1 e 12.
Caso um valor inválido seja informado, o programa retornará um erro (IllegalMonthError).
O calendário é exibido no idioma padrão do sistema (geralmente inglês), a menos que o locale seja configurado manualmente com calendar.setfirstweekday() ou locale.setlocale().

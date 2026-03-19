# Consumo-de-energia
# :zap: CALCULADOR DE CONSUMO DE ENERGIA
## :pushoin: Descrição
esse projeto calcula o consumo de energia
do aparelho que você escolher
## :rocket: Como executar
Execute o projeto com:
python app.py
## :hammer_and_wrench: Tecnologias
- python
## :man_technologist: Autor
Gabriel cruz
# :fire: Código
'''python
# Programa para calcular consumo mensal de energia
aparelho= input("Digite o nome do aparelho: ")
horas= float(input("Quantas horas médias você usa esse aparelho? "))
potencia= float(input("Qual a potência do aparelho (w)? "))
consumo= (potencia * horas * 30) / 1000
custo= (consumo * 0.75)
print(f"Aparelho: {aparelho}")
print(f"Consumo estimado: {consumo:.2f} kWh/mês ")
print(f"Custo estimado do {aparelho} será de R$ {custo:.2f} ")

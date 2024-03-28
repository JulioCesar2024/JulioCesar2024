- 👋 Hi, I’m @JulioCesar2024
- 👀 I’m interested in work in the area of programing or information security.
- 🌱 I’m currently learning of Python, fundamentals of Big Data and Data Anlystics whith Python
- 💞️ I’m looking to collaborate on leanr and help.
- 📫 How to reach me, mizaelj27@yahoo.com
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
JulioCesar2024/JulioCesar2024 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->
# Claculo de juros simples, entre valor, meses e juros.
# Pedir para digitar valor, juros e meses.

print ("Valor do emprestimo")
emprestimo = float(input())
 
# juros a ser pago
print ("Juros")
juros = float(input() )

print ("Quantidade de meses")
meses = int(input())

calculo = meses * (juros * emprestimo ) /100
resultado = emprestimo / meses + calculo + emprestimo
parcelas = resultado / meses
#resultado= calculo / meses + emprestimo

print(f"O valor total a ser pago em meses é: {resultado}")
print (f"O valor da parcela é: {parcelas}")



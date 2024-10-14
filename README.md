# Desafio-dio-Calculo-Potencia-Ruby
Cálculo com Potência em Ruby

Programa em Ruby para Cálculo de Potência
Vamos criar um programa em Ruby que permite ao usuário calcular a potência de um número. O usuário poderá informar a base e o expoente, e o programa calculará a potência.

Código do Programa
Aqui está um exemplo de como você pode escrever esse programa:

# Função para calcular a potência
def calcular_potencia(base, expoente)
  base ** expoente
end

# Solicita ao usuário a base
print "Digite a base: "
base = gets.chomp.to_f

# Solicita ao usuário o expoente
print "Digite o expoente: "
expoente = gets.chomp.to_f

# Realiza o cálculo da potência
resultado = calcular_potencia(base, expoente)

# Exibe o resultado
puts "#{base} elevado a #{expoente} é igual a #{resultado}."
Explicação do Código
Função calcular_potencia: Recebe a base e o expoente e calcula a potência usando o operador **.
gets.chomp: Lê a entrada do usuário e remove a quebra de linha.
to_f: Converte a entrada para um número em ponto flutuante.
Como Executar o Programa
Crie um arquivo Ruby chamado potencia.rb:

touch potencia.rb
Abra o arquivo em um editor de texto e cole o código acima.

Execute o programa no terminal:

ruby potencia.rb
Siga as instruções na tela para inserir a base e o expoente.

Exemplo de Saída
Se você inserir 2 como base e 3 como expoente, a saída será:

2.0 elevado a 3.0 é igual a 8.0.

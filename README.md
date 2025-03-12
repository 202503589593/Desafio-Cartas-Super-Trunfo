Super Trunfo em C
Este projeto é uma implementação em C do jogo Super Trunfo, onde o usuário pode comparar atributos de duas cartas de países. O programa permite a escolha de dois atributos para comparação, calcula a soma dos valores desses atributos e determina o vencedor da rodada. Além disso, o código é robusto, com menus dinâmicos e tratamento de entradas inválidas.

Funcionalidades
Cadastro de Cartas: O usuário insere os dados de duas cartas, incluindo população, área, PIB, número de pontos turísticos, etc.

Cálculo de Atributos Derivados: O programa calcula a densidade populacional e o PIB per capita para cada carta.

Super Poder: Calcula o "Super Poder" de cada carta, somando todos os atributos numéricos.

Comparação de Cartas: O usuário escolhe dois atributos para comparar as cartas. O programa compara os atributos e exibe o resultado.

Tratamento de Empates: Se a soma dos atributos for igual, o programa informa que houve um empate.

Menus Dinâmicos: Menus interativos permitem ao usuário escolher atributos de forma dinâmica, sem repetições.

Requisitos
Para compilar e executar o programa, você precisará de:

Um compilador C (como GCC ou Clang).

Um terminal ou prompt de comando.

Como Compilar e Executar
Clone o repositório para o seu ambiente local:

bash
Copy
git clone https://github.com/seu-usuario/super-trunfo-c.git
Navegue até o diretório do projeto:

bash
Copy
cd super-trunfo-c
Compile o programa usando o GCC:

bash
Copy
gcc -o super_trunfo Comparacao_Cartas_Final.c
Execute o programa:

bash
Copy
./super_trunfo
Estrutura do Código
O código está organizado da seguinte forma:

Entrada de Dados: O usuário insere os dados das duas cartas.

Cálculos: O programa calcula a densidade populacional, o PIB per capita e o Super Poder.

Menus Dinâmicos: O usuário escolhe dois atributos para comparação.

Comparação e Resultados: O programa compara os atributos e exibe o resultado da rodada.

Exemplo de Uso
Insira os dados das duas cartas quando solicitado.

Escolha dois atributos para comparação a partir do menu interativo.

O programa exibirá os valores dos atributos, a soma dos atributos e o resultado da comparação.

Exemplo de Saída
Copy
Comparação de Cartas:

País 1: Brasil
País 2: Argentina

Atributos Escolhidos:
- População
- PIB per Capita

Valores:
- População (Brasil): 213.000.000
- População (Argentina): 45.000.000
- PIB per Capita (Brasil): 8.500
- PIB per Capita (Argentina): 12.000

Soma dos Atributos:
- Brasil: 213008500
- Argentina: 45012000

Resultado: Brasil venceu!

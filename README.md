# Solucionador Método Simplex
- M210 - Disciplina de Otimização I
- Repositório para registro do projeto desenvolvido na disciplina.
- Instituto Nacional de Telecomunicações - Inatel.
- Curso: Engenharia de Software.
- Elaborado por: Iza Lopes.
 
## Descrição
 
Este projeto é um solucionador do Método Simplex para problemas de Programação Linear (PL). A aplicação permite resolver problemas de otimização linear, maximizando ou minimizando uma função objetivo sujeita a um conjunto de restrições lineares.
 
## Funcionalidades
 
- **Entrada de Dados**: Interface para entrada dos coeficientes da função objetivo, coeficientes das restrições e  e seleção da opções "maximize" e "minimize".
- **Resolução do Problema**: Implementação do método Simplex para encontrar o ponto ótimo para o PPL.
- **Exibição do Resultado**: Mostra o valor ótimo, a solução ótima e os preços-sombra de cada restrição com duas casas decimais.
- **Interface Gráfica**: Utilização do Tkinter para criar uma interface gráfica amigável para entrada e visualização dos dados.
 
## Tecnologias Utilizadas
 
- **Python**: Linguagem de programação principal utilizada no projeto.
- **Tkinter**: Biblioteca padrão do Python para a criação de interfaces gráficas.
- **Scipy**: Utilizada para cálculos científicos e de otimização.
- **Numpy**: Utilizada para manipulação de arrays e operações matemáticas.
 
## Instalação
 
1. Clone o repositório:
    ```bash
    git clone https://github.com/Izalp/solucionador-metodo-simplex.git
    ```
 
2. Instale as dependências:
    ```bash
    pip install scipy
    pip install tkinter
    pip install numpy
    ```
 
## Execução do projeto
 
1. Execute o script principal para iniciar a interface gráfica:
    ```bash
    python Simplex/projectSimplex.ipynb
    ```
 
2. Insira os coeficientes da função objetivo das as restrições.
 
3. Escolha entre as opções de maximização e minimização para a solução do PPL.
 
3. Clique no botão "Resolver" para encontrar o resultado.
 
4. O valor ótimo, a solução ótima e os preços-sombra de cada restrição serão exibidos na interface.
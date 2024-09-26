# Introdução ao Jupyter Notebook

O **Jupyter Notebook** é uma ferramenta super prática e poderosa para quem trabalha com programação e análise de dados, principalmente em Python. Ele também suporta outras linguagens, como Julia e R. No passado, ele era conhecido como *IPython Notebook*, mas o nome mudou para refletir o suporte a várias linguagens.

<br>

## Modos do Jupyter

O Jupyter possui dois modos principais:

- **Modo Comando**: quando tem uma borda azul ao redor da célula. Aqui podemos usar comandos para controlar o notebook
- **Modo Edição**: quando a célula tem uma borda verde. Nesse modo podemos alterar o conteúdo da célula

<br>

### Principais atalhos no Modo Comando

- ```a```: insere uma nova célula acima da atual
- ```b```: insere uma nova célula abaixo da atual
- ```Ctrl + Enter```: Executa a célula atual
- ```dd```: deleta a célula atual
- ```ii```: interrompe o kernel (útil quando o código trava ou entra em em loop)
- ```00```: reinicia o kernel (**cuidado**, pois isso apaga todas as variáveis e o histórico de execução)
- ```h```: acessar todos os atalhos disponíveis. Abre uma janela com os atalhos de teclado<br><br>

### Principais atalhos no Modo Edição

Enquanto estiver editando uma célula, alguns atalhos também podem ser super úteis:
- ```Shift + Tab```: Mostra a documentação sobre uma função ou método. Tecle quatro vezes para que a janela permaneça fixa na tela
- ```Ctrl + Enter```: Executa a célula e permanece no modo de edição
- ```Esc```: Sai do modo de edição e retorna para o modo comando<br><br>

### Dicas Avançadas
- ```?```: coloque um ponto de interrogação após uma função para ver sua documentação (exemplo: ```print?```)
- ```??```: coloque dois pontos de interrogação após uma função para ver seu código-fonte (exemplo: ```print??```)<br><br>

### Magias do Jupyter

Além de código Python, o Jupyter tem alguns "truques", que são comandos especiais precedidos por ```%``` ou ```%%```. Alguns exemplos úteis são:
- ```%matplotlib inline```: faz com que os gráficos gerados pelo ```matplotlib``` sejam exibidos diretamente no notebook
- ```%timeit```: mede quanto tempo um trecho de código leva para ser de executado
- ```%lsmagic```: para ver todas as magias disponíveis com o comando %lsmagic. E se quiser detalhes de alguma, basta usar o ```?``` depois do noime (exemplo: ```%timeit?```)

<br>

## Quando Usar o Jupyter

O Jupyter é excelente para experimentação e exploração de dados, visualização de gráficos e teste de algoritmos. Se você está tentando entender um algoritmo ou experimentar algo novo, ele é a ferramenta ideal. Mas, se o seu objetivo é desenvolver aplicações em produção ou um código mais robusto, com várias classes e testes, talvez seja melhor usar um editor como **VS Code** ou **Py Charm**.

Se você deseja uma experiência mais completa, o **Jupyter Lab** pode ser uma boa opção, pois ele conta com um ambiente mais parecido com o de uma IDE, integrando as funcionalidades do Jupyter com recursos de desenvolvimento.

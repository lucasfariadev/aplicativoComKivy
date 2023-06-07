# Projeto de Cotação de Moedas
Este projeto foi desenvolvido como parte da disciplina de Algoritmos e Lógica de Programação da Faculdade de Tecnologia (Fatec). Ele consiste em um aplicativo criado com o framework Kivy que exibe a cotação atual de algumas moedas, como Dólar, Euro, Bitcoin e Ethereum. O objetivo do projeto é aplicar os conceitos de programação aprendidos durante a disciplina.

# Funcionalidades
O aplicativo possui as seguintes funcionalidades:

Exibição da cotação do Dólar em reais (R$).
Exibição da cotação do Euro em reais (R$).
Exibição da cotação do Bitcoin em reais (R$).
Exibição da cotação do Ethereum em reais (R$).

# Pré-requisitos
Antes de executar o aplicativo, é necessário ter os seguintes requisitos instalados:

- Python 3
- Biblioteca Kivy
- Biblioteca requests
Você pode instalar as dependências necessárias executando o seguinte comando:

```
pip install kivy requests
```
Como executar o aplicativo
Para executar o aplicativo, siga as etapas abaixo:

Faça o download ou clone este repositório em seu computador.
Abra o terminal e navegue até o diretório onde o projeto está localizado.
Execute o seguinte comando:
```
python main.py
```
Isso iniciará o aplicativo e você verá a interface gráfica exibindo as cotações das moedas.

# Como funciona
O aplicativo é composto por dois arquivos principais:

main.py: Este arquivo contém a classe MeuAplicativo, que é responsável por construir a interface gráfica e obter as cotações das moedas. Ele utiliza a biblioteca requests para fazer requisições à API AwesomeAPI e exibe as cotações nas Labels correspondentes na interface.

tela.kv: Este arquivo contém a descrição da interface gráfica em formato de linguagem de marcação do Kivy. Ele define um GridLayout com uma coluna e quatro Labels, cada uma representando uma moeda e sua respectiva cotação.

# Contribuição
Sinta-se à vontade para contribuir com melhorias para este projeto. Você pode abrir issues para relatar problemas ou enviar pull requests com suas alterações.

Se encontrar algum problema ou tiver alguma sugestão, por favor, abra uma issue no repositório.

# Licença
Este projeto está licenciado sob a MIT License. Sinta-se à vontade para utilizar e modificar o código de acordo com os termos da licença.

# Meu projeto está no Github uhull!

Essa é a documentação do meu projeto: 
[Meu projeto](https://mslbr-vgabriel.github.io/workshop01-jdd/)

# 1. Mkdocs

Ferramenta para documentação, permite o usuário, seja ele desenvolvedor ou pessoa de negócio documentar as etapas e processos do projeto, tão bem como documentar funções e suas funcionalidades. O Mkdocs permite paginamento, ou seja, criar páginas para cada seção do seu projeto, por exemplo, criar uma página dedicada a uma etapada do fluxo de trabalho/processo.

## 1.1. Instalação do mkdocs 
    poetry add mkdocs

## 1.2. Criação do projeto
    mkdocs new .


## 1.3. Plug-ins mkdocs
    poetry add mkdocstrings-python pygments mkdocs-material pymdown-extesions

### Adicionando funções na documentação

Para inserir as funções utilizadas no projeto em sua documentação basta utilizar o comando exemplo abaixo

Exemplo:
    
    " ### ::: app.pipeline.extract.extract_from_excel "

Obs: lembrar de substituir o caminho para o arquivo .py e nome da função de acordo com o seu projeto

## 1.4. Mermaid

Ferramenta de diagramação e gráficos. Excelente ferramenta para a criação de fluxo de processos/trabalho

JavaScript que renderiza definições de texto inspiradas em Markdown para criar e modificar diagramas dinamicamente.
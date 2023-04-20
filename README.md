# Create React Component Extension for Visual Studio Code

Esta extensão para Visual Studio Code simplifica a criação de componentes React e React Native estruturados, permitindo gerar componentes com arquivos separados para o componente principal, estilos e um arquivo de exportação.

## Funcionalidades

- Cria componentes React e React Native em uma estrutura organizada
- Suporta arquivos TypeScript (`.tsx`) e JavaScript (`.js` e `.jsx`)
- Gera automaticamente arquivos separados para o componente principal, estilos e exportação

## Como usar

1. Instale a extensão no Visual Studio Code.
2. Abra a paleta de comandos (`Ctrl+Shift+P` ou `Cmd+Shift+P` no macOS) e digite "Create React Component".
3. Selecione o comando "Create React Component" na lista de comandos.
4. Digite o nome do componente que deseja criar e pressione Enter.
5. Selecione o tipo de componente (React ou React Native) na lista suspensa.
6. Escolha o tipo de arquivo que deseja usar para os arquivos do componente (`.tsx`, `.js` ou `.jsx`).
7. Selecione a pasta onde o novo componente será criado.

A extensão criará uma pasta para o novo componente com os seguintes arquivos:

- `ComponentName.extensao`: arquivo principal do componente
- `componentname.styled.extensao`: arquivo de estilos do componente
- `index.extensao`: arquivo de exportação do componente

## Contribuindo

Caso você encontre algum problema ou queira sugerir melhorias, sinta-se à vontade para abrir um Issue no repositório do projeto no GitHub.

## Licença

Esta extensão é licenciada sob a Licença MIT.

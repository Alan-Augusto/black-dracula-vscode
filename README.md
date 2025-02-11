## Como instalar:

1. Clonar o repositório:

https://github.com/Alan-Augusto/black-dracula-vscode.git

1. Abrir no terminal
2. Rodar o comando:

    ```jsx
    code --install-extension .\black-dracula-vscode-2.25.1.vsix
    ```


## Como editar:

Basta alterar o arquivo `./src/dracula.ymml`

## Como compilar:

1. Caso não tenha o `vsce` instalado, rodar o comando:

    ```jsx
    npm install -g vsce

    ```

2. Rodar o comando:

    ```jsx
    vsce package

    ```

3. E instale no vscode rodando

    ```jsx
    code --install-extension .\black-dracula-vscode-2.25.1.vsix
    ```
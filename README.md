# Code Cleanup Profile (Visual Studio 2022)

O **"Code Cleanup Profile"** no Visual Studio 2022 é uma ferramenta que permite automatizar a limpeza e aprimoramento do código-fonte por meio de uma série de correções automáticas conhecidas como "fixers". Cada fixer corresponde a uma regra ou conjunto de regras que abordam problemas específicos no código.

## Como faço para acessar essa funcionalidade?

<details>

<summary>Identificação da ferramenta</summary>

### **Passo 1**: Clique com o botão direito sobre o projeto ou solução que deseja realizar a limpeza e identifique a opção mostrada na imagem abaixo.
  
![image](https://github.com/CaioDSPeixoto/CodeCleanupProfile/assets/72414478/b302fab5-48e4-4cdb-ba54-0aa06693b1e7)

</details>

<details>

<summary>Opções disponíveis</summary>

### **Passo 2**: Vamos navegar pelas opções que irão abrir após clicar na imagem anterior.
  
![image](https://github.com/CaioDSPeixoto/CodeCleanupProfile/assets/72414478/4ec69115-3e02-4760-9595-18728e6cfb16)

- Por padrão, a ferramenta vem com dois perfis de limpeza do código, sendo eles totalmente configuráveis.
  
> [!NOTE]
> Caso já tenha configurado e queira executar, basta selecionar a opção "Run Code Cleanup (Profile)" com o _perfil desejado_.

</details>

<details>

<summary>Tela de configuração</summary>

### **Passo 3**: Ainda na tela anterior, vamos selecionar a opção Configure Code Cleanup iniciada por um ícone de engrenagem. Nela, vamos visualizar a tela de configuração de perfil e suas respectivas "fixers".
 ![image](https://github.com/CaioDSPeixoto/CodeCleanupProfile/assets/72414478/efb72a10-1726-4f1f-a2c6-e35dabed7b5a)

| Cor  | Descricao     |
|-----:|---------------|
|:red_square:  |Perfis de limpeza|
|:green_square:|Regras já inclusas no perfil|
|:blue_square: |Controle de adicionar ou remover regras aplicadas|
|:brown_square:|Regras disponíveis para serem incluídas|


</details>

<details>

<summary>Controle das regras</summary>

### **Passo 4**: Para adicionar ou remover uma fixer é bem simples, vamos seguir essa breve explicação.

:arrow_up: Para adicionar da lista das fixers disponíveis (embaixo) para a lista de fixers aplicadas (encima).

:arrow_down: Para remover da lista de fixers aplicadas (encima) e retornar para a lista de fixers disponíveis (embaixo).
  
![codecleanup](https://github.com/CaioDSPeixoto/CodeCleanupProfile/assets/72414478/dc48cc7c-49c9-4c16-9f0e-4796632042b3)

- Após finalizar os ajustes, basta clicar em OK para salvar as alterações.

</details>

<details>

<summary>Explicação das fixers</summary>

| Fixers  | Descricao | Url role| 
|---------|-----------|---------|

</details>

## Consigo automatizar a execução dessa limpeza?

> [!TIP]
> SIM! Para realizar a limpeza sempre após salvar o arquivo, basta acessar o caminho "Tools > Options > Text Editor > Code Cleanup", selecionar o perfil que será utilizado e ativar a opção "Run Code Cleanup profile on Save".

![image](https://github.com/CaioDSPeixoto/CodeCleanupProfile/assets/72414478/0bd74762-8da5-40ab-b7f8-266f95bb8da9)

### Links Úteis

[Microsoft - Code Cleanup](https://learn.microsoft.com/en-us/visualstudio/ide/code-styles-and-code-cleanup?view=vs-2022)

[Visual Studio 2022](https://visualstudio.microsoft.com/pt-br/vs/)

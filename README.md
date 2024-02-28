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

### **Passo 4**: Vamos navegar pelas opções que irão abrir após clicar na imagem anterior.
  
![image](https://github.com/CaioDSPeixoto/CodeCleanupProfile/assets/72414478/4ec69115-3e02-4760-9595-18728e6cfb16)

- Por padrão, a ferramenta vem com dois perfis de limpeza do código, sendo eles totalmente configuráveis.

</details>

<details>

<summary>Explicação das fixers</summary>

### **Passo 5**: Vamos navegar pelas opções que irão abrir após clicar na imagem anterior.
  
Organizar Usings (Sort and Remove Unused Usings):

Descrição: Organiza e classifica as declarações using no início do arquivo. Também remove aqueles que não são mais necessários.
Formatar Código (Format Code):

Descrição: Aplica formatação consistente ao código, como indentação, espaçamento e quebras de linha de acordo com as convenções de codificação.
Corrigir Espaços em Branco (Fix White Spaces):

Descrição: Remove espaços em branco extras ou adiciona espaços em branco conforme necessário para garantir uma consistência na formatação do código.
Corrigir Nomes (Fix Naming):

Descrição: Renomeia variáveis, métodos ou classes para seguir as convenções de nomenclatura definidas, garantindo consistência no código.
Reformatar Documento (Reorder Type and Member Declarations):

Descrição: Organiza a ordem de declaração de tipos e membros de acordo com convenções específicas.
Corrigir Constantes Mágicas (Use Explicit Type for Constants):

Descrição: Substitui constantes mágicas por constantes com tipos explícitos para melhorar a legibilidade e manutenção do código.
Aplicar Padrões de C# (Apply C# Code Style):

Descrição: Aplica estilos de código específicos do C# para garantir consistência no código, como a disposição de chaves, o uso de var ou tipos explícitos, entre outros.
Corrigir Comentários (Remove and Sort Usings):

Descrição: Remove comentários desnecessários ou desatualizados e organiza os comentários restantes para manter a clareza.
Aplicar Padrões de Formatação de Documento (Format Document):

Descrição: Realiza uma formatação abrangente do documento, ajustando a indentação, espaçamento e quebras de linha conforme as configurações definidas.

</details>

## Consigo automatizar a execução dessa limpeza?

> [!TIP]
> SIM! Para realizar a limpeza sempre após salvar o arquivo, basta acessar o caminho "Tools > Options > Text Editor > Code Cleanup", selecionar o perfil que será utilizado e ativar a opção "Run Code Cleanup profile on Save".

![image](https://github.com/CaioDSPeixoto/CodeCleanupProfile/assets/72414478/0bd74762-8da5-40ab-b7f8-266f95bb8da9)

### Links Úteis

[Microsoft - Code Cleanup](https://learn.microsoft.com/en-us/visualstudio/ide/code-styles-and-code-cleanup?view=vs-2022)

[Visual Studio 2022](https://visualstudio.microsoft.com/pt-br/vs/)

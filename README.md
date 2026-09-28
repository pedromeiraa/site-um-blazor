# SiteUmBlazor

Projeto acadêmico desenvolvido para praticar a criação de aplicações web com Blazor e .NET 10.

## Sobre o projeto

O projeto reúne exemplos simples de componentes Razor com renderização interativa no servidor. Entre as atividades disponíveis estão:

- contador;
- placar com ações para aumentar, diminuir e zerar a pontuação;
- exibição e ocultação de mensagem;
- página de informações sobre o clima;
- página sobre o projeto.

## Tecnologias

- .NET 10;
- ASP.NET Core;
- Blazor Web App;
- C#;
- Razor;
- Bootstrap.

## Pré-requisitos

- SDK do .NET 10 instalado;
- um navegador atualizado;
- Visual Studio Code ou outra IDE compatível com .NET.

Confira a instalação com:

```bash
dotnet --version
```

## Como executar

1. Abra um terminal na pasta do projeto.
2. Restaure as dependências:

   ```bash
   dotnet restore
   ```

3. Inicie a aplicação:

   ```bash
   dotnet run
   ```

Para desenvolver com recompilação automática, use:

```bash
dotnet watch run
```

Depois, acesse `https://localhost:7221` ou `http://localhost:5100`.

## Rotas disponíveis

| Rota | Descrição |
| --- | --- |
| `/contador` | Permite aumentar, diminuir e acompanhar o valor de um contador. |
| `/mensagem` | Exibe ou oculta uma mensagem ao clicar em um botão. |
| `/placar` | Gerencia a pontuação, com opções para adicionar, remover ou zerar pontos. |
| `/sobre` | Apresenta informações gerais sobre o projeto e seu desenvolvimento. |

## Estrutura principal

```text
SiteUmBlazor/
├── Components/
│   ├── Layout/       # Layout e menu de navegação
│   └── Pages/        # Páginas Razor da aplicação
├── Properties/       # Configurações de execução
├── wwwroot/          # Arquivos estáticos e estilos
├── Program.cs        # Configuração da aplicação
└── SiteUmBlazor.csproj
```

## Objetivo

O objetivo é aplicar conceitos básicos de componentes, rotas, eventos, estado e renderização interativa com Blazor.
# Site de Casamento Personalizado - Leo & Dan

Este é um site de casamento moderno e responsivo, desenvolvido para Leo & Dan, com funcionalidades essenciais para organizar e compartilhar os detalhes do grande dia com seus convidados.

## ✨ Funcionalidades Incluídas

- **Página Principal (`index.html`)**: Uma landing page elegante com informações sobre o casal, data, locais da cerimônia e recepção, e botões de acesso rápido.
- **Confirmação de Presença (RSVP - `rsvp.html`)**: Formulário para os convidados confirmarem presença, com campos para nome, número de acompanhantes e mensagem.
- **Lista de Presentes (`gifts.html`)**: Redirecionamento direto para a lista de presentes externa (Ferreira Costa).
- **Painel Administrativo (`admin.html`)**: Uma interface simples para os noivos visualizarem as confirmações de presença e gerenciarem outros detalhes (funcionalidade básica, pode ser expandida).
- **Design Responsivo**: O site se adapta a diferentes tamanhos de tela (desktops, tablets e smartphones).
- **Paleta de Cores Personalizada**: Tema visual em tons de terracota.
- **Foto de Fundo Personalizada**: Imagem do casal como plano de fundo na seção principal.

## 🚀 Como Usar (Iniciando do Zero no GitHub)

Siga estes passos para colocar seu site no ar usando o GitHub Pages:

### 1. Baixe o Projeto

Baixe o arquivo ZIP completo deste projeto. Ele contém todos os arquivos necessários, incluindo o `index.html`, `rsvp.html`, `gifts.html`, `admin.html`, a pasta `assets/` com a imagem de fundo e outros recursos.

### 2. Crie um Novo Repositório no GitHub

- Acesse [GitHub](https://github.com/) e faça login na sua conta.
- Clique no botão `New` (Novo) para criar um novo repositório.
- Dê um nome ao seu repositório (ex: `nosso-casamento` ou `leo-dan-casamento`).
- Certifique-se de que o repositório seja **Público**.
- **NÃO** marque a opção `Add a README file` (Adicionar um arquivo README) ou qualquer outra opção de inicialização. Deixe o repositório vazio.
- Clique em `Create repository` (Criar repositório).

### 3. Faça o Upload dos Arquivos

- Após criar o repositório, você verá uma página com instruções para fazer o upload de arquivos.
- Clique no link `uploading an existing file` (enviar um arquivo existente) ou arraste e solte os arquivos diretamente na página.
- **Arraste e solte TODOS os arquivos e pastas (incluindo `index.html`, `rsvp.html`, `gifts.html`, `admin.html`, `assets/`, etc.) que você extraiu do ZIP para a área de upload.**
- Role para baixo e clique em `Commit changes` (Confirmar alterações).

### 4. Configure o GitHub Pages

- No seu repositório, clique na aba `Settings` (Configurações).
- No menu lateral esquerdo, clique em `Pages` (Páginas).
- Em `Source` (Fonte), selecione `Deploy from a branch` (Publicar a partir de um branch).
- Em `Branch` (Branch), selecione `main` (ou `master`, dependendo do nome padrão do seu branch) e a pasta `/ (root)` (raiz).
- Clique em `Save` (Salvar).

### 5. Acesse Seu Site

- Após salvar as configurações do GitHub Pages, aguarde alguns minutos (geralmente de 5 a 10 minutos).
- O GitHub Pages irá construir e publicar seu site.
- O endereço do seu site será algo como: `https://SEU_USUARIO.github.io/NOME_DO_REPOSITORIO/`
  (Ex: `https://leoneope.github.io/leo-dan-casamento/`)

## 🎨 Personalização

Você pode facilmente personalizar este site editando os arquivos HTML e o CSS:

- **Nomes do Casal**: Edite `index.html`, `rsvp.html`, `admin.html` e `gifts.html` para alterar os nomes "Leo & Dan" para os seus.
- **Data e Hora**: Edite `index.html`, `rsvp.html` e `admin.html` para alterar a data e hora do casamento.
- **Locais**: Edite `index.html`, `rsvp.html` e `admin.html` para atualizar os endereços da cerimônia e recepção, incluindo os links do Google Maps.
- **Lista de Presentes**: Edite `gifts.html` e `index.html` para atualizar o link da sua lista de presentes.
- **Foto de Fundo**: Substitua o arquivo `assets/couple_background.jpg` pela sua própria foto. Certifique-se de manter o mesmo nome de arquivo ou atualizar a referência no `index.html`.
- **Cores**: As cores principais são definidas no bloco `<style>` dentro de `index.html` (variáveis CSS como `--terracota-primary`). Você pode alterá-las para a sua paleta desejada.
- **Textos**: Todos os textos são editáveis diretamente nos arquivos HTML.

## 🛠️ Desenvolvimento Local (Opcional)

Se você quiser testar as alterações localmente antes de fazer o upload para o GitHub, pode usar um servidor HTTP simples:

1.  Navegue até a pasta raiz do projeto no seu terminal.
2.  Execute o comando:
    ```bash
    python3 -m http.server 8000
    ```
3.  Abra seu navegador e acesse `http://localhost:8000`.

## 💖 Feito com Amor

Este site foi criado para ajudar você a celebrar seu dia especial. Esperamos que seja útil!


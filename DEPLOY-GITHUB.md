# Guia de Deploy — GitHub Pages

## Publicar o site em 5 minutos

### Pré-requisito
Conta no GitHub criada (usuário: `prado59`)

---

### Passo 1: Criar o repositório

1. Acesse: **https://github.com/new**
2. Em **Repository name**, digite: `namoradocerto`
3. Deixe como **Public**
4. **NÃO** marque "Add a README" nem ".gitignore"
5. Clique em **Create repository**

### Passo 2: Fazer upload dos arquivos

Na página do repositório:

1. Clique em **Add file** → **Upload files**
2. Arraste TODA a pasta `namoradocerto-site` para dentro (selecione todos os arquivos: `index.html`, `about.html`, `contact.html`, `privacy.html`, `404.html`, a pasta `css/`, a pasta `posts/`)
3. Role para baixo e clique em **Commit changes**

### Passo 3: Ativar GitHub Pages

1. No repositório, vá em **Settings** (⚙️)
2. No menu lateral esquerdo, clique em **Pages**
3. Em **Branch**, selecione `main` e `/ (root)`
4. Clique em **Save**
5. Aguarde 1-2 minutos

### Passo 4: Acessar o site

Seu site estará disponível em:
**https://prado59.github.io/namoradocerto/**

---

### Importante: Configurar o Google Analytics

No `index.html` e em todas as páginas, substitua `G-XXXXXXXXXX` pelo seu ID real do Google Analytics:

1. Crie uma conta em: https://analytics.google.com/
2. Copie o ID de medição (formato `G-XXXXXXXXXX`)
3. Substitua em TODOS os arquivos HTML

### Formulário de contato (opcional)

1. Crie conta em https://formspree.io/
2. Crie um novo formulário
3. Copie o ID do formulário
4. Em `contact.html`, substitua `SEU_FORM_ID` pelo ID

### Personalizar domínio (opcional)

Se quiser usar `namoradocerto.com`:
1. No repositório → Settings → Pages
2. Em **Custom domain**, digite `namoradocerto.com`
3. Configure os registros DNS no seu provedor de domínio

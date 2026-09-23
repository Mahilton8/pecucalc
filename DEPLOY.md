# Instruções de Deploy — GitHub Pages

## Passo a passo

### 1. Criar o repositório no GitHub

1. Acesse [github.com/new](https://github.com/new)
2. Defina o nome do repositório — sugestão: **`pecucalc`**
3. Marque como **Public**
4. **Não** marque "Add a README file" (você vai subir o seu)
5. Clique em **Create repository**

---

### 2. Fazer upload dos arquivos

Na página do repositório recém-criado:

1. Clique em **"uploading an existing file"** (ou arraste os arquivos)
2. Faça upload de:
   - `index.html`
   - `README.md`
3. Na caixa de commit, escreva: `feat: deploy inicial PecuCalc`
4. Clique em **Commit changes**

---

### 3. Ativar o GitHub Pages

1. Vá em **Settings** → **Pages** (menu lateral esquerdo)
2. Em **Source**, selecione **Deploy from a branch**
3. Branch: **main** | Folder: **/ (root)**
4. Clique em **Save**

---

### 4. Acessar o site

Após 1–2 minutos, o site estará disponível em:

```
https://mahilton8.github.io/pecucalc/
```

> Substitua `pecucalc` pelo nome exato que você escolheu no repositório.

---

## Atualizar o app (versões futuras)

Para subir uma nova versão do `index.html`:

1. Acesse o repositório no GitHub
2. Clique no arquivo `index.html`
3. Clique no ícone de lápis ✏️ (Edit)
4. Cole o conteúdo novo ou use o botão de upload
5. Commit com mensagem descritiva: `fix: correção cálculo suplementação` etc.

O GitHub Pages atualiza automaticamente em até 2 minutos.

---

## Via linha de comando (opcional)

Se preferir usar o terminal:

```bash
git clone https://github.com/mahilton8/pecucalc.git
cd pecucalc
# copie o index.html para esta pasta
git add .
git commit -m "feat: deploy inicial PecuCalc"
git push origin main
```

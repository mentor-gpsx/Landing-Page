# 🚀 GUIA COMPLETO: GitHub + Vercel

## ⏱️ TEMPO TOTAL: 5 MINUTOS

---

# 1️⃣ CRIAR REPOSITÓRIO NO GITHUB

## Passo 1.1: Acesse GitHub
```
1. Abra: https://github.com
2. Faça login na sua conta (ou crie uma)
```

## Passo 1.2: Criar novo repositório
```
1. Clique em "+" (canto superior direito)
2. Selecione "New repository"
3. Preencha os dados:

   Repository name: formacao-gestores
   Description: Landing page - Workshop GPS.X
   Public (deixar público)
   ✓ Add a README file
   ✓ Add .gitignore (Node)

4. Clique em "Create repository"
```

## Passo 1.3: Copiar link do repositório
```
1. Clique em "Code" (botão verde)
2. Copie o link HTTPS
   Exemplo: https://github.com/seu-usuario/formacao-gestores.git
```

---

# 2️⃣ FAZER UPLOAD DOS ARQUIVOS

## Passo 2.1: Clonar o repositório (no seu computador)
```bash
git clone https://github.com/seu-usuario/formacao-gestores.git
cd formacao-gestores
```

## Passo 2.2: Adicionar os arquivos
```
Copie os 3 arquivos para a pasta do repositório:
  - index.html
  - qr_pagamento.png
  - qr_whatsapp.png
  
(Os arquivos README.md e .gitignore já estão lá)
```

## Passo 2.3: Fazer commit e push
```bash
git add .
git commit -m "Initial commit: landing page com QR codes"
git push origin main
```

**Se pedir login:**
- Use seu email do GitHub
- Senha = token pessoal (gere em Settings > Developer settings)

---

# 3️⃣ CONECTAR VERCEL

## Passo 3.1: Acesse Vercel
```
1. Abra: https://vercel.com
2. Faça login (ou crie conta com GitHub)
3. Clique em "Add New" > "Project"
```

## Passo 3.2: Importar repositório
```
1. Clique em "Import Git Repository"
2. Cole o link do GitHub: https://github.com/seu-usuario/formacao-gestores.git
3. Clique em "Continue"
```

## Passo 3.3: Configurar projeto
```
Framework Preset: Other (deixar assim)
Root Directory: ./ (deixar assim)
Build Command: (deixar vazio)
Output Directory: ./ (deixar assim)

Clique em "Deploy"
```

## Passo 3.4: Aguardar deploy
```
Vercel vai processar... ⏳
Quando terminar, aparece a URL:

https://formacao-gestores.vercel.app
(ou outro nome similar)
```

---

# 4️⃣ CONFIGURAR DOMÍNIO CUSTOMIZADO (Opcional)

```
1. No painel do Vercel, vá em "Settings" > "Domains"
2. Adicione seu domínio customizado
3. Configure DNS (instruções aparecem na tela)
```

---

# ✅ PRONTO! AGORA VOCÊ TEM:

✅ Repositório no GitHub  
✅ Deploy automático no Vercel  
✅ URL pública funcionando  
✅ QR codes operacionais  

---

# 🔄 PARA FAZER UPDATES NO FUTURO

Qualquer vez que quiser atualizar:

```bash
# 1. Edite os arquivos localmente
# 2. Faça commit
git add .
git commit -m "Descrição da mudança"
git push origin main

# 3. Vercel detecta automaticamente e faz deploy
# (Leva 1-2 minutos)
```

---

# 🆘 TROUBLESHOOTING

## "Erro ao clonar repositório"
```
✓ Verifique se tem Git instalado: https://git-scm.com
✓ Verifique sua senha/token do GitHub
```

## "Deploy não funcionou no Vercel"
```
✓ Verifique se todos os 3 arquivos estão no repositório
✓ Acesse GitHub > seu repositório > confirme os arquivos
✓ Tente fazer novo deploy no Vercel
```

## "QR codes não aparecem"
```
✓ Verifique se qr_pagamento.png e qr_whatsapp.png 
  estão na mesma pasta que index.html
✓ Confirme o upload no GitHub
```

---

# 🎉 VOCÊ ESTÁ PRONTO!

Seu site está ao vivo! Compartilhe a URL:

**https://formacao-gestores.vercel.app**

(Ou o domínio customizado que configurou)

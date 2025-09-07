# 🚀 DEPLOY RÁPIDO - Render.com

## ⚡ Deploy em 3 Passos

### 1. **Subir para GitHub**
```bash
git init
git add .
git commit -m "Site PROGERAÇÃO pronto"
git remote add origin https://github.com/SEU_USUARIO/site-progeracao.git
git push -u origin main
```

### 2. **Conectar no Render**
1. Acesse: [render.com](https://render.com)
2. Clique: "New +" → "Static Site"
3. Conecte seu repositório GitHub
4. Configure:
   - **Name**: `site-progeracao`
   - **Build Command**: `npm install`
   - **Publish Directory**: `.`
   - **Start Command**: `npm start`

### 3. **Deploy Automático**
- ✅ Render fará o deploy automaticamente
- ✅ URL será gerada: `https://site-progeracao.onrender.com`
- ✅ Site estará online em poucos minutos

## 📁 Arquivos Incluídos

- ✅ `package.json` - Configuração do projeto
- ✅ `server.js` - Servidor Express
- ✅ `render.yaml` - Configuração do Render
- ✅ `render.json` - Configuração alternativa
- ✅ `healthcheck.html` - Verificação de saúde
- ✅ `DEPLOY.md` - Instruções detalhadas

## 🎯 Pronto para Produção!

O site está 100% otimizado para o Render.com com:
- SEO otimizado
- Meta tags completas
- Performance otimizada
- Responsividade total
- Favicon configurado

**Só fazer o push para o GitHub e conectar no Render! 🎉**

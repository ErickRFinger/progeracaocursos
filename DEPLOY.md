# 🚀 Deploy no Render.com - Site PROGERAÇÃO

## 📋 Pré-requisitos

1. **Conta no Render.com**: [render.com](https://render.com)
2. **Repositório Git**: GitHub, GitLab ou Bitbucket
3. **Arquivos do projeto**: Todos os arquivos do site

## 🔧 Passo a Passo para Deploy

### 1. **Preparar o Repositório**

```bash
# Inicializar Git (se ainda não foi feito)
git init

# Adicionar todos os arquivos
git add .

# Fazer commit
git commit -m "Site PROGERAÇÃO pronto para deploy"

# Conectar com repositório remoto
git remote add origin https://github.com/SEU_USUARIO/site-progeracao.git

# Enviar para o repositório
git push -u origin main
```

### 2. **Configurar no Render.com**

1. **Acesse**: [dashboard.render.com](https://dashboard.render.com)
2. **Clique**: "New +" → "Static Site"
3. **Conecte**: Seu repositório Git
4. **Configure**:
   - **Name**: `site-progeracao`
   - **Branch**: `main`
   - **Build Command**: `npm install`
   - **Publish Directory**: `.` (ponto)
   - **Start Command**: `npm start`

### 3. **Configurações Avançadas**

#### **Environment Variables** (se necessário):
```
NODE_ENV=production
```

#### **Custom Headers** (para melhor performance):
```
Cache-Control: public, max-age=31536000
```

### 4. **Deploy Automático**

- ✅ **Auto Deploy**: Ativado por padrão
- ✅ **Branch**: `main`
- ✅ **Build**: Automático a cada push
- ✅ **URL**: Gerada automaticamente

## 🌐 Acessando o Site

Após o deploy, você receberá uma URL como:
```
https://site-progeracao.onrender.com
```

## 🔄 Atualizações Futuras

Para atualizar o site:

```bash
# Fazer alterações nos arquivos
# Fazer commit
git add .
git commit -m "Atualização do site"
git push origin main

# O Render fará o deploy automaticamente
```

## 📊 Monitoramento

- **Logs**: Disponíveis no dashboard do Render
- **Métricas**: Uptime e performance
- **Domínio**: Pode conectar domínio personalizado

## 🛠️ Troubleshooting

### **Problemas Comuns:**

1. **Build falha**:
   - Verifique se todos os arquivos estão no repositório
   - Confirme se o package.json está correto

2. **Site não carrega**:
   - Verifique se o index.html está na raiz
   - Confirme se as imagens estão no caminho correto

3. **CSS não aplica**:
   - Verifique se o styles.css está sendo carregado
   - Confirme se os caminhos estão corretos

## 📱 Recursos Incluídos

- ✅ **Responsivo**: Funciona em todos os dispositivos
- ✅ **SEO**: Meta tags otimizadas
- ✅ **Performance**: Carregamento rápido
- ✅ **Favicon**: Logo da PROGERAÇÃO
- ✅ **Analytics**: Pronto para Google Analytics

## 🎯 Próximos Passos

1. **Conectar domínio personalizado** (opcional)
2. **Configurar Google Analytics** (opcional)
3. **Configurar SSL** (automático no Render)
4. **Monitorar performance**

---

**Site da PROGERAÇÃO pronto para produção! 🎉**

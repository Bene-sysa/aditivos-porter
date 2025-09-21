# 🎓 Sistema de Treinamento - Novo Processo de Faturamento

Sistema completo e interativo para treinamento do novo processo de faturamento, com transição de planilhas para o ERP como fonte única de dados.

## 🚀 Demonstração Online

**🌐 Acesse o sistema funcionando:** [https://SEU_USUARIO.github.io/treinamento-processo-faturamento](https://SEU_USUARIO.github.io/treinamento-processo-faturamento)

*(Substitua SEU_USUARIO pelo seu nome de usuário do GitHub)*

## 📁 Estrutura do Projeto

```
treinamento-processo-faturamento/
├── index.html                    # Hub principal de navegação
├── roteiro-treinamento.html      # Apresentação interativa completa
├── documentacao.html             # Guia de referência detalhado
├── matriz-raci.html              # Matriz de responsabilidades interativa
├── pocs-setoriais.html          # Guias práticos por setor
└── README.md                     # Este arquivo
```

## 🎯 Funcionalidades

### 🏠 **Hub Principal (index.html)**
- **Design moderno** com partículas animadas
- **Cards interativos** para cada módulo
- **Estatísticas** do processo em tempo real
- **Navegação intuitiva** entre seções

### 📚 **Roteiro de Treinamento (roteiro-treinamento.html)**
- **7 slides interativos** com progressão visual
- **Exercícios práticos** e simulações
- **Quiz integrado** para avaliação
- **Navegação por teclado** (setas)
- **Cenários reais** baseados nos documentos

### 📖 **Documentação (documentacao.html)**
- **Sidebar com busca** inteligente
- **Seções organizadas** por processo
- **FAQ interativo** expansível
- **Design responsivo** para consulta mobile
- **Procedimentos detalhados** passo-a-passo

### ⚡ **Matriz RACI (matriz-raci.html)**
- **Tabela interativa** com tooltips explicativos
- **Filtros dinâmicos** por time/responsabilidade
- **Vista Timeline** do fluxo temporal
- **Badges coloridos** com sistema intuitivo
- **Responsabilidades claras** para cada atividade

### 🔧 **POCs Setoriais (pocs-setoriais.html)**
- **5 guias específicos** por setor
- **Checklists interativos** com progresso
- **Calculadora de bonificações** integrada
- **Simuladores práticos** para cenários
- **Lembretes visuais** para prazos críticos

## ⚙️ Como Configurar no GitHub Pages

### **Passo 1: Criar o Repositório**

1. Acesse [github.com](https://github.com) e faça login
2. Clique em **"New Repository"** (botão verde)
3. Configure o repositório:
   - **Nome:** `treinamento-processo-faturamento`
   - **Visibilidade:** Public
   - ✅ Marque "Add a README file"
   - Clique **"Create repository"**

### **Passo 2: Upload dos Arquivos**

1. No seu repositório, clique em **"uploading an existing file"**
2. Arraste e solte TODOS os arquivos HTML:
   - `index.html`
   - `roteiro-treinamento.html`
   - `documentacao.html`
   - `matriz-raci.html`
   - `pocs-setoriais.html`
3. Na caixa de commit, escreva: `Adicionar sistema de treinamento completo`
4. Clique **"Commit changes"**

### **Passo 3: Ativar GitHub Pages**

1. No seu repositório, vá em **"Settings"** (aba superior)
2. Role a página até encontrar **"Pages"** na sidebar esquerda
3. Em **"Source"**, selecione:
   - **Branch:** `main`
   - **Folder:** `/ (root)`
4. Clique **"Save"**
5. ⏳ Aguarde 2-5 minutos para o deploy

### **Passo 4: Acessar o Sistema**

Após o deploy, seu sistema estará disponível em:
```
https://SEU_USUARIO.github.io/treinamento-processo-faturamento
```

> 💡 **Dica:** Substitua `SEU_USUARIO` pelo seu nome de usuário do GitHub

## 🎨 Personalização

### **Cores da Empresa**
Edite as variáveis CSS nos arquivos para personalizar:

```css
/* Cores principais */
--primary-gradient: linear-gradient(135deg, #667eea, #764ba2);
--accent-color: #4299e1;
--success-color: #48bb78;
--warning-color: #ed8936;
--danger-color: #e53e3e;
```

### **Logo da Empresa**
Adicione o logo editando o header em cada arquivo:

```html
<div class="header">
    <img src="logo-empresa.png" alt="Logo" style="height: 60px; margin-bottom: 1rem;">
    <h1>Novo Processo de Faturamento</h1>
</div>
```

### **Contatos Específicos**
Atualize as informações de contato em:
- `documentacao.html` → Seção "Contatos"
- `pocs-setoriais.html` → Função `showContacts()`

## 📱 Compatibilidade

- ✅ **Desktop:** Chrome, Firefox, Safari, Edge
- ✅ **Mobile:** iOS Safari, Android Chrome
- ✅ **Tablet:** iPad, Android tablets
- ✅ **Responsivo:** Adapta-se a qualquer tamanho de tela

## 🔧 Tecnologias Utilizadas

- **HTML5** com semântica moderna
- **CSS3** com Grid, Flexbox e animações
- **JavaScript** vanilla (sem dependências)
- **Design responsivo** mobile-first
- **Acessibilidade** WCAG 2.1 AA

## 📈 Métricas e Analytics (Opcional)

Para acompanhar o uso do treinamento, adicione Google Analytics:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## 🎯 Principais Destaques

### **Processo Transformado:**
- ❌ **Antes:** Planilhas manuais, retrabalho, erros
- ✅ **Agora:** ERP centralizado, dados confiáveis, eficiência

### **Pontos Críticos Enfatizados:**
- 🕙 **Dia 10:** Prazo para bonificações
- ⚖️ **Jurídico:** Baixar aditivos imediatamente
- 🎯 **Solicitante:** Criar orçamentos no SERVICE
- 📊 **ERP:** Única fonte de verdade

### **Experiência Interativa:**
- 🎮 Simuladores de cenários reais
- ✅ Checklists com progresso visual
- 🎯 Quiz de avaliação integrado
- 📱 Funcionamento perfeito no mobile

## 🔄 Atualizações Futuras

Para atualizar o conteúdo:

1. Edite os arquivos HTML localmente
2. No GitHub, clique no arquivo que quer editar
3. Clique no ícone ✏️ (Edit this file)
4. Faça as alterações
5. Commit as mudanças
6. As atualizações aparecerão automaticamente no site

## 📞 Suporte

Para dúvidas técnicas sobre o sistema:
- 📧 **Email:** suporte-tecnico@empresa.com
- 💬 **Slack:** #suporte-treinamento
- 📖 **Documentação:** Este README

---

## 🎉 Resultado Final

Você terá um **sistema completo de treinamento** com:

- ✅ Design profissional e moderno
- ✅ Interatividade total
- ✅ Funciona em qualquer dispositivo
- ✅ Hospedagem gratuita no GitHub
- ✅ Fácil manutenção e atualização
- ✅ URL personalizada da empresa

**🌟 Seu treinamento nunca mais será o mesmo!**

---

*Sistema desenvolvido para otimizar o processo de faturamento e capacitar equipes de forma moderna e eficiente.*
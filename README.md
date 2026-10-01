# LegisAlimentos - Site Institucional

Site profissional para Engenharia de Alimentos com painel administrativo.

## Acesso ao Painel Administrativo

**Atalho:** Pressione `Ctrl + Shift + A`

**Login padrão:**
- Usuário: `admin`
- Senha: `admin123`

> ⚠️ **Importante:** Altere a senha no arquivo `js/admin.js` (linhas 3-4) antes de publicar!

## Estrutura de Arquivos

```
legisalimentos_site/
├── index.html          # Página principal
├── css/
│   └── style.css       # Estilos do site
├── js/
│   ├── main.js         # Funcionalidades do site
│   └── admin.js        # Sistema de administração
└── assets/
    ├── img/            # Imagens
    ├── videos/         # Vídeos
    └── docs/           # Documentos
```

## Funcionalidades do Painel Admin

### 1. Geral
- Editar título principal
- Editar subtítulo
- Editar texto "Sobre Nós"

### 2. Mídia
- Escolher entre vídeo ou logo
- Upload de vídeo (MP4/AVI) ou inserir URL
- Upload de logo (PNG, JPG, BMP)

### 3. Missão, Visão e Valores
- Editar textos de Missão e Visão
- Editar lista de Valores (um por linha)

### 4. Conteúdo
- Adicionar conteúdo com:
  - Imagens (BMP, JPEG, PNG)
  - Arquivos PDF
  - Links externos (URLs)

### 5. Contato
- Telefone
- E-mail
- Endereço
- WhatsApp (número completo com código do país)
- Links das redes sociais (Instagram, LinkedIn, Facebook)

## Como Publicar

### Opção 1: Hospedagem Gratuita
1. [Netlify](https://netlify.com) - Arraste a pasta
2. [Vercel](https://vercel.com)
3. [GitHub Pages](https://pages.github.com)

### Opção 2: Hospedagem Paga
- Hostgator
- Locaweb
- UOL Host

## Personalizações

### Alterar cores
Edite o arquivo `css/style.css` e modifique as variáveis CSS no início:

```css
:root {
    --primary-color: #1e5631;    /* Verde principal */
    --secondary-color: #f39c12;  /* Laranja/dourado */
    --accent-color: #27ae60;     /* Verde claro */
}
```

### Alterar credenciais de acesso
Edite o arquivo `js/admin.js`:

```javascript
const ADMIN_USER = 'seu_usuario';
const ADMIN_PASS = 'sua_senha';
```

## Observações

- Os dados são salvos no navegador (localStorage)
- Para uso em produção, considere implementar um backend
- O site é totalmente responsivo (funciona em celular, tablet e desktop)
- Todos os textos são editáveis pelo painel admin

## Suporte

Para dúvidas ou suporte técnico, entre em contato.

---

**LegisAlimentos** - Engenharia de Alimentos  
CRQ-RS 053004319

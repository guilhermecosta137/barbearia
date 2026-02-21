# TLbarbeer - Site Premium

Site profissional desenvolvido para a barbearia TLbarbeer, focado em design premium, experiência do usuário e alta conversão.

## 🎯 Características

- **Design Premium**: Paleta de cores sofisticada (preto, cinza escuro, dourado)
- **Responsivo**: Funciona perfeitamente em desktop, tablet e mobile
- **Conversão Otimizada**: Múltiplos CTAs para agendamento via WhatsApp
- **Animações Suaves**: Transições e efeitos que valorizam a experiência
- **SEO Básico**: Meta tags e estrutura otimizada para buscadores
- **Performance**: Código limpo e otimizado para carregamento rápido

## 📁 Estrutura de Arquivos

```
tlbarbeer/
├── index.html      # Estrutura HTML do site
├── style.css       # Estilos e design
├── script.js       # Interatividade e animações
└── README.md       # Este arquivo
```

## 🚀 Como Usar

### Opção 1: Abrir Localmente (Mais Simples)

1. Baixe todos os arquivos (index.html, style.css, script.js)
2. Mantenha os 3 arquivos na mesma pasta
3. Clique duas vezes no arquivo `index.html`
4. O site abrirá no seu navegador padrão

### Opção 2: Com Servidor Local (Recomendado)

Se você tiver Python instalado:

```bash
# Navegue até a pasta do site
cd caminho/para/tlbarbeer

# Inicie um servidor local
python -m http.server 8000

# Abra no navegador
http://localhost:8000
```

Se você tiver Node.js e npm:

```bash
# Instale o live-server globalmente (apenas uma vez)
npm install -g live-server

# Na pasta do site, execute
live-server
```

## 🎨 Personalização

### Alterar Cores

Abra o arquivo `style.css` e modifique as variáveis CSS no início:

```css
:root {
    --color-accent: #d4af37;  /* Cor dourada (mude aqui) */
    --color-primary: #000000; /* Preto principal */
    /* ... outras cores ... */
}
```

### Alterar Número do WhatsApp

Procure por `5532998397552` nos arquivos e substitua pelo novo número:
- No arquivo `index.html`: Encontre todas as ocorrências do link WhatsApp
- Formato: `55` (código do Brasil) + `32` (DDD) + `998397552` (número)

### Adicionar Imagens Reais

1. Crie uma pasta chamada `images` na mesma pasta dos arquivos
2. Adicione suas imagens nesta pasta
3. No arquivo `index.html`, substitua:

```html
<!-- Procure por .image-placeholder e substitua por: -->
<img src="images/sua-foto.jpg" alt="TLbarbeer">
```

### Editar Textos (Copy)

Abra o arquivo `index.html` e localize as seções:
- **Hero**: Texto principal da página inicial
- **Services**: Descrição dos serviços
- **About**: Texto sobre a barbearia
- **Location**: Informações de contato

### Ajustar Google Maps

No arquivo `index.html`, procure pelo iframe do Google Maps e:

1. Acesse [Google Maps](https://www.google.com/maps)
2. Pesquise pelo endereço exato da barbearia
3. Clique em "Compartilhar" > "Incorporar um mapa"
4. Copie o código iframe
5. Substitua o iframe atual pelo novo código

## 📱 Recursos de Conversão

### Botões de WhatsApp

O site possui 3 tipos de botões para maximizar conversão:

1. **Botão Flutuante**: Sempre visível no canto inferior direito
2. **CTAs nas Seções**: Botões estratégicos em cada seção
3. **Botão no Menu**: Acesso rápido na navegação

Todos redirecionam para WhatsApp com mensagem pré-formatada.

### Mensagens Automáticas

As mensagens enviadas via WhatsApp já vêm pré-preenchidas:
- "Olá! Gostaria de agendar um horário na TLbarbeer."

Para personalizar, edite o parâmetro `text=` nos links do WhatsApp.

## 🔧 Funcionalidades Técnicas

### JavaScript
- **Scroll suave**: Navegação fluida entre seções
- **Menu mobile**: Responsivo e funcional
- **Animações**: Fade-in ao rolar a página
- **Navegação ativa**: Destaque da seção atual
- **Efeito parallax**: No hero principal

### CSS
- **Grid e Flexbox**: Layout moderno e flexível
- **Variáveis CSS**: Fácil personalização
- **Animações**: Transições suaves
- **Media queries**: Responsividade total
- **Custom scrollbar**: Estilização personalizada

## 📊 SEO Local

O site já inclui:
- Meta description otimizada
- Keywords relevantes para barbearia em Juiz de Fora
- Títulos hierarquizados (H1, H2, H3)
- Textos descritivos
- Alt text para imagens (quando adicionadas)

### Para Melhorar SEO:

1. **Google My Business**: Cadastre a barbearia
2. **Schema.org**: Adicione dados estruturados (JSON-LD)
3. **Sitemap**: Crie um sitemap.xml
4. **Analytics**: Instale Google Analytics
5. **Search Console**: Configure o Google Search Console

## 🎯 Próximos Passos Recomendados

### Essencial (Fazer Primeiro)
- [ ] Adicionar fotos reais da barbearia e trabalhos
- [ ] Atualizar o iframe do Google Maps com localização exata
- [ ] Testar todos os links do WhatsApp
- [ ] Verificar responsividade em diferentes dispositivos

### Importante
- [ ] Adicionar favicon (ícone do site)
- [ ] Criar logo profissional
- [ ] Adicionar depoimentos de clientes
- [ ] Criar galeria de trabalhos realizados
- [ ] Adicionar preços dos serviços

### Avançado
- [ ] Configurar domínio próprio (tlbarbeer.com.br)
- [ ] Implementar sistema de agendamento online
- [ ] Adicionar Instagram Feed
- [ ] Implementar chatbot
- [ ] Criar blog com dicas de estilo
- [ ] Adicionar formulário de contato
- [ ] Integrar Google Analytics

## 🚀 Hospedagem

### Opções Gratuitas:
1. **Netlify**: Arraste a pasta e faça deploy
2. **Vercel**: Deploy via GitHub
3. **GitHub Pages**: Hospedagem gratuita
4. **Render**: Deploy simples e rápido

### Opções Pagas (Recomendado):
1. **Hostinger**: A partir de R$ 10/mês
2. **HostGator**: Planos a partir de R$ 15/mês
3. **Locaweb**: Hospedagem nacional

## 📝 Manutenção

### Atualizações Frequentes:
- Horário de funcionamento
- Novos serviços
- Promoções especiais
- Fotos de trabalhos recentes

### Backups:
Faça backup dos arquivos regularmente antes de fazer alterações.

## 💡 Dicas de Conversão

1. **Teste os botões**: Verifique se todos os links do WhatsApp funcionam
2. **Imagens de qualidade**: Use fotos profissionais dos trabalhos
3. **Depoimentos**: Adicione avaliações de clientes
4. **Urgência**: Adicione "vagas limitadas" em promoções
5. **Prova social**: Mostre número de clientes atendidos
6. **Before/After**: Galeria de transformações

## 🎨 Paleta de Cores

```
Preto Principal:  #000000
Preto Secundário: #1a1a1a
Dourado/Accent:   #d4af37
Cinza Claro:      #a8a8a8
Fundo Escuro:     #0a0a0a
Borda:            #2a2a2a
```

## 📞 Suporte

Para dúvidas ou personalizações adicionais, considere contratar um desenvolvedor web freelancer ou agência especializada.

## 📄 Licença

Este site foi desenvolvido exclusivamente para TLbarbeer. Todos os direitos reservados.

---

**Desenvolvido com foco em qualidade, conversão e experiência do usuário premium.**

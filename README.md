# 🌿 Marabela - Sistema de Gestão de Resíduos Sólidos

<div align="center">

![Marabela](https://img.shields.io/badge/Marabela-Sistema%20de%20Coleta-10b981?style=for-the-badge&logo=recycle&logoColor=white)
![Status](https://img.shields.io/badge/Status-Ativo-success?style=for-the-badge)
![Versão](https://img.shields.io/badge/Versão-1.0.0-blue?style=for-the-badge)

**Sistema oficial de gestão e monitoramento de coleta de resíduos sólidos de Marabá**

[Funcionalidades](#-funcionalidades) • [Tecnologias](#-tecnologias) • [Como Usar](#-como-usar) • [Estrutura](#-estrutura-do-projeto)

</div>

---

## 📋 Sobre o Projeto

O **Marabela** é uma aplicação web desenvolvida para a Prefeitura de Marabá (SSAM) que permite aos cidadãos consultarem horários e rotas de coleta de resíduos sólidos em tempo real. O sistema oferece uma interface moderna, responsiva e acessível, com suporte a tema escuro e notificações em tempo real.

---

## ✨ Funcionalidades

### 🏠 Landing Page
- **Hero Section**: Apresentação visual do sistema com informações em tempo real
- **Contador de Rotas Ativas**: Exibe quantas rotas de coleta estão em andamento
- **Relógio em Tempo Real**: Mostra a hora atual no fuso horário de Belém/PA
- **Seção de Features**: Destaca as principais funcionalidades do sistema
- **Como Funciona**: Guia passo a passo para os usuários
- **Estatísticas**: Números do sistema (bairros atendidos, denúncias, etc.)
- **Blog/Notícias**: Seção com artigos sobre sustentabilidade e avisos

### 📅 Sistema de Cronograma de Coleta
- **Consulta por Bairro**: Pesquisa de horários por nome do bairro
- **Filtro por Região**: Filtragem por áreas da cidade:
  - Morada Nova
  - Nova Marabá
  - São Félix
  - Cidade Nova
  - Marabá Pioneira
  - Cidade Jardim
  - Rural/Distritos
- **Filtro por Status**: 
  - 🔴 **Aguarde** - Coleta ainda não está próxima
  - 🟢 **Prepare-se** - Coleta em até 60 minutos
  - 🟡 **Em Andamento** - Caminhão está passando agora
  - ⚫ **Finalizada** - Coleta já passou hoje
  - ⬜ **Sem coleta hoje** - Não há coleta no dia atual

### 🔔 Sistema de Notificações
- **Monitoramento de Bairro**: Usuário pode selecionar seu bairro para receber alertas
- **Notificações Push**: Alertas quando a coleta está próxima ou em andamento
- **Persistência Local**: Preferências salvas no navegador (localStorage)

### 🗺️ Mapa de Denúncias de Lixo
- **Mapa Interativo**: Baseado em Leaflet/OpenStreetMap
- **Reportar Lixo Irregular**: Clique no mapa para denunciar acúmulo de lixo
- **Tipos de Lixo**:
  - 🏠 Doméstico
  - 🏗️ Entulho/Construção
  - 📺 Eletrônico
  - ☠️ Perigoso
  - ♻️ Reciclável
  - 🌿 Orgânico/Poda
- **Upload de Fotos**: Até 3 imagens por denúncia (com compressão automática)
- **Mapa de Calor (Heatmap)**: Visualização das áreas com mais denúncias
- **Geolocalização Reversa**: Conversão automática de coordenadas em endereços
- **Visualizador de Imagens**: Modal para ver fotos em tela cheia

### 📰 Sistema de Blog
- **Artigos Educativos**: Conteúdo sobre reciclagem e sustentabilidade
- **Categorias**:
  - 🌿 Campanhas
  - ⚠️ Avisos
  - 📅 Eventos
  - 🎓 Educação
  - 📊 Relatórios
  - 📰 Notícias
- **Busca e Filtros**: Pesquisa por título, descrição e categoria
- **Tags**: Sistema de tags para organização do conteúdo
- **Compartilhamento Social**: Botões para WhatsApp, Facebook, Twitter e LinkedIn
- **Modal de Leitura**: Visualização completa dos artigos

### 🌙 Tema Escuro (Dark Mode)
- **Toggle de Tema**: Botão para alternar entre modo claro e escuro
- **Detecção Automática**: Respeita preferência do sistema operacional
- **Persistência**: Salva preferência do usuário
- **Transições Suaves**: Animações durante a troca de tema

### 📱 Design Responsivo
- **Mobile First**: Interface otimizada para dispositivos móveis
- **Menu Hambúrguer**: Navegação adaptativa em telas pequenas
- **Cards Adaptativos**: Grid responsivo (1 a 4 colunas)
- **Touch Friendly**: Botões e áreas de toque adequadas

### ♿ Acessibilidade
- **Focus Visible**: Indicadores visuais de foco para navegação por teclado
- **Contraste**: Cores com contraste adequado WCAG
- **Semântica HTML**: Estrutura semântica correta
- **Navegação por Teclado**: Suporte a atalhos (ESC para fechar modais, setas para navegação)

---

## 🛠️ Tecnologias

| Tecnologia | Uso |
|------------|-----|
| **HTML5** | Estrutura semântica |
| **Tailwind CSS** | Estilização e responsividade |
| **JavaScript (Vanilla)** | Lógica da aplicação |
| **Luxon** | Manipulação de datas e fusos horários |
| **Leaflet** | Mapas interativos |
| **Leaflet.heat** | Mapa de calor |
| **Font Awesome** | Ícones |
| **Google Fonts (Inter)** | Tipografia |

---

## 🚀 Como Usar

### Consultar Horário de Coleta
1. Acesse a Landing Page
2. Clique em "Consultar Cronograma"
3. Use a barra de busca para encontrar seu bairro
4. Ou utilize os filtros por região e status

### Ativar Monitoramento
1. Encontre seu bairro na lista
2. Clique no ícone de sino (🔔)
3. Permita notificações quando solicitado
4. Receba alertas automáticos sobre a coleta

### Denunciar Lixo Irregular
1. Clique em "Ver Mapa de Denúncias" na Landing Page
2. Ou acesse pelo botão "Mapa" no app de coleta
3. Clique no local do lixo no mapa
4. Selecione o tipo de lixo
5. Adicione descrição e fotos (opcional)
6. Confirme a denúncia

### Alternar Tema
- Clique no ícone de sol/lua (☀️/🌙) no cabeçalho

---

## 📁 Estrutura do Projeto

```
marabela/
├── index.html          # Arquivo principal (SPA)
├── README.md           # Documentação
└── assets/             # (futuro) Recursos estáticos
```

### Componentes Principais

```
index.html
├── Landing Page
│   ├── Header (navegação + tema)
│   ├── Hero Section
│   ├── Features
│   ├── How It Works
│   ├── Stats
│   ├── Blog Preview
│   └── Footer
│
├── App de Coleta
│   ├── Header (busca + filtros)
│   ├── Seção "Meu Bairro"
│   ├── Grid de Resultados
│   └── Footer
│
├── Blog Page
│   ├── Header
│   ├── Filtros
│   ├── Grid de Posts
│   └── Footer
│
└── Modais
    ├── Mapa de Denúncias
    ├── Formulário de Denúncia
    ├── Visualizador de Imagens
    └── Post do Blog
```

---

## 📊 Dados do Sistema

### Regiões Atendidas
- **Morada Nova**: 3 bairros
- **Nova Marabá**: 30+ bairros (Folhas)
- **São Félix**: 2 bairros
- **Cidade Nova**: 10+ bairros
- **Marabá Pioneira**: 2 bairros
- **Cidade Jardim**: 3 bairros
- **Rural/Distritos**: 6 localidades

### Horários de Coleta
- **Diurna**: 07:00 - 16:30
- **Noturna**: 18:00 - 02:00

### Dias de Coleta
- **Regular**: Segunda a Sábado
- **Especial**: Dias específicos para áreas rurais

---

## 💾 Armazenamento Local

O sistema utiliza `localStorage` para persistir:

| Chave | Descrição |
|-------|-----------|
| `coleta_user_neighborhood` | Bairro monitorado pelo usuário |
| `coleta_theme` | Preferência de tema (light/dark) |
| `coleta_trash_reports` | Denúncias de lixo reportadas |

---

## 🔧 Configurações

### Fuso Horário
O sistema utiliza o fuso horário `America/Belem` para garantir precisão nos horários de coleta.

### Coordenadas de Marabá
- **Centro**: -5.3688, -49.1178
- **Zoom Padrão**: 13

---

## 📱 PWA (Futuro)

O projeto está preparado para ser convertido em Progressive Web App:
- Meta tags de Open Graph configuradas
- Favicon SVG responsivo
- Design responsivo completo

---

## 🤝 Contribuição

Este é um projeto da Prefeitura de Marabá. Para sugestões ou reportar problemas:

1. Entre em contato com a SSAM
2. Use o sistema de denúncias para reportar problemas de coleta
3. Acompanhe as notícias no blog do sistema

---

## 📄 Licença

Este projeto é de uso público, desenvolvido para os cidadãos de Marabá.

---

<div align="center">

**Desenvolvido para a Prefeitura de Marabá - SSAM**

♻️ *Juntos por uma cidade mais limpa* ♻️

</div>

# 🎓 O Futuro Importa! | Transformando Caminhos

> *"Orientação, oportunidades e apoio para você construir um futuro melhor!"*

O **O Futuro Importa!** é uma plataforma web completa voltada para empregabilidade, capacitação gratuita e orientação profissional em todo o Brasil. O sistema conecta candidatos a empresas parceiras de maneira acessível, oferecendo um feed dinâmico de vagas, gerador de currículos em tempo real, curadoria de cursos gratuitos e um painel administrativo completo.

---

## ✨ Funcionalidades Principais

* **Feed de Vagas Estilo Rede Social:**
  * Publicação e visualização de vagas com filtros avançados por palavra-chave, Estado (UF), Cidade e Modalidade (*Presencial, Remoto ou Híbrido*).
  * Canais de candidatura flexíveis: envio direto pela plataforma, contato imediato via **WhatsApp** (com mensagem pré-preenchida) ou envio por **E-mail**.
  * Integração direta com o motor de busca do **Google Jobs Brasil**.
* **Gerador de Currículo Profissional (PDF):**
  * Formulário interativo com pré-visualização em tempo real no layout oficial da plataforma.
  * Exportação limpa e otimizada para impressão ou salvamento em **PDF** (`@media print`).
* **Sistema Multi-Perfil e Onboarding Inteligente:**
  * **Candidatos:** Cadastro com validação de máscaras (CPF, CEP, Telefone) seguido de uma etapa guiada para geração imediata do currículo inicial.
  * **Empresas Parceiras:** Cadastro com CNPJ e validação de domínio corporativo (bloqueio de provedores gratuitos comuns para maior segurança), liberando permissão para postar vagas no feed.
  * **Triagem Rápida de Competências:** Teste integrado no momento da candidatura avaliando conhecimentos básicos de Português, Matemática e Raciocínio Lógico.
* **Curadoria de Cursos Gratuitos:**
  * Diretório com acesso direto às principais plataformas de ensino gratuito com certificado do Brasil (SEBRAE, Fundação Bradesco, EV.G, Google Atelier, SENAI Play).
* **Painel Administrativo Exclusivo (Criador):**
  * Métricas em tempo real (acessos totais, candidatos cadastrados, empresas parceiras, vagas ativas e candidaturas).
  * Tabela de auditoria e logs de ações dos usuários com persistência via `localStorage`.
  * Permissão para moderar/excluir vagas e publicar comunicados ou vagas oficiais.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5 Semântico:** Estruturação acessível e organizada em seções e modais.
* **Tailwind CSS (via CDN):** Estilização responsiva e configuração customizada da paleta oficial da marca (`brand-deep`, `brand-vibrant`, `brand-plum`, etc.).
* **JavaScript (Vanilla ES6+):** Lógica de roteamento por abas, filtros dinâmicos, máscaras de formulário, geração de links de WhatsApp/Mailto e armazenamento local (`localStorage`).
* **Font Awesome 6 & Google Fonts (Inter):** Iconografia moderna e tipografia de alta legibilidade.

---

## 🚀 Como Executar o Projeto

Por ser desenvolvido em arquitetura **Single-File** (arquivo único autocontido), não há necessidade de instalação de dependências, servidores complexos ou etapas de build:

1. Baixe ou clone o arquivo `index.html`.
2. Abra o arquivo diretamente em qualquer navegador moderno (Google Chrome, Microsoft Edge, Firefox, Safari).
3. Para hospedar online gratuitamente, basta fazer o upload do `index.html` para serviços como **GitHub Pages**, **Vercel**, **Netlify** ou **Cloudflare Pages**.

---

## 🔐 Credenciais de Acesso (Ambiente de Demonstração)

Para testar os recursos exclusivos de gerenciamento e relatórios do sistema, utilize o botão **Entrar** no topo da página com as credenciais administrativas:

* **Usuário / E-mail:** `Ofu7ur01mp0r74`
* **Senha:** `20Futur026`

*(Para testar o fluxo de Candidato ou Empresa, basta clicar em **Cadastrar** e preencher os formulários).*

---

## 🎨 Identidade Visual (Paleta de Cores)

| Cor | Código Hex | Uso Principal |
| :--- | :--- | :--- |
| **Roxo Profundo** | `#542080` | Cabeçalhos, botões principais e títulos de destaque |
| **Roxo Vibrante** | `#8629B8` | Ícones, links ativos e gradientes |
| **Lilás Intenso** | `#B94BD5` | Detalhes de apoio e subtítulos |
| **Lilás Pastel** | `#D99AF0` | Bordas sutis e barra de rolagem |
| **Rosa Clarinho** | `#F8DDF8` | Badges e fundos de tags |
| **Off-White** | `#F7F2FA` | Fundo geral da página e inputs |
| **Ameixa Escuro** | `#30203F` | Textos principais e rodapé |

---

## 📄 Licença

© 2026 **O Futuro Importa! — Transformando Caminhos**. Todos os direitos reservados.
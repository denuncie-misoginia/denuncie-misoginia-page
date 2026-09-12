# Denuncie Misoginia — Informação, Proteção e Denúncia

Uma página web informativa e de utilidade pública voltada para a conscientização sobre a misoginia e a violência de gênero no ambiente digital, oferecendo orientações práticas sobre como coletar provas, conhecer seus direitos e encontrar canais seguros de acolhimento e denúncia no Brasil.

O projeto também destaca o debate legislativo em torno do **PL 896/2023** (de autoria da senadora Ana Paula Lobato), que propõe a tipificação de crimes resultantes de misoginia na Lei de Racismo (Lei nº 7.716/1989).

---

## 🚀 Funcionalidades

- **Guia Prático de Coleta de Evidências**: Passo a passo detalhado e interativo para ajudar vítimas a preservar provas digitais (prints, URLs, metadados) de forma robusta e juridicamente útil.
- **Checklist Interativo**: Uma lista de checagem interativa integrada que permite mapear se todas as informações necessárias foram coletadas antes do registro da denúncia.
- **Botão de Saída Rápida (Quick Exit)**: Localizado no topo e no menu, permite que a usuária saia instantaneamente da página para o site de buscas do Google e limpe dados temporários da sessão, preservando sua segurança e privacidade caso precise ocultar a navegação repentinamente.
- **Canais de Atendimento com Cópia Rápida**: Atalhos de discagem direta para o Ligue 180 (Central de Atendimento à Mulher) e 190 (Polícia Militar), além de links diretos para a SaferNet e Ministério Público Federal (MPF). Inclui também botões de clique-para-copiar os números para a área de transferência.
- **Seção de Perguntas Frequentes (FAQ)**: Respostas objetivas para dúvidas comuns sobre o valor de prints de WhatsApp como prova, denúncias anônimas e o que fazer em caso de ameaças.
- **Acessibilidade Prioritária**: Desenvolvido com foco em acessibilidade na web, utilizando `skip-link` para navegação por teclado, focos visuais claros, marcação semântica adequada e atributos ARIA para leitores de tela.

---

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído utilizando tecnologias web modernas de forma extremamente leve e direta (Single Page Application estática):

- **HTML5** (Semântico e estruturado para acessibilidade)
- **CSS3** & **Tailwind CSS** (Utilizado via CDN para estilização rápida, responsiva e elegante)
- **JavaScript (Vanilla)** (ES6+ para o comportamento dinâmico e controle de estados sem necessidade de frameworks pesados)
- **Lucide Icons** (Ícones em SVG modernos e acessíveis)
- **Google Fonts** (*Playfair Display* e *Inter* para excelente legibilidade)

---

## 📂 Estrutura do Projeto

```bash
denuncie-misoginia-page/
├── index.html     # Código-fonte principal (HTML, CSS customizado, Tailwind Config e JavaScript)
└── README.md      # Documentação do projeto (este arquivo)
```

---

## 💻 Como Rodar o Projeto Localmente

Como se trata de uma página estática pura, você não precisa instalar nenhuma dependência ou gerenciador de pacotes!

### Opção 1: Abrir diretamente no navegador
1. Faça o clone deste repositório:
   ```bash
   git clone https://github.com/seu-usuario/denuncie-misoginia-page.git
   ```
2. Navegue até a pasta do projeto:
   ```bash
   cd denuncie-misoginia-page
   ```
3. Dê um duplo clique no arquivo `index.html` ou abra-o diretamente com o seu navegador favorito.

### Opção 2: Usar uma extensão de servidor local (Recomendado)
Para uma experiência perfeita de carregamento de fontes e scripts externos:
- Se você utiliza o **VS Code**, pode instalar a extensão **Live Server** e clicar em **Go Live** no canto inferior direito.
- Alternativamente, usando Python (caso tenha instalado no sistema):
  ```bash
  python3 -m http.server 8000
  ```
  Depois, acesse `http://localhost:8000` em seu navegador.

---

## 📄 Aviso Legal (Disclaimer)

Esta página possui **caráter estritamente informativo e educativo**. Ela não substitui orientação jurídica, psicológica ou o atendimento de serviços oficiais de emergência das forças de segurança do Estado. O status e a tramitação do PL 896/2023 podem sofrer alterações; recomenda-se sempre consultar os portais oficiais da Câmara dos Deputados e do Senado Federal para obter informações atualizadas.

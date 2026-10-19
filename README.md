# 🌴 Tropicália

> Uma página web informativa e interativa dedicada a celebrar e explicar a **Tropicália**, o marcante movimento cultural brasileiro da década de 1960.

Este projeto foi desenvolvido como um trabalho educacional através do programa **Start by Alura**, funcionando como uma aplicação fictícia sem fins comerciais.

---

## 📌 Índice
* [Visão Geral](#-visão-geral)
* [Funcionalidades](#-funcionalidades)
* [Acessibilidade](#-acessibilidade)
* [Tecnologias Utilizadas](#-tecnologias-utilizadas)
* [Como Rodar o Projeto](#-como-rodar-o-projeto)

---

## 🔍 Visão Geral

A aplicação consiste em uma Landing Page responsiva estruturada em seções de navegação rápida:
* **Início:** Boas-vindas dinâmicas com apresentação visual do grupo *Os Mutantes*.
* **O que foi a Tropicália:** Seção textual detalhando a história, o auge (1967-1968) e as misturas artísticas do movimento.
* **Galeria:** Acervo visual dinâmico com fotos históricas de grandes nomes como *Jorge Ben, Gilberto Gil e Caetano Veloso*.
* **Contato:** Um formulário estruturado para envio de mensagens.

---

## ✨ Funcionalidades

- **Navegação Fluida (Single Page):** Links de ancoragem no menu superior para rolagem suave entre seções.
- **Animações de Rolagem:** Integração com a biblioteca externa `ScrollReveal` para revelação gradual dos elementos conforme o usuário navega na página.
- **Formulário de Contato:** Validação estrutural de campos (Nome, E-mail e Mensagem).
- **Design Responsivo:** Adaptável para dispositivos móveis e desktops utilizando o ecossistema do Bootstrap.

---

## ♿ Acessibilidade

O projeto conta com uma barra de ferramentas dedicada à acessibilidade para garantir uma experiência inclusiva:
- [x] **Aumento de Fonte (A+):** Permite ampliar os textos da página para melhor leitura.
- [x] **Diminuição de Fonte (A-):** Permite reduzir o tamanho dos textos.
- [x] **Alternância de Contraste:** Modifica as cores de fundo e texto para facilitar a navegação de usuários com baixa visão.
- [x] **Navegação por Teclado:** Seções principais mapeadas com atributos `tabindex` e `aria-label` para leitores de tela.

---

## 💻 Tecnologias Utilizadas

* **HTML5:** Estruturação semântica e tags de acessibilidade.
* **CSS3 Customizado:** Estilizações locais personalizadas (`styles.css`).
* **Bootstrap (v5.3.3):** Framework principal para agilidade em layout, grids e componentes responsivos.
* **Bootstrap Icons (v1.11.3):** Biblioteca de vetores para os ícones sociais e ferramentas.
* **JavaScript (Vanilla):** Lógica local para os botões de acessibilidade (`script.js`).
* **ScrollReveal (v4.0.9):** Biblioteca externa para animações assíncronas ativadas por rolagem de tela.

---

## 🚀 Como Rodar o Projeto

### Pré-requisitos
Você não precisa de nenhum servidor complexo, apenas de um navegador moderno instalado.

### Passo a Passo

1. **Clone este repositório:**
   ```bash
   git clone https://github.com
   ```

2. **Acesse a pasta do projeto:**
   ```bash
   cd nome-do-seu-repositorio
   ```

3. **Execução:**
   Como o projeto utiliza referências de CDN online para o Bootstrap e as bibliotecas, basta abrir o arquivo `index.html` diretamente em qualquer navegador (Google Chrome, Edge, Firefox, etc.) ou utilizar uma extensão como o *Live Server* no VS Code.

* **[Banco de Dados]** 

---

## 📝 Licença
Distribuído sob a licença **MIT**. Veja o arquivo `LICENSE` para mais detalhes.

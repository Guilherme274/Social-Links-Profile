
# Social Links Profile - Guilherme Paixão

Esta é uma solução para o desafio [Social links profile do Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG1Z96s6QD). O projeto consiste em um cartão de perfil responsivo que centraliza links de redes sociais, funcionando como uma "Linktree" personalizada.

  - [O Desafio](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ)

---

## 🔍 Visão Geral

### O Desafio

Os usuários devem ser capazes de:
- Visualizar estados de *hover* e *focus* em todos os links.
- Visualizar o layout de forma otimizada em diferentes tamanhos de tela (Responsividade).
- Interagir com uma interface limpa e acessível.

### Preview

![Design preview for the Social links profile coding challenge](./preview.jpg)

### Links

- [Projeto Hospedado](https://social-links-profile-one-blush.vercel.app)

---

## 🛠️ Meu Processo

### Tecnologias Utilizadas

- **HTML5 Semântico**: Para uma estrutura robusta e acessível.
- **CSS3 Personalizado**: Uso de variáveis (Custom Properties) para gerenciar cores.
- **Flexbox**: Utilizado para centralizar o card na tela e alinhar os elementos internos.
- **Mobile-first**: Design pensado primeiramente para dispositivos móveis.

### O que aprendi

Durante o desenvolvimento deste projeto, foquei em:
1. **Centralização Perfeita:** Uso de `min-height: 100vh` no corpo para garantir que o card fique sempre ao centro.
2. **Estilização de Botões:** Criação de transições suaves nos estados de `:hover`.
3. **Organização de Código:** Estruturação de classes CSS seguindo boas práticas de legibilidade.

```css
/* Exemplo de como gerenciei o estado de hover */
.link-button:hover {
  background-color: #c5f82a; /* Cor neon do desafio */
  color: #1f1f1f;
  font-weight: bold;
}

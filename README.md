# 📦 Clone Interface Mercado Livre

<img width="800"  alt="Image" src="https://github.com/user-attachments/assets/b28e98b2-97ab-4d40-a0d8-ab8831e55ae3" />


> Uma réplica responsiva da interface principal do Mercado Livre, desenvolvida com CSS Grid e manipulação otimizada do DOM.

## 🔗 Live Demo
[Acesse o projeto online aqui](https://clonemercado-livre.vercel.app/)

## 🛠️ Tecnologias Utilizadas

* **HTML5 Semântico**: Uso correto de tags como `header`, `main`, `section` e inputs do tipo `search`.
* **CSS3 Avançado**:
    * **Flexbox**: Alinhamento de menus e distribuição de elementos na navbar.
    * **CSS Grid**: Estrutura da vitrine de produtos responsiva (colunas adaptáveis).
    * **Scroll Snap & Overflow**: Criação de navegação com rolagem horizontal (carrossel) para mobile.
    * **Micro-interações CSS**: Efeitos de feedback tátil sem uso de scripts pesados.
* **JavaScript **:
    * Manipulação do DOM   
    * Manipulação de eventos (Click/Keypress).
    * Lógica de Menu Dropdown "Click Outside".
    * Redirecionamento de busca via teclado.

## 🚀 Funcionalidades Principais

### 1. 🔍 Experiência de Busca (Search UX)
* **Redirecionamento Inteligente**: O usuário pode pressionar "Enter" (ou "Ir" no teclado do celular) para realizar a busca, sem precisar clicar no botão, graças a um *Event Listener* de teclado.
* **Input Semântico**: Utilização de `type="search"` para ativar o teclado correto em dispositivos móveis.

### 2. 📱 Layout Mobile Otimizado
* **Adaptação de Grid**: A vitrine de produtos ajusta o número de colunas automaticamente baseado no tamanho da viewport.

### 3. 🖱️ Menu Dropdown & Interatividade
* **Menu de Categorias**: Lógica implementada com JavaScript para abrir/fechar e detectar cliques fora do menu para fechamento automático.
* **Feedback Tátil (CSS Only)**: Implementação de efeito de "pressão" nos cards de produtos utilizando apenas CSS (`transform: scale` e `box-shadow`), garantindo alta performance sem sobrecarregar a thread do JavaScript com animações de Ripple complexas.

## 📸 Screenshots

### Desktop

<img width="700"  alt="Image" src="https://github.com/user-attachments/assets/f7407f0b-8403-4e03-8a2c-e28604935131" />

# ⚛️ Atomic Architect 3D
https://atomic-architect.onrender.com

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-blue)](#)

O **Atomic Architect 3D** é um simulador web interativo em 3D que permite visualizar e manipular estruturas atómicas, explorar as propriedades físico-químicas dos elementos da tabela periódica e simular circuitos e materiais em tempo real.

---

## 🚀 Funcionalidades

- **🧱 Modulo Átomo & Material:**
  - Manipulação dinâmica de **Protões ($Z$)**, **Neutrões** e **Eletrões** via *sliders*.
  - Identificação automática do elemento químico e do seu estado de ionização (Neutro, Cátion, Ânion).
  - Cálculo e exibição em tempo real da **Massa Atómica**.
  - Ajuste de **Temperatura** para simular mudanças de estado físico (Sólido, Líquido, Gasoso).
- **🎨 Visualização 3D:**
  - Representação tridimensional interativa do elemento/material.
- **⚡ Módulo Circuito:**
  - Simulação do comportamento elétrico dos materiais e componentes.

---

## 🛠️ Tecnologias Utilizadas

- **Frontend:** [React](https://reactjs.org/) / [HTML5] / [CSS3] / [TypeScript/JavaScript]
- **Gráficos 3D:** [Three.js](https://threejs.org/) / WebGL (ou [React Three Fiber](https://docs.pmnd.rs/react-three-fiber/))
- **Estilização:** CSS Modules / Tailwind CSS

---

## 📦 Como Executar o Projeto

### Pré-requisitos
Certifica-te de ter o [Node.js](https://nodejs.org/) instalado na tua máquina.

### Passo a passo

1. **Clonar o repositório:**
   ```bash
   git clone [https://github.com/teu-usuario/atomic-architect-3d.git](https://github.com/teu-usuario/atomic-architect-3d.git)
Entrar no diretório do projeto:

Bash
cd atomic-architect-3d
Instalar as dependências:

Bash
npm install
# ou
yarn install
Iniciar o servidor de desenvolvimento:

Bash
npm run dev
# ou
npm start
Abra o navegador e aceda a http://localhost:3000 (ou a porta indicada no terminal).

🧪 Exemplo de Uso (Ouro - Au)
Para visualizar o Ouro-197 no simulador:

Protões (Z): 79

Neutrões: 118 (para atingir a massa de ~196.97 u)

Eletrões: 79 (Estado Neutro)

📄 Licença
Este projeto está sob a licença MIT. Sente-te à vontade para utilizar e contribuir!

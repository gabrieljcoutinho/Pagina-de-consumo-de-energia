# Sistema de Gerenciamento de Consumo de Energia

Uma aplicação web completa para controle de eficiência energética. O sistema permite que usuários se autentiquem para gerenciar dispositivos domésticos, monitorar o consumo individual e total, e organizar aparelhos por níveis de prioridade.

---

## 🚀 Funcionalidades

### Autenticação de Usuários
* **Página de Cadastro**: Permite a criação de novos usuários no sistema.
* **Página de Login**: Validação de acesso para entrada na plataforma.

### Painel de Controle (Dashboard)
* **Cadastro de Dispositivos**: Registro de aparelhos informando nome, nível de importância e consumo em kWh.
* **Filtro de Importância**: Organização automática da lista por níveis de prioridade (1 a 3).
* **Cálculo de Consumo Real-Time**: Soma automática do consumo de todos os dispositivos ativos através do método `reduce`.
* **Gerenciamento de Lista**: Opção de deletar dispositivos individualmente com atualização imediata da interface.

---

## 📂 Estrutura de Arquivos

O projeto está organizado da seguinte forma:

* `login.html`: Interface de acesso ao sistema.
* `cadastro.html`: Interface de criação de conta.
* `index.html`: Dashboard principal com lógica de gerenciamento de dispositivos.
* `css/`: Pasta contendo as folhas de estilo (como `index.css`).
* `js/`: Scripts de manipulação de dados e lógica de interface.

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Descrição |
| :--- | :--- |
| **HTML5** | Estruturação semântica das telas de login, cadastro e dashboard. |
| **CSS3** | Estilização moderna com sistemas de Grid e Flexbox. |
| **JavaScript (ES6+)** | Manipulação dinâmica do DOM, tratamento de eventos e lógica de arrays. |

---

## 📐 Lógica de Programação Aplicada

O núcleo do sistema utiliza métodos avançados de JavaScript para garantir performance:

* **`.push()`**: Para adicionar novos objetos de dispositivos ao estado da aplicação.
* **`.filter()`**: Para a remoção precisa de itens baseada no `ID` gerado pelo `Date.now()`.
* **`.sort()`**: Para ordenar a visualização conforme a importância do dispositivo.
* **`.reduce()`**: Para o cálculo matemático acumulativo do consumo total de energia.

---

## ⚙️ Como Executar o Projeto

Este é um projeto **Front-end puro**, o que significa que não precisa de servidores complexos para rodar.

1. Clone este repositório:
   ```bash
   git clone [https://github.com/seu-usuario/gerenciamento-energia.git](https://github.com/seu-usuario/gerenciamento-energia.git)

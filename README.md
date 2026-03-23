# 🤖 Tic Tac Toe AI for Papergames

Script de automação para **Tic-Tac-Toe** no site **papergames.io**, utilizando lógica de IA com **Minimax** para calcular a melhor jogada automaticamente.

> ⚠️ Este script foi desenvolvido para uso com **Tampermonkey/Greasemonkey** e roda diretamente no navegador.

---

## 📌 Visão Geral

Este userscript foi criado para automatizar partidas de **Jogo da Velha** no **papergames.io**.

Ele faz isso através de:
- leitura automática do tabuleiro;
- identificação do jogador atual (`X` ou `O`);
- cálculo da melhor jogada com algoritmo **Minimax**;
- clique automático na célula ideal;
- opções extras como **Auto Queue**, **Logout rápido** e **controle de profundidade da IA**.

---

## ✨ Funcionalidades

### 🧠 IA para jogar automaticamente
O script analisa o estado atual do tabuleiro e escolhe a melhor jogada possível usando o algoritmo **Minimax**.

### 🎯 Leitura automática do tabuleiro
Captura o estado das 9 posições do jogo diretamente da interface do **papergames.io**.

### 🖱️ Clique automático
Após calcular a melhor jogada, o script simula o clique na célula correspondente.

### 👤 Detecção do jogador
O script identifica automaticamente se o usuário está jogando com:
- `X`
- `O`

### ⚙️ Menu de configurações
Adiciona um botão de **Settings** na tela com opções para:
- ativar/desativar **Auto Queue**;
- ajustar a profundidade (`Depth`) da IA.

### 🔁 Auto Queue
Permite automatizar a fila de partidas, clicando em botões relevantes da interface para entrar novamente em jogos.

### 🚪 Botão de Logout
Inclui um botão de **Logout** para remover o nome de usuário salvo no armazenamento do script.

### 💾 Armazenamento local
Utiliza recursos do Tampermonkey/Greasemonkey para salvar:
- nome de usuário;
- profundidade da IA;
- estado do Auto Queue.

---

## 🛠️ Tecnologias utilizadas

- **JavaScript**
- **Tampermonkey / Greasemonkey**
- **DOM Manipulation**
- **MutationObserver**
- **Minimax Algorithm**

---

## 📂 Como funciona

O script segue este fluxo:

1. Aguarda o carregamento da página do **papergames.io**;
2. Lê o nome de usuário salvo ou solicita ao usuário;
3. Observa alterações no tabuleiro;
4. Captura o estado atual das casas;
5. Detecta se é a vez do jogador;
6. Calcula a melhor jogada com **Minimax**;
7. Simula o clique automaticamente;
8. Mantém recursos extras como **Auto Queue** e **Settings** ativos.

---

## ⚙️ Instalação

### 1. Instale uma extensão de userscript
Você pode usar uma destas extensões:

- **Tampermonkey**
- **Greasemonkey**
- **Violentmonkey**

### 2. Crie um novo script
Abra a extensão e crie um novo script.

### 3. Cole o conteúdo do arquivo
Cole o conteúdo do arquivo:

```bash
Tic Tac Toe AI for papergames.user.js

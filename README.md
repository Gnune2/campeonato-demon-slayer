# ⚔️ Hinokami League Manager

<div align="center">

![Badge em Desenvolvimento](https://img.shields.io/badge/STATUS-EM%20DESENVOLVIMENTO-yellow?style=for-the-badge)
![Badge Game](https://img.shields.io/badge/GAME-DEMON%20SLAYER-red?style=for-the-badge)
![Badge License](https://img.shields.io/badge/LICENSE-MIT-green?style=for-the-badge)

**Um sistema robusto para gestão de campeonatos locais de E-sports.**
*Focado na estratégia, banimentos e pontos corridos.*

[Funcionalidades](#-funcionalidades) • [Regras do Torneio](#-regras-de-negócio) • [Tecnologias](#-tecnologias) • [Como Rodar](#-como-rodar)

</div>

---

## 📖 Sobre o Projeto

O **Hinokami League Manager** é uma plataforma web desenvolvida para facilitar a criação, organização e execução de campeonatos de jogos de luta, com foco inicial em *Demon Slayer: Hinokami Chronicles*. 

Diferente de chaves de torneio simples, nosso sistema é projetado para ligas de **pontos corridos (ida e volta)** com regras de validação de personagens (bans e picks) integradas ao fluxo de registro de resultados. O objetivo é profissionalizar a jogatina local entre amigos.

## 🚀 Funcionalidades

- **Autenticação de Players:** Sistema de login e perfil de jogador.
- **Gestão de Convites:** Administradores enviam convites e jogadores aceitam participar da liga.
- **Gerador de Tabela:** Algoritmo automático de *Round Robin* (Todos contra todos) com rodadas de Ida e Volta.
- **Painel do Administrador:** Interface exclusiva para lançamento de resultados em tempo real.
- **Leaderboard Dinâmico:** Tabela de classificação atualizada automaticamente após cada partida.

## ⚖️ Regras de Negócio (O Diferencial)

O sistema não apenas registra pontos, ele valida se as regras do nosso campeonato estão sendo cumpridas:

1.  **Pontuação de Liga:**
    - 🏆 **Vitória:** 3 Pontos
    - 🤝 **Empate:** 1 Ponto
    - ❌ **Derrota:** 0 Pontos
2.  **Sistema Anti-Mirror:** Jogadores não podem utilizar o mesmo personagem na mesma partida.
3.  **Sistema de Banimento:** Registro de banimentos de personagens antes de cada confronto.
4.  **Regra de Exaustão (Ida e Volta):** O personagem utilizado pelo jogador na partida de "Ida" fica **bloqueado** para ele na partida de "Volta".

## 🛠 Tecnologias

Este projeto está sendo desenvolvido utilizando as seguintes tecnologias:

* **Front-end:** (Coloque aqui: ex: React.js / Vue / HTML5 & CSS3)
* **Back-end:** (Coloque aqui: ex: Node.js / Python Django)
* **Banco de Dados:** (Coloque aqui: ex: PostgreSQL / MongoDB)

## 📸 Screenshots

*(Espaço reservado para colocar prints do layout do site futuramente)*

## 🏁 Como Rodar o Projeto

```bash
# Clone este repositório
$ git clone [https://github.com/SEU-USUARIO/NOME-DO-REPO.git](https://github.com/SEU-USUARIO/NOME-DO-REPO.git)

# Acesse a pasta do projeto no terminal/cmd
$ cd NOME-DO-REPO

# Instale as dependências
$ npm install (ou o comando da sua linguagem)

# Execute a aplicação
$ npm start

# 🗡️ Dungeon Crawler: O Escolhido

Um jogo de RPG/Roguelite em turnos baseado em console (terminal), desenvolvido totalmente na linguagem C. Explore masmorras, resolva enigmas, aprimore seu equipamento e sobreviva para derrotar o temível lorde das trevas, Krauser.

## 📜 História

O sombrio Krauser aterroriza toda a vila, espalhando uma névoa de morte. Muitos tentaram invadir seu domínio, mas todos pereceram. As profecias sempre falaram de um **Escolhido** — alguém destinado a trazer o equilíbrio a este mundo caótico. Apenas aquele que transcender os limites de seu poder poderá empunhar as armas lendárias.

Lute. Sobreviva. E prove ser o guerreiro mais honrado de nossa era.

---

## ✨ Funcionalidades

* **Exploração em Turnos:** Navegue por 4 andares de masmorras geradas estaticamente com níveis crescentes de dificuldade.
* **Sistema de Combate Direcional:** O combate depende da direção que o jogador está olhando e da arma equipada.
* **Feedback Visual:** Sistema de renderização de ataques temporários (mostrando um `z` na área de dano) e temas visuais de cores para cada andar.
* **Armas e Evoluções (Ascensão):** Escolha sua classe no início e encontre o botão de ascensão para liberar o poder máximo da sua arma (efeito dourado).
* **IA de Inimigos Variada:** * `X`: Movimenta-se aleatoriamente.
* `Y`: Persegue o jogador ativamente.
* `Z` (Krauser - Boss): Teleporta-se e invoca lacaios para o campo de batalha.



---

## 🎮 Como Jogar

### Controles

* **W, A, S, D:** Movimentar o personagem e mudar a direção do olhar.
* **I:** Interagir com NPCs, portas, botões e descidas.
* **O:** Atacar (a área de acerto depende da sua arma).

### A Lenda do Mapa

| Símbolo | Descrição |
| --- | --- |
| `^`, `v`, `<`, `>` | O Jogador (A ponta indica a direção do olhar) |
| `*` | Parede impenetrável |
| `k` | Caixa frágil (Destrua atacando para abrir caminho) |
| `#` | Espinhos letais (Cuidado, hit kill!) |
| `@` | Chave da esperança |
| `D` | Porta trancada (Requer uma chave) |
| `O` | Botão de Ascensão (Evolui o dano da arma de 1 para 3) |
| `L` | Escadaria para o próximo andar |
| `N` | Ancião da Vila (Interaja para escolher sua arma) |

---

## ⚔️ O Arsenal do Escolhido

Ao falar com o Ancião no primeiro mapa, você deve escolher seu estilo de combate. Cada arma possui uma área de efeito (Hitbox) única:

| Escolha | Arma Inicial | Evolução (Ascensão) | Estilo de Ataque |
| --- | --- | --- | --- |
| **1** | Wooden Sword | **Master Sword** | **Cleave:** Foca em dois blocos imediatamente à frente e nas diagonais. |
| **2** | Patched Bow | **Galadhrim Bow** | **Longo Alcance:** Dispara em uma linha reta de até 4 blocos de distância. |
| **3** | Hickory Staff | **Void Staff** | **Área Mágica (AoE):** Ataca todos os blocos adjacentes (3x3 ao redor do jogador). |

---

## 🚀 Como Compilar e Executar

### Pré-requisitos

Este projeto foi desenvolvido utilizando bibliotecas específicas do Windows (`<windows.h>` e `<conio.h>`). Portanto, ele deve ser compilado e executado nativamente em ambientes **Windows**.

### Passo a Passo (Usando GCC/MinGW)

1. Clone o repositório:
```bash
git clone https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git

```


2. Navegue até o diretório do projeto:
```bash
cd SEU_REPOSITORIO

```


3. Compile o código com o GCC:
```bash
gcc main.c -o dungeon_crawler.exe

```


4. Execute o jogo:
```bash
./dungeon_crawler.exe

```



---

## 👨‍💻 Desenvolvedores

Este projeto foi desenvolvido com dedicação pela equipe:

* **Leonardo Augusto**
* **Adan Melo**


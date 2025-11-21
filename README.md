
# 🏰 **Castle Defender – Jogo em Unity (3D)**

Este repositório contém o projeto **Castle Defender**, um jogo desenvolvido em Unity seguindo o tutorial. O objetivo é defender o castelo contra ondas de inimigos (Esqueleto, Lagarto e Golem), utilizando animações, IA simples, sistema de vida, sistema de dano e criação contínua de monstros.

O projeto foi construído utilizando Unity 3D, com importação de assets externos gratuitos e scripts personalizados para movimentação, spawn de inimigos e combate.

---

## 🎮 **Descrição do Jogo**

**Castle Defender** é um jogo 3D desenvolvido no Unity utilizando o template _Universal 3D_ e assets gratuitos da Unity Asset Store.  
O objetivo principal é **defender o castelo** contra ondas de inimigos que surgem de portais mágicos espalhados pelo mapa.

O jogador controla um personagem equipado com uma katana. Três tipos de inimigos atacam o castelo:

- **Esqueleto** – Rápido, pouca vida (1 golpe).
    
- **Lagarto** – Vida moderada (2 golpes).
    
- **Golem** – Forte e resistente (3 golpes).
    

A cada intervalo de tempo, três portais invocam novos monstros automaticamente. O jogador precisa derrotá-los **antes que alcancem o portão do castelo**.

### 🕹 **Controles**

Os controles são os padrões importados junto ao asset **RPG Combat System**, permitindo movimentação fluida em terceira pessoa:

- **W / A / S / D** – Movimento do personagem
    
- **Mouse** – Controle da câmera
    
- **Botão Esquerdo do Mouse** – Ataque com a espada
    
- **Espaço** – Pular
    
- **Shift** – Correr
    

A katana possui um _collider_ configurado como **Trigger**, responsável por detectar colisões com os inimigos e aplicar dano de acordo com o sistema de vida implementado.

---

## 📜 **História do Jogo**

Há muitos anos, o Reino de Eldoria vivia em paz, protegido por um castelo mágico capaz de repelir qualquer ameaça. Porém, forças sombrias despertaram novamente. Três portais arcanos surgiram nos arredores do castelo, trazendo monstros de outras dimensões: **Esqueletos amaldiçoados**, **Lagartos mutantes** e o temível **Golem de Pedra**.

Você é o último guardião capaz de empunhar a espada ancestral. Sua missão é simples, mas vital:

> **Impedir que os monstros alcancem o portão do castelo e destruam o coração mágico que protege Eldoria.**

Com cada portal trazendo inimigos cada vez mais frequentes, apenas sua habilidade e reflexos podem salvar o reino. Derrote as criaturas, sobreviva às ondas e prove que ainda existe esperança para Eldoria.

---

## 🧩 **Principais Funcionalidades Implementadas**

- ✨ **Portais mágicos** com efeitos visuais
    
- 👹 **Três tipos de inimigos**, cada um com animações e vida próprias
    
- 🧭 **IA simples** configurada para perseguir e atacar o castelo
    
- ⚔️ **Sistema de combate** com detecção de golpes via _collider_
    
- ❤️ **Script de Vida do Inimigo** totalmente funcional
    
- 🔁 **Sistema de Spawn periódico** gerando monstros a cada X segundos
    
- 🛠 **Animações personalizadas** para Idle, Walk, Chase e Attack
    
- 📦 **Build final exportada** para execução
    


---

## 🚀 **Tecnologias utilizadas**

- **Unity 2021+** (Template: Universal 3D)
    
- **C# Scripts**
    
- Assets gratuitos da **Unity Asset Store**:
    
    - RPG Combat System
        
    - Hyper Casual Cartoon Castles
        
    - Magic Effects Free
        
    - Dungeon Skeletons Demo
        
    - Lizard Monster
        
    - Golem Monster

---

## 📂 **Estrutura do projeto**

```
CastleDefender/
 ├─ Assets/
 │   ├─ RPGCombatSystem/
 │   ├─ Castle/
 │   ├─ MagicEffects/
 │   ├─ Inimigos/
 │   │   ├─ Esqueleto/
 │   │   ├─ Lagarto/
 │   │   ├─ Golem/
 │   ├─ Scripts/
 │   │   ├─ criaMonstro.cs
 │   │   ├─ mataMonstro.cs
 │   │   ├─ VidaInimigo.cs
 │   └─ ...
 ├─ ProjectSettings/
 ├─ Packages/
 └─ README.md
```

---

## 🧠 **Scripts principais**

### **`criaMonstro.cs`**

Responsável pelo spawn automático dos inimigos nos círculos mágicos usando `InvokeRepeating`.

### **`mataMonstro.cs`**

Detecta colisão da espada com inimigos usando `OnTriggerEnter()` e aplica danos diferentes para cada tipo (via Tag).

### **`VidaInimigo.cs`**

Gerencia vida e morte dos inimigos (com portabilidade para animações e efeitos futuros).

---

## 🕹️ **Como jogar**

1. Clone este repositório:
    
    ```bash
    git clone https://github.com/SEU-USUARIO/SEU-REPO.git
    ```
    
2. Abra o Unity Hub → **Open Project**
    
3. Execute a cena principal do projeto (Environment)
    
4. Use a personagem para defender o castelo atacando os monstros!
    

---

## 📦 **Build do jogo**

O build final se encontra na pasta:

```
/Jogo Pronto/
```

Você pode executar o `.exe` para jogar diretamente.

---

## 📸 **Screenshots 


![1](https://github.com/user-attachments/assets/5a36a0fc-ad76-49b7-84f3-b6da96d0702a)
![2](https://github.com/user-attachments/assets/384c8ecc-9353-4214-af82-51f8eae135ac)
![3](https://github.com/user-attachments/assets/83cbcbea-6add-4d57-9482-8424446b3293)
![4](https://github.com/user-attachments/assets/2fa2cb76-334b-427a-a79c-688a9a770914)

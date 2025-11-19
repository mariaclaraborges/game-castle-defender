
# 🏰 **Castle Defender – Jogo em Unity (3D)**

Este repositório contém o projeto **Castle Defender**, um jogo desenvolvido em Unity seguindo o tutorial. O objetivo é defender o castelo contra ondas de inimigos (Esqueleto, Lagarto e Golem), utilizando animações, IA simples, sistema de vida, sistema de dano e criação contínua de monstros.

O projeto foi construído utilizando Unity 3D, com importação de assets externos gratuitos e scripts personalizados para movimentação, spawn de inimigos e combate.

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

```
![1](https://github.com/user-attachments/assets/df4ca589-29d1-49fe-b2f7-b04fa5c6f5b4)

![2](https://github.com/user-attachments/assets/90c29bd6-e3b6-407a-bef8-083c7982296b)

![3](https://github.com/user-attachments/assets/e4f1d88e-2a12-42ba-8225-dc2024aa64db)

![4](https://github.com/user-attachments/assets/08800c73-1bcc-4b4d-a5da-3b2cc9e78b57)


```


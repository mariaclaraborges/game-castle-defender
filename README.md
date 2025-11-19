
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


![1](https://github.com/user-attachments/assets/5a36a0fc-ad76-49b7-84f3-b6da96d0702a)
![2](https://github.com/user-attachments/assets/384c8ecc-9353-4214-af82-51f8eae135ac)
![3](https://github.com/user-attachments/assets/83cbcbea-6add-4d57-9482-8424446b3293)
![4](https://github.com/user-attachments/assets/2fa2cb76-334b-427a-a79c-688a9a770914)

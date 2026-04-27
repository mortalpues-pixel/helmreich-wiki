# 🌳 Árbol Genealógico de la Dinastía Helmreich

> [!info] Documento de Sangre
> Registro oficial y clasificado de las distintas ramas y descendencia de la Familia HMR, desde sus fundadores (Generación 0) hasta las generaciones vigentes. 
> *Los miembros fallecidos están marcados en el esquema visual y con el símbolo ✝️.*

## 📊 Mapa Genealógico Completo

```mermaid
flowchart TD
    classDef dead fill:#3b1e1e,stroke:#f66,stroke-width:1px,color:#fff;
    classDef adopted fill:#1e273b,stroke:#8aa,stroke-width:1px,color:#fff,stroke-dasharray: 5 5;
    classDef gen0 fill:#423011,stroke:#da5,stroke-width:2px,color:#fff;
    classDef union fill:#da5,stroke:#da5,width:10px,height:10px;
    classDef spouse fill:#222,stroke:#444,color:#888;

    %% --- RAMA PRIMARIA ---
    Morack["👑 Morack"]:::gen0 --- M_Union([💍]):::union --- Margarita["✝️ Margarita"]:::dead
    
    M_Union --> Zero["Zero"]
    M_Union --> White["White"]
    M_Union --> Payton["✝️ Payton"]:::dead
    M_Union --> Juana["Juana"]
    M_Union --> Mict["Mict"]
    M_Union --> Swoune["Swoune"]
    M_Union --> Elisa["✝️ Elisa"]:::dead

    White --- W_Union([💍]):::union --- W_Spouse["Pareja"]:::spouse
    W_Union --> Paolo["Paolo"]
    W_Union --> Tiziano["Tiziano"]
    W_Union --> Marge["✝️ Marge"]:::dead

    Marge --- Ma_Union([💍]):::union --- Ma_Spouse["Pareja"]:::spouse
    Ma_Union --> Guillermo["Guillermo"]
    Ma_Union --> Irratie["Irratie"]

    Juana --- J_Union([💍]):::union --- J_Spouse["Pareja"]:::spouse
    J_Union --> Luti["Luti"]
    J_Union --> Pato["Pato"]
    J_Union --> Nagel["Nagel"]
    J_Union --> Sophia["✝️ Sophia"]:::dead
    J_Union --> Flux["Flux"]

    Nagel --- N_Union([💍]):::union --- N_Spouse["Pareja"]:::spouse
    N_Union --> Nacho["Nacho"]

    %% --- RAMA SECUNDARIA ---
    Carlota["✝️ Carlota"]:::dead --- C_Union([🛡️]):::union --- Ron["⚔️ Ron"]:::gen0

    C_Union --> Gaby["Gaby"]
    C_Union --> Napo["Napo"]
    C_Union --> Futu["Futu"]
    C_Union --> Lisa["✝️ Lisa"]:::dead
    C_Union --> Deidara["Deidara"]
    C_Union --> Anna["✝️ Anna"]:::dead

    Futu --- F_Union([💍]):::union --- F_Spouse["Pareja"]:::spouse
    F_Union --> Must["Must"]
    F_Union --> Beagle["Beagle"]
    F_Union --> Sacu["Sacu"]
    F_Union --> Chad["Chad"]
    F_Union --> Governor["Gov."]
    F_Union --> Mac["Mac"]
    F_Union --> Sebastian["Sebast."]

    Beagle -. Adopción .-> Maya["Maya"]:::adopted
```

---

## 📜 Archivo Histórico por Ramas

### 👑 Línea de Morack y Margarita
Los fundadores de la rama principal.

* **Primera Generación (Hijos):** 
  * [[Zero Helmreich]]
  * [[White Helmreich]]
  * [[Payton Helmreich]] (✝️)
  * [[Juana Helmreich]]
  * [[Mict Helmreich]]
  * [[Swoune Helmreich]]
  * [[Elisa Helmreich]] (✝️)

* **Segunda Generación (Nietos):**
  * *Hijos de White:* Paolo, Tiziano, Marge (✝️)
  * *Hijos de Juana:* Luti, Pato, Nagel, Sophia (✝️), Flux

* **Tercera Generación (Bisnietos):**
  * *Hijos de Marge:* Guillermo, Irratie
  * *Hijos de Nagel:* Nacho

### ⚔️ Línea de Carlota y Ron
La rama secundaria de la descendencia.

* **Primera Generación (Hijos):**
  * [[Gaby Helmreich]]
  * [[Napo Helmreich]]
  * [[Futu Helmreich]]
  * [[Lisa Helmreich]] (✝️)
  * [[Deidara Helmreich]]
  * [[Anna Helmreich]] (✝️)

* **Segunda Generación (Nietos):**
  * *Hijos de Futu:* Must, Beagle, Sacu, Chad, Governor, Mac, Sebastian

* **Tercera Generación (Bisnietos - Adopción):**
  * *Adoptada por Beagle:* [[Maya Helmreich]] (Canónicamente adoptada)

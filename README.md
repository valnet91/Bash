Langage: BASH

---
Bash: langage
category: Débutant
---

![Langage: BASH](Gnu-bash-logo.svg.png)

# Exemple de Mermaid en français

-- Mermaid pour Github

```mermaid
gitGraph
      commit
      commit
      branch develop
      checkout develop
      commit
      commit
      checkout main
      merge develop
      commit
      commit
```

```mermaid
  gitGraph
      commit
      commit
```     

```mermaid
  graph TD;
      A-->B;
      A-->C;
      B-->D;
      C-->D;
```
```mermaid
flowchart LR
A --> B
```

```mermaid
flowchart LR
A(Toutes mon Activités) --> B(tâches)
B --> Projets & C(Tâches complexes) & D(Tâches unitaires)
```

```mermaid
flowchart RL
A(Toutes mon Activités) --> B(tâches)
B --> Projets & C(Tâches complexes) & D(Tâches unitaires)
```

```mermaid
flowchart TD
A(Toutes mon Activités) --> B(tâches)
B --> Projets & C(Tâches complexes) & D(Tâches unitaires)
```

```mermaid
flowchart TD
	id1(Sujet en attente) --> id2(Boite de réception)
	id2 --> id3[Catégoriser]
	id3 --> id4{Action nécessaire?}
	id4 -- Non --> Jeter & Futur & Conserver
	id4 -- Oui --> id5{Plusieurs étapes?}
	id5 --> id7[Classer le projet]
	id7 --> id8[Découper] --> id9[Déterminer la première action]
	id9 --> id10{> 2 minutes?}

	id5 -- Non --> id10

	id10 --> id11[Faire tout de suite]
	id10 --> id12{Délégué?}

	id12 -- Oui --> id13[Effecturer la délégation]
	id12 -- Non --> id14[Reporter]
  ```
```mermaid
flowchart LR
	classDef rouge fill: #F00
A(Toutes mon Activités) --> B(tâches)
B --> Projets & C(Tâches complexes) & D(Tâches unitaires)
B --> E(Tâches au long court):::rouge
B --> F(Livrables)

A --> G(Rendez-vous)
G -. Sujets .-> B
G -. Actions .-> B
```
```mermaid
graph TD
    A[Choosing an OS] --> B{Do you fear technology ?}
    B -->|Yes| C{Is your daddy rich ?}
    C -->|Yes| E(fa:fa-apple Mac OS);
    C -->|No| F(fa:fa-chrome Chrome OS);
    
    B -->|No| D{Do you care about freedom/privacy ?}
    D -->|Yes| G{Do you have a life ?}
    D -->|No| H(fa:fa-windows Windows);
    
    G -->|Yes| I(fa:fa-ubuntu Ubuntu);
    G -->|Yes| K(fa:fa-fedora Fedora);
    G -->|No| L(fa:fa-linux Archlinux);
    G -->|No| M(fa:fa-shield Backtrack);

    style A fill:#0094FF,stroke:#333,stroke-width:4px,color:#fff
    style E fill:#808080,stroke:#333,stroke-width:2px,color:#fff,stroke-dasharray: 5 5
    style F fill:#808080,stroke:#333,stroke-width:2px,color:#fff,stroke-dasharray: 5 5
    style H fill:#004A7F,stroke:#333,stroke-width:2px,color:#fff,stroke-dasharray: 5 5
    style I fill:#FF6A00,stroke:#333,stroke-width:2px,color:#fff,stroke-dasharray: 5 5
    style K fill:#FF6A00,stroke:#333,stroke-width:2px,color:#fff,stroke-dasharray: 5 5
    style L fill:#7F0000,stroke:#333,stroke-width:2px,color:#fff,stroke-dasharray: 5 5
    style M fill:#7F0000,stroke:#333,stroke-width:2px,color:#fff,stroke-dasharray: 5 5
```

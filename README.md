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
 graph TD 
 st{HI!}
 good((Great))
 bad((Mizzz))
 en>Goodbye!]
A((HI))
```

```mermaid
graph TB
A(C'est parti.) --> B{Si vous êtes connecté}
B --- Oui. --> C[Aller à la page d'accueil]
B -- Non --> D[ Invite à ouvrir une session ]
C & D --> E(Fin)
F[ Noeuds qui peuvent sauter ];
click 

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


```mermaid
graph TD
start[<font size=6>附一电子报销流程]-->a1[<font size=6>1.发票检验]
a1-->b1[<font size=6>发票税号正确]
b1--<font size=6>是-->c1[<font size=6>发票下方盖公司有效印章]
c1-->d1[<font size=6>发票背面填写项目]
d1-->e1[<font size=6>项目名称]
d1-->e2[<font size=6>项目负责人签名]
d1-->e3[<font size=6>报销人签名]
d1-->e4[<font size=6>审核人签名]
start-->a2[<font size=6>2.填写报销单]
a2-->b2[<font size=6>项目负责人审核通过]
b2-->c3[<font size=6>打印报销单]
start-->a3[<font size=6>3.获取入库单]
a3-->a3b1[<font size=6>锐竞平台下单]
a3b1-->a3c1[<font size=6>...]
a3c1-->a3d1[<font size=6>在结算页面打印入库单]
b1--<font size=6>否-->c2[<font size=6>发票退回发票源更正]
c2-->a1
classDef className fill:#f9f,stroke:#333,stroke-width:4px
class start,a1,a2,a3 className;
```

```mermaid
gantt
axisFormat %e%b
todayMarker on
section Activity 1
    TaskA	: TA, 2021-06-14, 4d
    TaskB	: TB, after TA, 2d
section Activity 2
    TaskC	: TC, after TA, 3d
    TaskD	: TD, after TC, 2d
section Activity 3
    TaskE	: TE, after TD, 1d
    TaskF	: TF, after TE, 2d
```

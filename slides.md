---
marp: true
theme: gaia
paginate: true
---

![bg left:33%](./img/forge-411923_640.jpg)

<br>
<br>

# Software Craftsmanship

---
# whoami


```rust
fn main() {

    let lastname = "Moreau";
    let firstname = "David";
    let company = "Thales Alenia Space";
    let mut email:String = "david.moreau".to_owned();
    email.push_str("@jxdm.fr");

    println!("I'm {} {} email:{}", firstname, lastname, email);
}
```


---

<br>
<br>

# What's a Software Developer?



---

![bg](./img/construction-site-3432379_1280.jpg)
<!--
* Métaphore de la construction, architecte + autres corps de métier
* Archicte construction != Architecte logiciel
* Voir swarch, ivory tower
* Construction, c'est la compilation. la conception, c'est le développement
* La construction est un procédé industrielle maintenant mature avec des contraintes physiques claires
* Le developpement logiciel reste un métier jeun et surtout en perpetuelle évolution
* La créativité des différents corps de métier reste très limité par rapport au plan
Exemple il y a 30 ans (proc 200Mhz, pas de javascript, ni PHP/java)
* Les progrès de la construction sont simples et visibles alors que le développement logiciel est abstrait et invisible => dmo
* Processus de fabrication
* Si on recommence la même maison: temps identique, peu importe les macons
* Différents en softs: apprentissage + différentes compétences
-->
---

![bg](./img/piano-1846719_1920.jpg)
<!--
* Métaphore de l'artiste
* Pratiquer pour devenir meilleur comme un pianiste (par contre le piano évolue)
* Compositeur: nommage des variables, choix des algos
* Poète/peintre: beau code
-->

---

![bg](./img/garden-2040714_1920.jpg)
<!--
* Un logiciel ressemble à un jardin qui mérite un entretien en même temps qu'il grandit
* Entretien régulier/art
-->


---

![bg c](./img/tools.jpg)





<!--
* uses **his** knowledge and tools to create a 
specific product to satisfy a client need
* continiously improve its skills, to become a better developper
* Each developper is different
* :arrow_right: Craftsmanship Methaphor
-->

<!-- Pour améliorer vos logiciles, il faut de meilleuirs artisans
Parler de génération de code -->

---

# Software development

### Complex != Difficulty
* Ecosystem constant evolution 
* Software needs evolution
* art, creativiy


---

<br>
<br>

# What's Agile?

---

![bg contain](./img/Cycle_de_developpement_en_v.svg.png)

<!--
* Cycle de développement en cascade
* Ne répond pas au besoin de changement du monde du développement logiciel. Changement fonctionnel, changement de design
-->

---

### Software Developpement
Qu'est-ce que l'agilité
=> un manifeste
=> mindset

des exemples: scrum, extrem programming

=> Complex != compliqué

Complexité de nommer les choses
Le soft est partout: diesel gaten boeing...
la qualité intrinsèque est gratuite: se former qui est cher
Pourquoi désirer la qualité: pour soi, pour l'équipe
qualité intrinsèque: code, architecture, sécurité, performance


---
# Agile Manifesto (2001)

![bg left:33%](./img/agile.jpeg)
<!--
En février 2001, aux États-Unis, dix-sept spécialistes du développement logiciel
* 4 valeurs/12 principes
-->
**Individuals and Interactions** over processes and tools

**Working Software** over comprehensive documentation

**Customer Collaboration** over contract negotiation

**Responding to Change** over following a plan 

---

![bg left:100% 80%](./img/agile-hangover.jpg)

---
![bg left:33%](./img/question.jpeg)

### What's Wrong?
### What's Missing?

<br>

* In a software product, the most important deliverable is the software itself


---
![bg left:33%](./img/factory.jpg)
#### A Naive Approach to Software Projects

- Well-defined industrial process
- Engineeers and Architects
- Developpers as factory workers
- More developpers, more production
- Monnitoring
    - number of lines
    - % comments
<!-- Un deveppeur sous pression prend des raccourcis, ajoute de la complexité.
Ne prend pas le temps d'automatiser une tache répétitive -->

---
<!-- les sociétés choisissent cherchent uniquement un coût -->

---
<!--
### HOWTO Create a better Software

- More Software Developpers or better Craftmen?

    - Software Craftsmen
- Give
    - Autonomy
    - Mastering
    - Purpose

---
-->
![bg left:33%](./img/craft.jpg)
### Manifesto (2009)


Not only working software, but also **well-crafted software**

Not only responding to change,but also **steadily adding value**
<!-- Règle du boy-scout -->

Not only individuals and interactions, but also a **community of professionals**

Not only customer collaboration, but also **productive partnerships**

---
![bg left:33%](./img/def.jpg)
#### Software Craftsmanship: A Mindset
<!-->>It's a mindset where software developpers choose to be responsible for their own carreers, constantly bettering themselves.-->

>Software Craftsmanship is all about putting responsibility, professionalism, pragmatism, and pride back into software developpement.
*Sandro Mancuso, The Software Craftsman, 2014*

---
<!--
# Définitions
>Software craftsmanship is an approach to software development that emphasizes the coding skills of the software developers.
>It is a response by software developers to the perceived ills of the mainstream software industry, including the prioritization of financial concerns over developer accountability
*Wikipedia*

---
## Un peu d'Historique

* 1992, "What Is Software Design?", Jack W. Reeves
* 1999, "The Pragmatic Programmer: From Journeyman to Master "
* 2017, "Software Craftsmanship: The New Imperative"
* 2008, "Craftsmanship over Crap", Robert C. Martin 
* 2009, Manifesto for Software Craftsmanship
* 2010, London Software Craftsmanship Community 
* 2014, "Software Craftsmanship : Professionalism Pragmatism Pride", Sandro Mancuso
* 2017, 2018, 2019 Conférence SC Londres

---
-->
![bg left:33%](./img/oath.jpg)
# Mindset and Behaviors

- Never stop learning
- Never stop improving his craft
- Learn how to say no
- Provide options
- Be responsible
- Share your knowledges


---
![bg left:33%](./img/desordre.jpg)
## The Invisible Threat


![width:400px](./img/coc.svg)
- Software Entropy
    - Complexity
    - Technical Debt

<!-- "tendance naturelle d'un système à se désordonner" -->

---
![bg left:33%](./img/pair.png)

### Technical Practices

- Clean Code
    - Keep It Simple, Stupid (KISS)
    - Boy Scout Rule
    - YAGNI
    - Naming, Coupling...
    - Refactoring
- TDD (Test Driven Developpement)
- Pair Programming




---
<style>
img[alt~="center"] {
  display: block;
  margin: 0 auto;
}
</style>

### TL;DR

![center](./img/balance.png)



---

<br>
<br>

>Software Craftsmanship promises to take our industry to the next level, promoting professionalism, technical excellence, the death of the production line and factory workers attitude."
*Sandro Mancuso*

---
#### Ressources

- Book "Clean Code: A Handbook of Agile Software Craftsmanship", Robert S. Martin, 2008
- Book "Software Craftsmanship : Professionalism Pragmatism Pride", Sandro Mancuso, 2014
- Conference "The Craftsman's Oath", Robert S. Martin - SCLConf 2018 

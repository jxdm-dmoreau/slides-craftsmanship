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
# Agile Manifesto (2001)

![bg left:33%](./img/agile.jpeg)
<!--
En février 2001, aux États-Unis, dix-sept spécialistes du développement logiciel
* 4 valeurs/12 principes
* mindset + manifest
* framework: scrum/XP...
-->
**Individuals and Interactions** over processes and tools

**Working Software** over comprehensive documentation

**Customer Collaboration** over contract negotiation

**Responding to Change** over following a plan 


---
![bg left:33%](./img/surf.jpg)

###  TL;DR;
* Accept change
* Learn to ride
* Feedback loop providing data
* Business Value Oriented


---
<br >
<br >

# Agility everywhere

---

![bg left:100% 80%](./img/agile-hangover.jpg)

---
![bg left:33%](./img/question.jpeg)


<br>
<br>

## What's Wrong?
## What's Missing?


<br>





---
![bg left:33%](./img/factory.jpg)
#### Wrong understanding

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

![bg](./img/construction-site-3432379_1280.jpg)
<!--
* Métaphore de la construction, architecte + autres corps de métier
* Archicte construction != Architecte logiciel
* Construction, c'est la compilation. la conception, c'est le développement
* La construction est un procédé industrielle maintenant mature avec des contraintes physiques claires
* Le developpement logiciel reste un métier jeun et surtout en perpetuelle évolution
* La créativité des différents corps de métier reste très limité par rapport au plan
Exemple il y a 30 ans (proc 200Mhz, pas de javascript, ni PHP/java)
* Les progrès de la construction sont simples et visibles alors que le développement logiciel est abstrait et invisible => dmo
* Si on recommence la même maison: temps identique, peu importe les macons
* Différents en softs: apprentissage + différentes compétences

* apprentissage et résolution d'un problème
* Dépendant de l'équipe
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

* writter

---

![bg c](./img/tools.jpg)
<!-- Définition de l'artisan -->

---

* Mauvaise utilisation de l'agilité 
* Flaccid Scrum (Martin Fowler 2009)
** no quality, no practicle technique
---

###  In a software product, the most important deliverable is the code  itself

---
![bg left:33%](./img/question.jpeg)
<br>
###  Why Better Code is so important?
---

![bg contain](./img/debt.jpg)

---
![bg left:33%](./img/desordre.jpg)
## The Invisible Threat


![width:400px](./img/coc.svg)
- Software Entropy
    - Complexity
    - Technical Debt

<!-- Parallèle avec analyse statique de code
qui calcule une dette technique alors que c'est plutot 
le nombre de faute d'orthograpge !->


<!-- "tendance naturelle d'un système à se désordonner"
* parler de Sonar
-->

---

# Software Crafsmanship


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


<!-- les sociétés choisissent cherchent uniquement un coût -->

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
<!-- Complexité de comprendre le business
les seules spécificaitons non ambigues sont le code
-->

---
<!--
# Définitions
>Software craftsmanship is an approach to software development that emphasizes the coding skills of the software developers.
>It is a response by software developers to the perceived ills of the mainstream software industry, including the prioritization of financial concerns over developer accountability
*Wikipedia*

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

---
- Be responsible & professionnal
<!-- pour nous et le clien -->
- Learn how to say no & provide options

<!-- parler d'estimation -->
<!-- On n'a pas le temps -->
<!-- vaincre le syndrome du héros -->
<!-- Trouver des anesdotes -->

--- 
- Never stop learning and improving his craft
- Share your knowledges
<!-- dans l'équipe, dans la société, conférence ... -->
<!-- ici on montre que tous les développeurs sont différents -->




---

### Technical Practices



---
![bg left:50%](./img/clean_code.jpg)


Clean code is code that is easy to understand and easy to change.

<!-- Chaque morceau de code doit exprimer son intention
Pourquoi est-ce important:
* On passe 10 fois plus de temps à lire du code qu'à en écrire
* C'est être responsable de laisser un code propore: 
Pour les autres mais aussi pour nous.
-->
--- 
#### Clean Design?
* Simple Desgin (XP)
    * Runs all the tests
    * no duplicate code
    * clearly express intent 
    * YAGNI and KISS principle
* SOLID principles
    * Single responsability
    * Open/Closed
    * Liskov Subsitution
    * Interface Segregation
    * Dependency Inversion

---
![bg left:33%](./img/pair.png)
### Pair/Mob Programming

* Immediate feedback loop
* Better and cleaner code
* Collective ownership
* Share knowledge

--- 
![bg contain](./img/pair.jpg)

<!--
Parler de collective ownership
-->


---
### Test Automation Strategy

* feedback loop
* pyramid des tests
* TDD/ATDD/BDD
<!-- pas besoin de test , j'ai déjà testé et ca marche -->
<!-- On n'a pas besoin de TU -->


---

![bg contain](./img/tdd.jpg)

---
![bg contain](./img/tdd2.jpeg)


---
Coding Dojo, Kata
<!-- // avec le pianiste -->

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

---
![bg left:33%](./img/def.jpg)
#### Software Craftsmanship: A Mindset
<!-->>It's a mindset where software developpers choose to be responsible for their own carreers, constantly bettering themselves.-->
<!-- OK notre métier est mal compris, mais c'est à nous de l'expliquer et de dire non. A nous de prendre le temps de s'améliorer et de se formet. A nous de ne pas accepter d'introduire une dette technique non acceptable -->

>Software Craftsmanship is all about putting responsibility, professionalism, pragmatism, and pride back into software developpement.
*Sandro Mancuso, The Software Craftsman, 2014*

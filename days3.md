# Days 3

## ![Alt Text](./articleImg/3.png)

---

<!-- FRENCH: -->

Avec le V8 de Google, c'est l'inline caching qui sauvegarde ça dans un coin pour empêcher la répétition du code et donner directement accès au résultat. Par exemple, si je fais une boucle.

```javascript
    function hello(total) {
    console.log(`Number ${total}`);
    }

    for (let i = 1; i <= 5; i++) {
    hello(i);
    }
```
 Au lieu de lire à chaque fois ma fonction dans la boucle, le cache va directement afficher le résultat !


En programmation, il faut apprendre à coder proprement afin d'optimiser son code ou le compiler. Par exemple, l'intelligence du V8 de Google peut être ralentie si on fait :

```javascript
var humain = function (cheveux, yeux) {
    this.cheveux = cheveux;
    this.yeux = yeux;
} 

var man1 = new humain();
var man2 = new humain(); 

man1.bouche = true;
man1.main = true;

man2.main = true;
man2.bouche = true;
```

Le fait d'avoir changé l'ordre de déclaration va ralentir notre compilateur, car il aura déjà pris une 'habitude' dès la première déclaration. Voilà pourquoi il faut coder proprement et comprendre les choses en profondeur.


---
<!-- ENGLISH : -->
With Google's V8, it's **inline caching** that saves it on the side to prevent code repetition and provide direct access to the result. For example, if I have a loop:

```javascript
    function hello(total) {
    console.log(`Number ${total}`);
    }

    for (let i = 1; i <= 5; i++) {
    hello(i);
    }
```

Instead of reading the function every time in the loop, the cache will directly display the result!

In programming, it is important to learn to code cleanly in order to optimize one's code or compile it. For example, the intelligence of Google's V8 can be slowed down if we do the following:

```javascript
var human = function (hair, eyes) {
    this.hair = hair;
    this.eyes = eyes;
} 

var man1 = new human(); 
var man2 = new human(); 

man1.mouth = true;
man1.hand = true;

man2.hand = true;
man2.mouth = true;
```

Changing the declaration order like this will slow down our compiler because it will have already formed a 'habit' from the first declaration. That's why it is important to code cleanly and understand things in depth.

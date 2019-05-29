# Projet Tim Berners-Lee

Le fichier html comporte trois bloc dans le body

- Un bloc header qui contient : 
    - Une image (img)
    - Deux titre (h1,h3)
    - Un paragraphe (p)
    - Un lien (a) 
- Un bloc nav qui contient : 
    - Une liste désordonée (ul)
    - Trois line vers les réseaux sociaux 
- Un bloc article qui contient :
    - Un titre qui contient un mot marqué (h2,mark)
    - 3 bloc film (div class="movie") 

## Le bloc header

Le bloc header contient la plupart des information ***importante***
de Tim Berner-Lee, il doit donc être ***au-dessus de tout les autre contenu.***

```html
<img src="image/Tim-Berner.jpg" alt="Tim Berner">
<h1>Tim Berners-lee</h1>
<h2>Inventor of HTML</h2>
<p>
    Tim Berners-Lee is the <strong>inventor</strong> of the Web. In 1989, Tim was working in a computing services section of CERN when he came up with the concept,
    at the time he had no idea that it <strong>would be</strong> implemented on such an <strong>enormous scale</strong>
</p>
<a href="https://fr.wikipedia.org/wiki/Tim_Berners-Lee" target="_blank">See for yourself</a>
```

Le header contient ***l'image de Tim-Berners*** Lee ainsi que son nom en
h1 et ce qu'il a créer en h2.

```html
<img src="image/Tim-Berner.jpg" alt="Tim Berner">
<h1>Tim Berners-lee</h1>
<h2>Inventor of HTML</h2>
```
 
Le p est ***un petit descriptif*** pour le présenter.

```html
<p>
    Tim Berners-Lee is the <strong>inventor</strong> of the Web. In 1989, Tim was working in a computing services section of CERN when he came up with the concept,
    at the time he had no idea that it <strong>would be</strong> implemented on such an <strong>enormous scale</strong>
</p>
```
 
Le lien qui ***redirige sur la page wikipedia*** de Tim Berners-Lee.

```html
<a href="https://fr.wikipedia.org/wiki/Tim_Berners-Lee" target="_blank">See for yourself</a>

```

## Le bloc nav

Le bloc nav contient tous les ***réseaux sociaux*** mais il ne redirige sur rien.

```html
<nav>
    <ul>
        <li>
            <a href="#sqd" class="fab fa-facebook-f"></a>
            <p>Facebook</p>
        </li>
        <li>
            <a href="#sqd" class="fab fa-linkedin-in"></a>
            <p>LinkedIn</p>
        </li>
        <li>
            <a href="#sqd" class="fab fa-twitter"></a>
            <p>Twitter</p>
        </li>
    </ul>
</nav>
```

Je l'ai ai encapsuler dans ***une liste ul*** et j'ai donc remplis la liste des lien redirigeant vec des réseaux sociaux

```html
<ul>
    <li>
        ...
    </li>
    <li>
        ...
    </li>
    <li>
        ...
    </li>
</ul>
```

Les lien sont structurer de façon a ce que ***Le p fasse un saut a la ligne*** et que le lien se trouve ***juste au-dessus du p***

### Le lien facebook

```html
<a href="#sqd" class="fab fa-facebook-f"></a>
<p>Facebook</p>
```

### Le lien linkedin

```html
<a href="#sqd" class="fab fa-linkedin-in"></a>
<p>LinkedIn</p>
```

### Le lien twitter

```html
<a href="#sqd" class="fab fa-twitter"></a>
<p>Twitter</p>
```

## Le bloc article

le bloc article contient ses préférence en matière de film, c'est un bloc qui ***n'est pas important***

```html
<article>
    <h3><mark class="markup">His</mark> favorite movies</h3>
    <div class="movie">
        <img src="image/space-odyssey.jpg" alt="">
        <div class="movieDesc">
            <h2>2001 - Space Odyssey</h2>
            <p>Humanity find a mysterious, obvously artificial, object buried beneath the Lunar surface and, with the intelligent computer H.A.L. 9000, sets off on a quest</p>
        </div>
    </div>
    <div class="movie">
        <img src="image/vacance-hulot.jpg" alt="">
        <div class="movieDesc">
            <h2>Monsieur Hulot</h2>
            <p>Monsieur Hulot comes to a beachside hotel for a vacation, where he accidentally (but good-naturedly) causes havoc</p>
        </div>
    </div>
    <div class="movie">
        <img src="image/alien.jpg" alt="">
        <div class="movieDesc">
            <h2>Alien</h2>
            <p>
                The commercial vessel Nostromo receives a distress call from an unexplored planet. After searching for survivors, the crew heads home only to realize
                that a deadly bioform has joined them.
            </p>
        </div>
    </div>
</article>
```

J'ai mis un titre en h3 car le contenu ne semblait pas important et que la police d'écriture conrespondait

```html
<h3><mark class="markup">His</mark> favorite movies</h3>
```

Les bloc movie sont structuré de la même façon pour pouvoir stylisé cela en css plus rapidement et que la structure sois lisible et beau a lire.

```html
<div class="movie">
    <img src="image/space-odyssey.jpg" alt="">
    <div class="movieDesc">
        <h2>2001 - Space Odyssey</h2>
        <p>Humanity find a mysterious, obvously artificial, object buried beneath the Lunar surface and, with the intelligent computer H.A.L. 9000, sets off on a quest</p>
    </div>
</div>
<div class="movie">
    <img src="image/vacance-hulot.jpg" alt="">
    <div class="movieDesc">
        <h2>Monsieur Hulot</h2>
        <p>Monsieur Hulot comes to a beachside hotel for a vacation, where he accidentally (but good-naturedly) causes havoc</p>
    </div>
</div>
<div class="movie">
    <img src="image/alien.jpg" alt="">
    <div class="movieDesc">
        <h2>Alien</h2>
        <p>
            The commercial vessel Nostromo receives a distress call from an unexplored planet. After searching for survivors, the crew heads home only to realize
            that a deadly bioform has joined them.
        </p>
    </div>
</div>
```

### Le film space odyssey

```html
<div class="movie">
    <img src="image/space-odyssey.jpg" alt="">
    <div class="movieDesc">
        <h2>2001 - Space Odyssey</h2>
        <p>Humanity find a mysterious, obvously artificial, object buried beneath the Lunar surface and, with the intelligent computer H.A.L. 9000, sets off on a quest</p>
    </div>
</div>
```

### Le film Monsieur Hulot

```html
<div class="movie">
    <img src="image/vacance-hulot.jpg" alt="">
    <div class="movieDesc">
        <h2>Monsieur Hulot</h2>
        <p>Monsieur Hulot comes to a beachside hotel for a vacation, where he accidentally (but good-naturedly) causes havoc</p>
    </div>
</div>
```

### Le film Alien

```html
<div class="movie">
    <img src="image/alien.jpg" alt="">
    <div class="movieDesc">
        <h2>Alien</h2>
        <p>
            The commercial vessel Nostromo receives a distress call from an unexplored planet. After searching for survivors, the crew heads home only to realize
            that a deadly bioform has joined them.
        </p>
    </div>
</div>
```
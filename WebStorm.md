# WebStorm

table>tr*2>td*3
```
<table>
    <tr>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td></td>
        <td></td>
        <td></td>
    </tr>
</table>
```
p>lorem
```
<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Animi consectetur debitis dolorum maxime nesciunt,
    obcaecati odio recusandae. Aperiam earum inventore quidem. Asperiores cupiditate dolores impedit libero natus
    obcaecati reprehenderit unde?</p>
```
p>lorem200
```
<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ab accusantium architecto consectetur cupiditate, dicta
    dolore doloribus eius eos illo ipsum iusto, magnam neque nesciunt nobis officiis pariatur quia, repellendus tempore
    voluptate voluptatum. Doloribus enim illum ipsa natus nemo officiis optio sit tempora temporibus tenetur. Cum
    deserunt distinctio eum eveniet id impedit, labore laboriosam nulla recusandae tenetur. Ex numquam officia optio
    placeat! Nesciunt nulla, perferendis. Ad adipisci animi asperiores aut commodi deserunt distinctio dolore doloremque
    dolorum eligendi, eveniet excepturi expedita facere inventore ipsam iste magni minus natus, officiis omnis quae
    quaerat quidem quisquam sapiente sed sint soluta tempore unde vel veritatis? Cupiditate eveniet fuga mollitia
    perferendis sint ullam voluptate voluptatibus! Doloribus ipsa quas sapiente voluptate. Adipisci esse fugit iusto
    sequi tenetur veniam? Exercitationem iusto odio pariatur quaerat quos, voluptates. Ad aliquam corporis, dicta
    doloribus, est, excepturi exercitationem impedit libero modi nam nihil non numquam quidem suscipit voluptatum! Ad
    amet, animi aperiam aut commodi corporis dicta dolor, ducimus ea ex hic illo impedit iusto labore laborum minus modi
    mollitia non nulla odio omnis pariatur quae quam quis quod ratione saepe sapiente sed similique sint unde, veritatis
    vitae voluptatibus. Aliquid animi blanditiis cum deleniti, doloremque ducimus eligendi necessitatibus non placeat
    quaerat, reprehenderit tenetur.</p>
```
a
```
<a href=""></a>
```
h2{lorem5}+p>lorem20
```
<h2>lorem5</h2>
<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Blanditiis dolorem doloribus ea earum fugiat id quia.
    Cumque dolore sequi ullam!</p>
```
h1#toto
```
<h1 id="toto"></h1>
```
a[target="_blank"]
```
<a href="" target="_blank"></a>
```
CTRL + ALT + L : formate le code

div{block $}*3
```
<div>bloc 1</div>
<div>bloc 2</div>
<div>bloc 3</div>
```
la position d'un élément en css est toujours par rapport à la gauche. au lieu de chercher dans un code existant ou se trouve le positionnement de l'élément, il faut ajouter un top:auto / left:auto afin de reset la position. Ensuite on peut utiliser les éléments right sans probléme.

z-index -> change couche du bloc

### position
absolute : par rapport au parent non static le plus proche
fixed : par rapport à la fenêtre
relative : par rapport au parent
static : type de base

## Balises
Balise input : Si pas de type, le type par défaut est text
Autre type : radio - checkbox - email - password - color - url - tel - number - range - time - date - datetime-local - month - week

### Résolution 
72dpi = 1pt = 1px

### BLOCK
```
<header></header>
<main></main>
<footer></footer>
<article>
    <section></section>
</article>
<nav></nav>
<aside></aside>
<h1></h1>
<p></p>
<ul>
    <li></li>
</ul>
<ol>
    <li></li>
</ol>
<blockquote></blockquote>
<div></div>
<hr/>
<br/>
<figure>
    <figcaption></figcaption>
</figure>
```
### INLINE
```
<a></a>
<b></b>
<strong></strong> donne de l'importance dans le référence
<i></i>
<em></em> emphase > i
<mark></mark> surligné
<span></span>
<q></q> citation courte
```
### INLINE-BLOCK
```
<img></img>
<audio></audio>
<video></video>
<input>
<textarea></textarea>
<select></select>
<button></button>
```

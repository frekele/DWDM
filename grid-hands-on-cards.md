# Galeria com cards


```html

    <h1>My Awesome Shots</h1>

    <main>
        <div class="card">
            <div class="info">
                <strong class="title">My Title</strong>
                <p class="desc">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia consectetur sapiente ipsam nihil velit quae ab unde quasi exercitationem esse</p>        
            </div>
            <img src="http://freeaussiestock.com/free/Victoria/Melbourne/slides/fed_square.jpg">
        </div>
        <div class="card">
            <div class="info">
                <strong class="title">My Title</strong>
                <p class="desc">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia consectetur sapiente ipsam nihil velit quae ab unde quasi exercitationem esse</p>        
            </div>
            <img src="https://media.defense.gov/2013/Jul/16/2000032379/-1/-1/0/130628-F-DQ639-002.JPG">
        </div>
        <div class="card">
            <div class="info">
                <strong class="title">My Title</strong>
                <p class="desc">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia consectetur sapiente ipsam nihil velit quae ab unde quasi exercitationem esse</p>        
            </div>
            <img src="https://s0.geograph.org.uk/geophotos/03/25/64/3256477_ec7d83ab.jpg">
        </div>
        <div class="card">
            <div class="info">
                <strong class="title">My Title</strong>
                <p class="desc">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia consectetur sapiente ipsam nihil velit quae ab unde quasi exercitationem esse</p>        
            </div>
            <img src="http://freeaussiestock.com/free/Victoria/Melbourne/slides/melbourne_museum_roof.jpg">
        </div>
        <div class="card">
            <div class="info">
                <strong class="title">My Title</strong>
                <p class="desc">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia consectetur sapiente ipsam nihil velit quae ab unde quasi exercitationem esse</p>        
            </div>
            <img src="https://live.staticflickr.com/2387/1726578675_62f09cb233_z.jpg">
        </div>
        <div class="card">
            <div class="info">
                <strong class="title">My Title</strong>
                <p class="desc">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia consectetur sapiente ipsam nihil velit quae ab unde quasi exercitationem esse</p>        
            </div>
            <img src="https://s0.geograph.org.uk/geophotos/04/31/24/4312454_79d0a1d8.jpg">
        </div>
    </main>
 ```

```css
body, html {
  height: 100%;
}

body {
  margin: 0;
  font-family: 'Montserrat';
}

h1 {
  margin: 5rem;
}

main {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(19rem, 1fr));
  cursor: pointer;
}
main .card {
  transition: transform 1s;
}
main .card:nth-of-type(1) {
  background: #f8f8f8;
}
main .card:nth-of-type(2) {
  background: #eeeeee;
}
main .card:nth-of-type(3) {
  background: #fafafa;
}
main .card:nth-of-type(4) {
  background: #cfcfcf;
}
main .card:nth-of-type(5) {
  background: whitesmoke;
}
main .card:nth-of-type(6) {
  background: #d4d4d4;
}
main .card:hover {
  transform: translateY(-10px);
}
main .card .info {
  padding: 1rem;
}
main .card img {
  width: 100%;
}
main .card .desc {
  color: gray;
}

```


#REF

https://www.youtube.com/watch?v=bam83Xv4VMA

https://andy-bell.design/wrote/create-a-responsive-grid-layout-with-no-media-queries-using-css-grid/

https://drafts.csswg.org/css-grid/#auto-repeat

https://codepen.io/designcourse/pen/mYrxKr


Mais meterial sobre FR
https://medium.com/flexbox-and-grids/the-css-fractional-unit-fr-in-approachable-plain-language-fdc47bd387f7

https://hackernoon.com/understanding-css-grids-fractional-units-fr-the-easy-way-5f43ee008f29

https://alligator.io/css/css-grid-layout-fr-unit/

https://css-tricks.com/introduction-fr-css-unit/
https://css-tricks.com/introduction-fr-css-unit/

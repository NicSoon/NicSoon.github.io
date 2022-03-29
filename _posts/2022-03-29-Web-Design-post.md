Learning about how to fit our webpage when use on a mobile device, tablet, gaming console and even wearables. Exciting stuff.

Media queries enable us to create a responsive experience where specific styles are applied to small screens, large screens, and anywhere in between.

Break point is the limit where the screen changes.

```html

Media query demo


HTML

<div class="box"></div>
<main class="grid">
  <div class="item"></div>
  <div class="item"></div>
  <div class="item"></div>
</main>
```
````css
CSS

.box {
  background-color: lightblue;
  aspect-ratio: 16/4;
  
}
.grid{
  display:grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-gap: 30px;
}
.item{
  aspect-ratio: 1/1;
  background-color: teal;
}

<--! If statement (if media screen was 400px for example) -->
<--! New css file called responsive.css is created for this exercise -->

@media screen and ( max-width: 400px ) {
    .logo {
        width: 60px;
        margin: 5px auto;
        display:block;
    }
    .navigation {
        text-align: center;
    }
    .banner {
        aspect-ratio: 1/1;

    }
    .banner h1 {
        font-size: 150%;
    }
    .content {
        grid-template-columns: 1fr;
        margin: 30px 10px;
    }
    .card h3 {
        text-align: center;
    }
}  


<meta name="viewport" content="width=device-width, intial-scale=1">

````

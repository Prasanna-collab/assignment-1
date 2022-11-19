# Frontend Mentor - 2 side card

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.fro
qr-code-component-iux_sIO_H). 


### Screenshot

![](./images/screenshot.jpg)
SCREENSHOT OF THE DESKTOP VIEW OF WEBSITE.

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Display

### What I learned

With this work I learnt about,
  1. FLEX Property
  2. MEDIA QUERY

  Here the code snippets I used for this project.

```html
<div class='container'>
    <div class = 'items'>
        
        <div class = 'item first'>
            <h2 class='heading'> The Great <span style='color: hsl(277,64%,61%);'>Indian Sale </span> is on Now!! </h2>
            <p class='para'> Visit your nearest Fashion hub merchandise and own your designs. </p>
            <div class = 'statistics'>
                <div class='one'>
                <div> 10k+</div>
                <p> Companies</p>
                </div>
                    <div class='one'>
                <div> 374</div>
                <p> Templates</p>
                </div>
                    <div class='one'>
                <div> 12M+</div>
                <p> Queries</p>
                </div>
            </div>
        </div>
        <div class= 'item second'>
            <div class='sale-image'></div>
        </div>
        
        
    </div>
</div>
```
```css
@import url('https://fonts.googleapis.com/css2?family=Island+Moments&family=Raleway:ital,wght@0,100;1,200&family=Rubik+Bubbles&display=swap');

.sale-image{
	background: url(https://thumbs.dreamstime.com/b/new-year-s-sale-clothing-store-discounts-new-year-s-sale-clothing-store-discounts-103607006.jpg), hsl(277, 64%, 61%);
	background-blend-mode: luminosity;
	height: 18rem;
	width: 30rem;
	background-size: cover;
	background-position: center;
	background-repeat: no-repeat;
	border-radius: 5px;
    
}

.items{
    display: flex;
    width: 100%;
    
    align-items: center;
    justify-content: center;
    margin-left: 2rem;
    margin-right: 2rem;
    height:100vh;
    
}
.statistics{
    display: flex;
    justify-content: space-between;
    gap: 2rem;
    
}
.one div{
	font-family: 'Raleway', sans-serif;
	color: hsl(277, 64%, 61%);
	font-size: 2rem;
}
.one p {
	font-family: 'Raleway', sans-serif;
	color: hsl(277, 64%, 61%);
	font-size: 0.5rem;
}

.heading{
	text-align:left;
	font-family: 'Raleway';
	font-size: 2rem;
}
.para{ 
text-align:left;
	font-family: 'Island Moments';
    font-size:1.5rem;
}
.first{
   
    width: 30rem;
    min-height: 18rem;
    padding-left: 0.5rem;
    background-color: rgb(250, 250, 250);
    line-height: 2rem;
}
.second{
   
   
    background-color: rgb(250, 250, 250);
}


@media (max-width: 650px){
    .items{
        display: flex;
        flex-direction: column-reverse;
    }
    .first{
        text-align: center;
        min-height: auto;
    }
    .sale-image{
        background: url(https://thumbs.dreamstime.com/b/new-year-s-sale-clothing-store-discounts-new-year-s-sale-clothing-store-discounts-103607006.jpg), orchid;
        background-blend-mode: luminosity;
}
.statistics{
    display: flex;
    flex-direction: column;
    gap: 2rem;
    text-align: center;
}
}

```
### Continued development

1. Planning to upgrade this card design to make as personal portfolio.

## Author

- Website - [Prasanna](https://www.linkedin.com/in/prasanna-rajendran)
- Frontend Mentor - [@Prasana-collab](https://www.frontendmentor.io/profile/Prasanna-collab)

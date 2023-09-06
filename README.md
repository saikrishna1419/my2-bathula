# my2-bathula
This is my second repo created to complete course assignments.<br>
# Sri Sai Krishna Bathula<br>
### My favorite vacation spot is Hoskote in Bangalore.<br>
My favorite vacation spot is **Hoskote**, located in Bangalore, Karnataka state, India. I often go for bike rides with my **friends** in cold weather, wear jackets and enjoy the cool breeze while riding, and go to eat hoskote mani dum **biryani** at *4am*. 


***
### Activites and Food Dishes
#### Activities I do at my favorite vacation spot.
1. Enjoy the view.
2. Bike ride rod ghat roads.
3. Photoshots.

#### A list of food dishes can be found at my favorite place.
* Goat Biryani.
* Chicken Kabob.
* Goat Paya.

[Interesting facts about Sai krishna](https://github.com/saikrishna1419/my2-bathula/blob/main/MyStats.md)

---
### Sports I recommend others try
Here are some sports I recommend trying. Each of these sports offers unique benefits and improves your physical and mental strength.

| Sport | Reason | Average time spend weekly |
|:-------|:--------|:---------------------------|
|Cricket|This is the most commonly played Sport in all countries| 4 - 5 Hours
|Tennis|This another you can play. After playing this game you feel more active throughout the day| 5 - 6 Hours|
|Basket Ball| You can burn for calories. Improve balance and Co-ordination.|3 - 5 Hours|
|Foot Ball|In this game you need run more this helps to improve your heart health and blood pressure. It Improves your concentration.| 4 - 5 Hours|

---
## Pithy Quotes
> "Imagination is more important than knowledge." - *Albert Einstein*<br>
> "The present is theirs; the future, for which I really worked, is mine." - *Nikola Tesla*<br>
> "I do not think you can name many great inventions that have been made by married men." - *Nikola Tesla*

---
>How to create a responsive menu(Hamburger menu)
>[Click here](https://stackoverflow.com/questions/36310655/how-to-create-a-responsive-menuhamburger-menu)


```CSS
.hamburger {
  cursor: pointer;
  position: absolute;
  width: 48px;
  height: 48px;
  transition: all 0.25s;
}

.hamburger__top-bun,
.hamburger__bottom-bun {
  content: '';
  display: block;
  position: absolute;
  left: 15px;
  width: 18px;
  height: 1px;
  background: #fff;
  transform: rotate(0);
  transition: all 0.25s;
}

.hamburger:hover [class*="-bun"] {
  background: #999;
}

.hamburger__top-bun {
  top: 23px;
  transform: translateY(-3px);
}

.hamburger__bottom-bun {
  bottom: 23px;
  transform: translateY(3px);
}

.open {
  transform: rotate(90deg);
}

.open .hamburger__top-bun {
  transform: 
    rotate(45deg) 
    translateY(0px);
}

.open .hamburger__bottom-bun {
  transform: 
    rotate(-45deg) 
    translateY(0px);
} 
```

```JavaScript
$('.hamburger').click (function(){
  $(this).toggleClass('open');
});

```

[Snippet Source](https://css-tricks.com/snippets/css/apple-com-hamburger-bun-menu/)
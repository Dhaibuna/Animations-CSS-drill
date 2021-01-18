# Animations CSS - Drill 

Drill exercices showing animation realised at Becode during **promo Jepsen 4.27**

[Ceci est un lien vers trois rectangles animés](https://dhaibuna.github.io/Animations-CSS-drill/)

## Exercice A 

I simply put a transition on my first box, which is also applied for my second and third block:     

.box:nth-of-type(1), :nth-of-type(2), :nth-of-type(3)   
{                    
    transition: 1.5s;                   
}        

## Exercice B 

I put a  transform:scale which make my div grows 30% of its original size

.box:nth-of-type(2):hover     
{   
    transform: scale(1.3);  
}

## Exercice C 

I put a transform translate which make my div moves from original position to right of 50% on the X axis 

.box:nth-of-type(3):hover     
{   
    transform: translateX(50%);        
}   
# ERP-base
An ERP project for apparel industry written by PHP
Start from the night on FEB. 4th, go throug the tutorial for newcomer, big surprised at what I see.

fixed element's width
this is the first problem I met. Once the element is fixed, it's position and width are relative with the screen, not the parent container. For element's width, when we define it with percentage, we have to be careful to calculate it right. The case in my script is,
screen: 1266px for width; body: 960px for width, the width for <header>element I want to make it fixed is 75.8%.

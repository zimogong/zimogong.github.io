---
layout: post
title: Study Notes on Daniel Kleppner’s "An Introduction To Mechanics"
date: 2024-08-14 15:19:00 +0800
math: true
categories: [Physics]
tags: [Mechanics, Notes]
---

There are my own solutions for the exercise problems in the book

* 1.12:  
Choosing the z axis vertically upward,We have $\ddot{z}(t)=-g$. If the body is releasing at t = 0 with initial velocity $v_0$, we have a quadratic equation with respect to time $t$: $\ \ z=z_0+v_0t-\frac{1}{2}gt^2$.  
Without loss of generality, let $z_0$ = 0, the equation is  
$\ \ z=v_0t-\frac{1}{2}gt^2$  
When $z=A$, we get $A=v_0t-\frac{1}{2}gt^2$, then  
$\ \ gt^2-2v_0t+2A=0 $,  
and we can get $t_{A1}$ and $t_{A2}$, the two roots of the above equation.  
Now, looking at the diagram in 1.12, we see that  
$\ \ T_A=|t_{A1}-t_{A2}|=\frac{\sqrt{4v_0^2-8gA}}{g}$.    
Similarly, let $z=B$, we get  
$\ \ gt^2-2v_0t+2B=0 $  
and  
$\ \ T_B=|t_{B1}-t_{B2}|=\frac{\sqrt{4v_0^2-8gB}}{g}$.   
Thus, $(T_A)^2 -(T_B)^2=\frac{8g(B-A)}{g^2}$.  
Because $B-A=h$, $(T_A)^2 -(T_B)^2=\frac{8h}{g}$.  
Isolating $g$, we have: $g=\frac{8h}{(T_A)^2-(T_B)^2}$.

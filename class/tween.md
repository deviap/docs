---
title: tween
description: Documentation of tween class.
published: true
tags: 
---

## Purpose

Tweening is when you generate intermediate steps be*tween* a starting goal and end goal. It's useful for animating or otherwise making smooth transitions. So, this service is provided to allow you to tween tevObjects.

## Easings

Easings are how the intermediate steps are generated. By default, they're generated linearly (easing = "linear"). However, there are many kinds of easings avaliable to you.

The first part of the easing's name indicates the direction the easing has. The second part will tell you how style of the easing. For example, a valid tweening name would be `inExpo`. The first part tells you the direction is `in` and the second part tells you the style is `expo`ential.

| Directions | Description |
| --- | --- |
| in | The size of each step starts at 0 unit, then increases over time. |
| out  | The size of each step starts at 1 unit, then decreases over time. |
| inOut | The size of each step starts at 0 and increases over time. Then, it peaks at the middle of the tween and decreases over time. |
| outIn | The size of each step starts at 1 and decreases over time. Then, it peaks at the middle of the tween and start to increase over time.

| Styles | Description |
| --- | --- |
| linear | Linear steps to goal. |
| quad |  Quadratic steps to goal. |
| cubic | Cubic steps to goal. |
| quart | Similar to quad, but at a faster increase in rate.  |
| quint | Similar to quad, but at a slower increase in rate. |
| sine | ? |
| expo | Expotential steps to goal. |
| circ | ? |
| elastic | ? |
| back | ? |
| bounce | ? |

# AdventuresInSVG

Experimenting with SVG animation

# What & why?

For a while now I've been a little fascinated with SVGs and the ability to animate them, mainly thanks to [@benfoxall](https://github.com/benfoxall) and [this repo](https://github.com/benfoxall/logo-hacks).

I wanted to find out how semi-complex animations could be achieved and try and pick the "best" way of doing it. 

Here are my results so far...

# Animating with JavaScript

See: [AnimatingWithJavaScript.html](http://averagemarcus.github.io/AdventuresInSVG/AnimatingWithJavaScript.html)

```diff 
+ Easy to change the routine of the animation
+ The timings can be changed on-the-fly
- A bit of CSS is needed to achieve it easily
- May not perform well on load-end devices if the amount of work done in JS is large
```
# Animating with CSS

See: [AnimatingWithCSS.html](http://averagemarcus.github.io/AdventuresInSVG/AnimatingWithCSS.html)

```diff
+ Few lines of code needed to animate something
+ Animations are smooth
- Timings are hard and not very flexible.
- Cannot change the timing on-the-fly
```

# Animating with Promises (JS)

See: [AnimatingWithPromises.html](http://averagemarcus.github.io/AdventuresInSVG/AnimatingWithPromises.html)

*Note:* I used [Q](https://github.com/kriskowal/q) for this.

```diff
(All the same as JS above)
+ Timings between animations can be varied
+ Nice, easy to read syntax
- Much more code
```

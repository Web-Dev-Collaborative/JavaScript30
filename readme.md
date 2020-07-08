![](https://javascript30.com/images/JS3-social-share.png)

# JavaScript30

I've decided to brush up on some JavaScript while also learning new JS capabilities I may not have come across before by doing [Wes Bos's](https://twitter.com/wesbos) course, [JavaScript30](https://javascript30.com).

I will trying to complete each day's challenge before watching the tutorial, then comparing my solution to Wes's solution.

This repo was forked from [wesbos/JavaScript30](https://github.com/wesbos/JavaScript30).

Commit tweet: https://twitter.com/jackdomleo7/status/1280791338921984001

You can see my progress below.

---

## Day 1: Drum kit

8th July 2020

Fairly cool, simple program. I learned about the [`transitionend`](https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement/transitionend_event) which I can see be very beneficial rather than using `setTimeout` because it hooks onto the CSS `transition` value. Also learned how to play sounds, but I can never find a decent website where you can download really simple useful sounds 🤔.

My method was different the Wes's, because Wes used `function playSound() { }`, where I instead used `const playSound = () => { }`. My initial method used `setTimeout`, but Wes's demo on the `transitionend` event was so useful.

**Link**: https://jackdomleo7.github.io/JavaScript30/01-javascript-drum-kit

**Code**: https://github.com/jackdomleo7/JavaScript30/tree/master/01-javascript-drum-kit

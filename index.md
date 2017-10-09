---
layout: page
title: home
---

<style>
  @import url('https://fonts.googleapis.com/css?family=Josefin+Sans:100|Text+Me+One');

  h2.class-header {
    background-color: rgba(19, 37, 62, 1);
    color: white;

    font: 4.5rem/1em 'Text Me One', sans-serif;
    text-transform: uppercase;
    text-align: center;

    padding: 1.5rem;
    padding-top: 3rem;
    position: relative;
    z-index: -1;
  }

  .class-header .small {
    display: block;
    font: lighter 1.5rem/1.3em 'Josefin Sans', sans-serif;
  }

  .class-header:before, .class-header:after {
    content: '';
    display: block;
    position: absolute;
    background: url('img/wires.svg') -15px -11px/cover no-repeat padding-box;
    top: 0;
    height: 100%;
    width: 250px;
    z-index: -2;
  }

  .class-header:before {
    left: 0;
  }

  .class-header:after {
    right: 0;
    transform: rotateY(180deg);
    background-position-y: 39px;
  }
</style>

<h2 class="class-header">
    WPI Data Science
    <span class="small">wpids</span>
</h2>

Welcome to WPI Data Science

### Announcements

- Check out the [WPI DS Minor](minor.md)

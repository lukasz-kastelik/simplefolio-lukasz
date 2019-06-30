## Simplefolio is a Open Source, Fully customizable Beautiful Portfolio Template
Built with HTML5, Sass, Bootstrap 4, Webpack and more!

To view a live demo, **[click here](https://simplefolio.netlify.com/)**

This repo is an easily customizable personal portfolio template. Feel free to use it as-is or customize it as much as you want. I wanted to build a clean, beautiful and simple template without any unnecessary bloat.

---

Step 1) There are the 5 to fill out your information:
---

**Header** - Edit the `h1` and `p` in the jumbotron-text `div`
```
<div class="jumbotron-text">
  <h1>Brandon Morelli</h1>
  <p>Full-Stack Web Developer in Boston, Ma.</p>
</div>
```
---
**About** - Edit the `h2` and `p`, or add more, in the main-content `div`
```
<div class="main-content">
  <div class="content-header">
    <a class="anchor" name="about"></a>
    <h2>About</h2>
  </div>
  <div class="content-body">
    <p>text here</p>
    <p>text here</p>
  </div>
</div>
```
---
**Portfolio** - Experiences are organized in content-body `div`. There is an `h4` and a `p` that you can edit.
```
          <div class="content-body">
            <div class="card">
              <div class="card-header">
                <h4>Company <span class="job-title">Job Title</span></h4>
              </div>
              <div class="card-content">
                <p>Paragraph text</p>
              </div>
            </div>
```
---
**Contact** - Simply cahnge the `address` to include your email address
```
<form method="POST" action="https://formspree.io/email@email.com">
```
---
**Footer** - content-body `div` with an editable `p`
```
          <div class="content-body">
            <p>Copyright YOUR NAME 2017</p>
          </div>
```
---

Step 2) Change the color theme:
---

**Header** - Edit the `h1` and `p` in the jumbotron-text `div`
```
<div class="jumbotron-text">
  <h1>Brandon Morelli</h1>
  <p>Full-Stack Web Developer in Boston, Ma.</p>
</div>
```
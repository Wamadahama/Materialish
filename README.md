# Materialish
![SLiMG Image](https://i.sli.mg/n5CnGT.png)

Material like CSS styles. This is not exhaustive to [Google's material design guidelines ](https://material.google.com/) nor is a complete CSS framework. This is just a set of style
to make up some material components that I commonly use.
## About
I often find myself rewriting the styles for material cards and paper bodies , so
I have taken my 'material' like CSS styles and coalesced them into one file.

Combine with your favorite CSS frameworks like [Picnic](https://github.com/picnicss/picnic) or [bootstrap](http://getbootstrap.com/) to make it nice and responsive

## Installation  

```sh
git clone https://www.github.com/wamadahama/materialish.git
cd materialish
cp materialish.css /path/to/site
```

Or just copy the materialish.css file to your machine

Add the following line to your ```head```
```html
<link rel="stylesheet" href="/path/to/css/materialish.css" media="screen" charset="utf-8">
```

**A bootstrap sample can be found in the ```samples/``` directory**

## Usage
Will write documentation later

### Header

#### Description
The header is just a simple full width ribbon to put at the top of the document.
This is great for things like a title bar

#### Usage  
```html
<header class="materialish-header" style="background-color:#fff;">
  <!-- Content -->
</header>
```

The default font color will be ```#424242;``` but can be overriden

### Strand

#### Description
This component is useful for a long ribbon of color. This is used to highlight pages and make floating elements pop.

There shouldn't be any content in these.

#### Usage
```html
<div class="materialish-strand" style="background-color:#3F51B5"></div>
```

### Paper body

#### Description

Used for main body content, will center itself on the page and float over strand elements. Width can be overridden

#### Usage

```html
<div class="materialish-paper-body">
  <!-- Content -->
</div>
```

### Medium Card

#### Description
Material paper card

#### Usage
```html
<div class="materialish-card-md">
  <!-- Content -->
</div>
```
TODO:
- Small and large cards
- Card titles


### Footer
Material footer, needs some visual touch ups
```html
<footer class="materialish-footer">

</footer>
```


---

# Sample

## Boilerplate
```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title></title>
  </head>
  <body>

  </body>
</html>
```

## Add reference to materialish
```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Materialish</title>
    <link rel="stylesheet" href="../materialish.css" media="screen" title="no title" charset="utf-8">
  </head>
  <body>
  </body>
</html>
```

## Page Skeleton
```html
<html>
  <head>
    <meta charset="utf-8">
    <title>Materialish</title>
    <link rel="stylesheet" href="../materialish.css" media="screen" title="no title" charset="utf-8">
  </head>
  <body>
    <!-- Page Header -->
    <header class="materialish-header" style="background-color:#fff;">
    </header>

    <!-- Background Strand -->
    <div class="materialish-strand" style="background-color:#3F51B5;"></div>

    <!-- Page body -->

    <div class="materialish-paper-body">
    </div>

    <!-- Footer -->
    <footer class="materialish-footer">
    </footer>

  </body>
</html>
```

## Add Content
```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Materialish Test</title>
    <link rel="stylesheet" href="../materialish.css" media="screen" title="no title" charset="utf-8">
  </head>
  <body>

    <header class="materialish-header" style="background-color:#fff;">
      <h1>Howard Phillips Lovecraft</h1>
    </header>

    <div class="materialish-strand" style="background-color:#3F51B5;"></div>

    <div class="materialish-paper-body">
      <div>
        <em><h2>H.P Lovecraft created a Horrific world to escape a Nihilistic universe</h2></em>
        <blockquote cite="H.P Lovecraft">"We live on a placid island of ignorance in the midst of black seas of infinity, and it was not meant that we should voyage far."</blockquote>
      </div>

      <div>
        <h2>Cosmic Indifference</h2>
        <p>
          Though cosmicism appears deeply pessimistic, H.P. Lovecraft thought of himself as neither a pessimist nor an optimist but rather a "scientific" or "cosmic" indifferentist,
          a theme expressed in his fiction. In Lovecraft's work, human beings are often subject to powerful beings and other cosmic forces,
          but these forces are not so much malevolent as they are indifferent toward humanity.
        </p>
        <hr>
      </div>

      <div>
        <h2>Fate/Hopelessness</h2>
        <p>
          Often in Lovecraft's works the protagonist is not in control of his own actions, or finds it impossible to change course. Many of his characters would be free from danger if they simply managed to run away;
           however, this possibility either never arises or is somehow curtailed by some outside force,
           such as in "The Colour Out of Space" and "The Dreams in the Witch House"
        </p>
        <hr>
      </div>

      <div>
        <h2>Irrelevance of mankind</h2>
        <p>
          Lovecraft made frequent reference to the "Great Old Ones": a loose pantheon of ancient,
          powerful deities from space who once ruled the Earth and who have since fallen into a deathlike sleep.
          This was first established in "The Call of Cthulhu", in which the minds of the human characters deteriorated when afforded a glimpse of what exists outside their perceived reality.
          Lovecraft emphasized the point by stating in the opening sentence of the story that "The most merciful thing in the world, I think, is the inability of the human mind to correlate all its contents."
        </p>
        <hr>
      </div>
      <h3>Sources:</h3>
      <a href="https://en.wikipedia.org/wiki/H._P._Lovecraft">H.P Lovecraft</a><br>
      <a href="https://en.wikipedia.org/wiki/Cosmicism">Cosmicism</a>
    </div>

    <footer class="materialish-footer">
      <div>
        <a href="#foo">Some</a>
        <a href="#bar">Links</a>
        <a href="#bazz">Help</a>
      </div>
    </footer>

  </body>
</html>
```

## Output
<!-- [SLiMG Image](https://i.sli.mg/OVA0gF.png) -->
![Output](https://i.sli.mg/OVA0gF.png)

# Other notes
Samples can be found in the ```samples/``` directory

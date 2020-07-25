![Image description](https://i1.faceprep.in/ProGrad/face-logo-resized.png)

# ProGrad Lab | HTML & CSS - NPM clone

## Learning Goals

In this exercise, the goal is to apply as many as possible of the concepts you've just learned:

- when and how to use different HTML tags,
- how to structure HTML page and add the content to it using _block and inline elements_,
- how to use flexbox to position elements on the page and
- how to style the page.

## Getting started

1. [Fork](https://github.com/FACEPrep-ProGrad/project-builder-html-css-npm) this repo
2. [Clone](https://github.com/FACEPrep-ProGrad/project-builder-html-css-npm) this repo

Whenever you create a first significant change, you should make your first commit.

3. Follow these [guidelines to add, commit and push changes](https://github.com/FACEPrep-ProGrad/general-guidelines-labs-project-builders.git).

In the end of this document, you will find guidelines on how to submit the exercise.

**Keep in mind that you don't have to wait to fully finish the exercise to make a pull request. You only have to make a pull request once. After that, every time when you make a commit, it will be automatically added and shown in the pull request.**

## Instructions

### Introduction

In this exercise, you will clone the landing page of the **NPM website**. NPM stands for a Node Package Manager, and you will be using it heavily throughout this course. The version you will be cloning is the one in that you see in the following image. If you want, you can visit the [official page](https://www.npmjs.com/) to pick up some of their styles, but this is not necessary; you’ll see that the NPM page has been updated, but that’s okay. You already have all the assets for this version in the images folder as well as the necessary text in the `index.html`.

Our goal is to get as close as possible to this:

![]()

(). If you're struggling to see the details, feel free to zoom in to 200%.
Although it doesn't look too complicated, we will have to apply quite a few styles on our web page: set a background color on different elements, set a font weight (bold, normal), and position elements using our newly acquired skills in flexbox.

We will divide our work into two parts:

- part I - create a webpage with no styles, just add HTML and
- part II - add styles and make it perfect. 🎨

So let's get started!

**The assets we provided contain the `index.html` file with all the necessary text, as well as the `images` folder with all the required images to successfully finish the exercise.**

### Part I - pure HTML (no styles applied)

It might seem like a joke, but this is our goal in this iteration:

![](https://ilkcng.bn.files.1drv.com/y4m6QVvhtgzJoBCQ_KtAAWCPb_LBNNGHx924XIQUp6wk5kQ8DNgHo68ZbufSvpjbzNmfA4b8P867jMXXYNJgHGZ12zF_vhB1YG-qPwZY3hwL3mVFhyZvAUa-fQCDihA8F3SfLnNXAljiZ-vEWbNr-hOL4IPee5ZJR2hkZTVKtFHkSdjNiDFjrwOJ_NyxaFBCOwuO7ThXvcsjY970QI-6HMFAg?width=1343&height=231&cropmode=none)
![](https://ilkdng.bn.files.1drv.com/y4m7jSoqgGQAR1BEsSRn8_sQ8e3MoasA_YYAS9up0TpDbuYs63s0vIJNLQKKWz8lzFScyCtNLA6llomIfIojTVwtY3qn8h7EkcVkShwUbZQe7mITI5Lwq1k_03YmnEhrtllmYeuEpLs_tHzi6yRDne6vERcwfBnMC8rPB-X6OFFOVDu-Kfdm59YyCYf2InCBYZdK9Gbdy5gWRGEM4lbZxDODg?width=1342&height=357&cropmode=none)
![](https://ilkbng.bn.files.1drv.com/y4mpb0kXN3GlEy0AhvRdSp6BWlwfxBF7vouTlM8zqxMrMHLGsmGCpaMKkNn3ryCUnL7_0AACTWhTtxL7PmjKWMud55uFanRHJCfqDdIY1-VT9nMv1Tx4I882fs7Tw9LNMPU_gflcezJxLL51e3H608ggkUUTtcZaIRgfhrqMvXgJlLTR3A8MKKUSHT3NEVAODecYg9EYBIwgls8WrDx2i9gGQ?width=1341&height=388&cropmode=none)
![](https://ilkang.bn.files.1drv.com/y4mOqKQHU6Pkr9v5QR6FGlp3SYxXSvOMn6LVxi2hEji4cdIF_h0tETmr6UJjyQoXej-7lNi_op6b7meI8fCSPhuwqJWOaeF-OrQCBg_kt6I4g_mVPnia90MQg1S6XwEXN1Cc0oHgRYHdkejgpfJ3jVltOTCkKoQtpYO7FoIFb44r6iuA12cLy2kj_j_Hf5VERcbvlt-lXyGXOYoiM_8pLUZTA?width=1343&height=530&cropmode=none)
![](https://iljqng.bn.files.1drv.com/y4menGzetAuCplL8dDPu1TRGNWM-ekdunP4qGsX6biVNnav994YW-b7K1JGGhXjiEF0ig2m9_NbMU5m30vm2NUHv2oDXplUxh6I1D3c92dl9mNDbTpw63QEa9Ivu5Oz21pTU-X5d2h07AGc8KLfBIskKFaCgRXWduzrAgWdypxwpIkh-JAsTaGo9spUZDiG0X2ybagG52jdfDgnRD1vqOcc3Q?width=1343&height=448&cropmode=none)
![](https://ilj8ng.bn.files.1drv.com/y4mH5euErvapj_XCRuOonRayqufCkv_jVTeiyGziHKme3FsJz1HvVXRmftBNVCQlxGdw3NCdMZZQOhkjqkMIaFH2DnxWRl6HCu4tPRFKlU7dcryBDyJsywLt9xFTOsO6cBtGBn_igNy4a3mzMdJ6vpDJkDr8qzjoJ2QHC_ECX3Lf8FMNUx8-ov7ClxaFwuDgV9rlPrdrlLEe9rOUMfIAWQWgg?width=1341&height=513&cropmode=none)
![](https://ilj9ng.bn.files.1drv.com/y4muhIIR4G6X3zbZYLWFkbLDQJm_ntNbkezHMpLIBo0n5y7FL1KfzGH9cCv-wMUGdV7gDyHZ2Zu7kvv90DJXSWcccfxn1faXpgR0FA8-I8LVIhZ0IuPjI63Kz5YnFevtl5QAvq6MjzjwYISXCHxZMUsltElKDz1tPOARgwMEZGAk2B1Uq2BPzf1Nj2amorBh24IPb9nOQHvAcM9ixJR05js1Q?width=1344&height=237&cropmode=none)
![](https://ilj8ng.bn.files.1drv.com/y4mH5euErvapj_XCRuOonRayqufCkv_jVTeiyGziHKme3FsJz1HvVXRmftBNVCQlxGdw3NCdMZZQOhkjqkMIaFH2DnxWRl6HCu4tPRFKlU7dcryBDyJsywLt9xFTOsO6cBtGBn_igNy4a3mzMdJ6vpDJkDr8qzjoJ2QHC_ECX3Lf8FMNUx8-ov7ClxaFwuDgV9rlPrdrlLEe9rOUMfIAWQWgg?width=1341&height=513&cropmode=none)
![](https://ilklng.bn.files.1drv.com/y4mpbWo-wfTgV2ia_oAQXu3rTLoYK50-lM3OFMKQejV6pIDF5wxrBCc-vvhb6VwsUrcVt13v0Oh3LOug4btJkV3aZ7Vv1ZQilAUn6zIosgdoGK9vg9nOF80DamecqwM6gpn4cE-X3ZYPemBBwqLp4-F2nTmYsrWiH68HImJgREKRwo8ifEfTLZ48Vb5lPkH5R3SE-uHSkCizUZfQolJduAXZg?width=1342&height=552&cropmode=none)

<br>

The very first step is deciding **how to structure the page and picking the correct _semantic_ tags**. In general, choosing the right tags will make your job easier in the next step when the time comes to do some styling.

Our recommendation is to try to keep it as simple as possible. Try to identify the different sections, and add `id`'s or `classes` to each `<div>`, `<section>`, `<ul>`, or `<header>` block elements to identify these elements. Here is suggested guideline but you might have something on your mind that is different from this - bring it up.

![]()

#### HTML 1 | `<header>` & `<nav>`

Your task in this iteration will be to create the `header` and `nav`, which are the first two elements of the page. As you can see on the image above, the first element inside the body is `header` and it is composed of two divs:

- the upper div contains another div with image and some text, and besides this, it has _nav_ tag with list displayed horizontally
- the bottom div has the logo, search bar (which is _form_) and some buttons all the way left.

![]()

However, remember, on the image above styles are already applied so our final result won't be quite the same.

We could try to represent this part of the website with the following:

```html
<header>
  <div>
    <div>
      <img class="blackHeart" src="LINK TO IMAGE GOES HERE" alt="black heart" />
      <span> Nifty Penguin Magic </span>
    </div>
    <nav>
      <ul>
        <li><a href="#"> npm Enterprise </a></li>
        <li><a href="#"> Products </a></li>
        <li><a href="#"> Solutions </a></li>
        <li><a href="#"> Resources </a></li>
        <li><a href="#"> Docs </a></li>
        <li><a href="#"> Support </a></li>
      </ul>
    </nav>
  </div>

  <div>
    <!-- add logo, search bar and buttons (or links and style them as buttons later) -->
  </div>
</header>
```

When done, you should get something similar to this:
![]()

You're ready to move to the next iteration. :raised_hands:

#### HTML 2 | Content Sections

Take a look at the image with market HTML elements on it one more time, and you can see we have three sections below the header. Create `section` tags and give each of them `id`s so you can identify them quickly.

The content for each of these sections is already in the _index.html_ but you have to organize it properly making sure there are headings, paragraphs, divs, etc.

**All images can be found in your `images` folder!**

You can see the final result on the gif at the beginning of this exercise.

The time has come! Let's add some styles and make it pretty! :nail_care:

### Part II - CSS/styles

#### CSS 1 | Setup

As you might recall, the first thing we have to do to add styles to our page is to create a `style.css` file and link it to our `index.html`.

So let's begin by creating a new file, in the same folder as our HTML file, and name it `style.css`. Now, link the file to the _index.html_.

_Hint_: In case you need to refresh your memory on how to do this, check _Introduction to CSS_ lesson.

_Hint2_: You might want to consider adding the following line to your CSS, just to confirm that you have linked it correctly:

```css
body {
  background-color: red;
}
```

Refresh the page in Chrome, and if your _style.css_ is linked properly, the page should turn red. (*You can delete the *background-color* property we added as a test once you have confirmed it's working.*) :wink:

:::info
Before we move forward, add at the very top of your _style.css_ file the following lines:

```css
@import url('https://fonts.googleapis.com/css?family=Poppins');

body {
  font-family: 'Poppins';
}
```

:::

This will be the default font you will be using on the entire webpage.

Now we are ready to start adding some styles to our page.

#### CSS 2 | The Header and the navbar

In the first part of this exercise, you created the header and inside it the navbar. Now we have to add some styles to make it more like this:

![]()

We'll help you style the part of the code we previously provided for you - the upper _div_ of the _header_ tag.

```css
header > div {
  padding: 0 25px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  border-bottom: 1px solid lightgray;
}

nav {
  width: 600px;
}

nav ul {
  list-style: none;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

nav a {
  text-decoration: none;
  color: black;
}

.blackHeart {
  width: 20px;
  margin-right: 1rem;
}
```

_Useful information_:

- _form label color_: rgba(0,0,0,.05)
- _form input color_: rgba(0,0,0,.05)
- _form button background color_: #fb3e44
- _form button letters color_: white

As you can see, a lot of _flexbox_ is involved - if needed, revise the lesson again or sneak peek into the official docs (use your Google skills) or use this [resource](https://flexbox.help/) as a help.

Make sure to use flexbox at any time where you need to position elements on a specific place - practice as much as possible: the more you understand now, the easier will be later.

#### CSS 3 | section 1

![]()

In this section, as you can see everything is _centered_. You can add some flexbox rules to the _id_ you attached to this section such is _display: flex;_ and _justify-content: center;_. But this is just the beginning - you still have to set _align-items_ and _flex-direction_.

_Useful information_:

- suggested height for this section: 600px
- background color: rgba(232,217,217,.3)
- "See plans" button background color: #FB3B49
- "See plans" button box shadow: 8px 8px 0 rgba(251,59,73,.2)

#### CSS 4 | section 2

![]()

This section has pretty much the same layout as the previous - some code to be reused :wink:.

_Useful information_:

- _heading background color_: rgba(255,204,53,.4)
- to get the transform of the yellow background in the left-hand direction use: _transform: skew(9deg,0deg);_
- to get it in the opposite direction of the letters, the way we need it on the page, use: _font-style: italic;_
- to additionally fine-tune the position of each element, use _margin_ property.

Again use a lot of flexbox to get the right position of elements - direction, justify-content, align-items.

**Inspect elements to get the right size of the font for each of them**. However, this is not a crucial thing, so don't spend too much time on it - focus on positioning primary.

#### CSS 5 | section 3

![]()

_Useful information_:

- color of the letters in each heading in this section: #ED1C24
- "Create an Org" box shadow: 8px 8px 0 rgba(128,83,35,.2)
- "Create an Org" letters color: white

## Submission

If you didn't [add, commit and push the changes]() you made, this is the last call. :smile:

And at the same time, if you didn't [create a pull request]() this is the time for that as well.

Your TAs will check up your work and provide feedback.

**Once again, a friendly reminder**: You don't have to wait to finish everything in order to follow the steps listed in the [guidelines](). In a moment when you've made a first significant step in working on this assessment, we advise you to make a pull request. Starting from that moment, every change you make will be automatically added to that pull request and will be visible to your TAs for a checkup.

## Summary

In this exercise, you've built a clone of a piece of the npm home page. This site is very complex so if you managed to make it look anything like the original, good job! :trophy:

This concludes the HTML / CSS module. We are proud of you!

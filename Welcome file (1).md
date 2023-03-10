﻿# Framer

Buttondown forms are easy to build, and can drive newsletter subscriptions directly from your website. If you’re in need of a website, [Framer](https://www.framer.com/) is a sleek, no-code tool that can help you build one. By the end of this tutorial, you’ll know how to embed a subscription form for your newsletter in Framer. 

> ## Getting Started
> Before we get going, make sure that you have: 
> - A [Framer](https://www.framer.com/) site that’s up, running, and ready for new content
> - A Buttondown account (don’t be shy, [sign up here](https://buttondown.email/register)!)


## Connecting Buttondown to Framer


### Retrieve your form
Our journey begins in the “Embedding & Sharing” section of your Buttondown [settings](https://buttondown.email/settings). Select the “As a Form” tab to find HTML code for adding a subscription form. Copy this code and keep it in your back pocket—you’ll need it later!

![Alt Text](https://i.imgur.com/sRGqPEu.mp4) 

### Insert an "Embed" block

Mosey on over to your canvas in [Framer](https://www.framer.com/). From here, click “Insert” and scroll through the dropdown menu until you arrive at “Utility.” Then click “Embed.” 


### Switch your "Embed" type to "HTML"
Click your newly embedded block, and glance over at the properties panel that pops up. 

Scroll down to the “Embed” section and switch your “Embed” type to “HTML.” 


### Copy and paste your HTML form
You’ve done it! Your new Buttondown form should look a little something like this. 


## Going Above & Beyond

### Add subscriber tags
As your subscriber base grows (congrats!), you may want to organize it by assigning tags to individual subscribers. These tags can be used to sort your subscriber base, as well as to send out targeted email blasts. 

You can automatically add tags to any new subscribers by modifying the HMTL code you used to create your subscription form. All you have to do is add a new <span class="bg-gray-200 font-mono p-0.5 rounded">input</span> tag that matches the following format. 

       <input type="radio" id="fettucine" name="tag" value="fettucine" />
      <label for="fettucine">Fettucine Alfredo</label>

As you can see above, the input <span class="bg-gray-200 font-mono p-0.5 rounded">type</span> is “radio,” and the input <span class="bg-gray-200 font-mono p-0.5 rounded">name</span> is “tag.” The input <span class="bg-gray-200 font-mono p-0.5 rounded">ID</span> and input <span class="bg-gray-200 font-mono p-0.5 rounded">value</span> are customizable for your reference, and the input <span class="bg-gray-200 font-mono p-0.5 rounded">label</span> is what your new subscriber will see as part of your subscription form. Here’s an example of how your HTML code might look with three new tag options. 

    <form
      action="
        https://buttondown.email/api/emails/
      "
      method="post"
      target="popupwindow"
      class="embeddable-buttondown-form"
    >
      <label for="email">Email</label>
      <input
        type="email"
        name="email"
        placeholder="you@example.com"
      //>
      <label for="email">What Is Your Favorite Pasta Dish?</label>
      <br />
      <input type="radio" id="Fettucine" name="tag" value="Fettucine" />
      <label for="Fettucine">Fettucine Alfredo</label>
      <input type="radio" id="Carbonara" name="tag" value="Carbonara" />
      <label for="Carbonara">Spaghetti Carbonara</label>
      <input type="radio" id="penne" name="tag" value="penner" />
      <label for="penne">Penne alla Vodka</label><br />
      <br />
      <input type="hidden" value="1" name="embed" />
      <input type="submit" value="Subscribe" />
      <p>
        <a href="https://buttondown.email" target="_blank">
            Powered by Buttondown.
        </a>
      </p>
    </form> 

Here's what that code looks like when it's rendered. 

<form
  action="
    https://buttondown.email/api/emails/
  "
  method="post"
  target="popupwindow"
  class="embeddable-buttondown-form"
>
  <label for="email">Email</label>
  <input
    type="email"
    name="email"
    placeholder="you@example.com"
  //>
  <label for="email">What Is Your Favorite Pasta Dish?</label>
  <br />
  <input type="radio" id="fettucine" name="tag" value="fettucine" />
  <label for="fettucine">Fettucine Alfredo</label>
  <input type="radio" id="carbonara" name="tag" value="carbonara" />
  <label for="carbonara">Spaghetti Carbonara</label>
  <input type="radio" id="penne" name="tag" value="penne" />
  <label for="penne">Penne alla Vodka</label><br />
  <br />
  <input type="hidden" value="1" name="embed" />
  <input type="submit" value="Subscribe" />
  <p>
    <a href="https://buttondown.email" target="_blank">
        Powered by Buttondown.
    </a>
  </p>
</form>

Success! Now you can add as many tags as your heart desires. If you’re interested in learning more about tags, check out our doc on “[Building your subscriber base](https://docs.buttondown.email/getting-started/building-your-subscriber-base).” 

### Customize your form

You may want to style your form so that it matches your website’s aesthetic—that’s all good! You can do that in Framer by referencing their “[Creating Custom Forms](https://www.framer.com/learn/how-to-create-a-custom-form/)” doc.

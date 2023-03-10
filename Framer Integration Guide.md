﻿# Framer

Buttondown forms are easy to build, and can drive newsletter subscriptions directly from your website. If you’re in need of a website, [Framer](https://www.framer.com/) is a sleek, no-code tool that can help you build one. By the end of this tutorial, you’ll know how to embed a subscription form for your newsletter in Framer. 

> ## Getting Started
> Before we get going, make sure that you have: 
> - A [Framer](https://www.framer.com/) site that’s up, running, and ready for new content
> - A Buttondown account (don’t be shy, [sign up here](https://buttondown.email/register)!)


## Connecting Buttondown to Framer


### Retrieve your form
Our journey begins in the “Embedding & Sharing” section of your Buttondown [settings](https://buttondown.email/settings). Select the “As a Form” tab to find HTML code for adding a subscription form. Copy this code and keep it in your back pocket—you’ll need it later!

![Alt Text](https://github.com/madelinezday/buttondown/blob/main/GetHTML.gif?raw=true)

### Insert an "Embed" block

Mosey on over to your canvas in [Framer](https://www.framer.com/). From here, click “Insert” and scroll through the dropdown menu until you arrive at “Utility.” Then click “Embed.” 

![Alt Text](https://github.com/madelinezday/buttondown/blob/main/EmbedBlock.gif?raw=true)


### Switch your "Embed" type to "HTML"
Click your newly embedded block, and glance over at the properties panel that pops up. 

![Alt Text](https://github.com/madelinezday/buttondown/blob/main/SelectBlock.gif?raw=true)

Scroll down to the “Embed” section and switch your “Embed” type to “HTML.” 

![Alt Text](https://github.com/madelinezday/buttondown/blob/main/SwitchHTML.gif?raw=true) 

### Copy and paste your HTML form

Remember that code you put in your back pocket? Pull it back out and paste it into the HTML field. 


![Alt Text](https://github.com/madelinezday/buttondown/blob/main/PasteHTML.gif?raw=true)

You’ve done it! Your new Buttondown form should look a little something like this. 

![Alt Text](https://github.com/madelinezday/buttondown/blob/main/SubscriptionForm.gif?raw=true)

## Going Above and Beyond

### Add subscriber tags
As your subscriber base grows (congrats!), you may want to organize it by assigning tags to individual subscribers. These tags can be used to sort your subscriber base, as well as to send out targeted email blasts. 

You can automatically add tags to any new subscribers by modifying the HMTL code you used to create your subscription form. All you have to do is add a new <span class="bg-gray-200 font-mono p-0.5 rounded">input</span> tag that matches the following format. 

       <input type="radio" id="fettucine" name="tag" value="fettucine" />
      <label for="fettucine">Fettucine Alfredo</label>

 Here’s an example of how your HTML code might look with three new tag options. 

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

![Alt Text](https://github.com/madelinezday/buttondown/blob/main/SubscriptionFormwithTags.gif?raw=true)

Feel free to add as many tags as your heart desires. If you’re interested in learning more about tags, check out our doc on “[Building your subscriber base](https://docs.buttondown.email/getting-started/building-your-subscriber-base).” 

### Customize your form

You may want to style your form so that it matches your website’s aesthetic—that’s all good! You can do that in Framer by referencing their “[Creating Custom Forms](https://www.framer.com/learn/how-to-create-a-custom-form/)” doc.

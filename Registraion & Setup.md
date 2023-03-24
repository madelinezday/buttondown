﻿# Registration & Setup

Ready to dive into Buttondown? Look no further for everything you need to sign up, configure your settings, and send your first newsletter.

## Getting Ready

Buttondown is entirely based in your browser (nifty, right?). This makes registration quick and easy—but it’ll be even quicker if you have a few things at the ready:

-   A browser with cookies, JavaScript, and in-browser pop-ups enabled
    
-   An active email address
    
-   A strong password
    
Once you’re ready to roll, you can begin by registering [here](https://buttondown.email/register).


## Signing Up

### Choose your username

First thing’s first: You’ll need to think up your username. This username is not only what you’ll use to log in—it’ll also be part of your public Buttondown URL. With this in mind, you may want to pick a username that’s memorable, identifiable, and unique to your newsletter. (Don’t worry, you can change this later if you need to.)


### Add your email

Enter your go-to email for receiving notifications, account updates, and billing information.
  
Later on, if you decide to send your newsletter from the Buttondown server, your subscribers won’t see the email address that you registered with. Instead, they’ll see a Buttondown email address formatted as “username@mail.buttondown.email.” It’ll look something like this:

![Sample email address if sending from Buttondown server](https://github.com/madelinezday/buttondown/blob/registration-&-setup/Sample%20email%20address%20if%20sending%20from%20Buttondown%20server.png?raw=true) 

You also have the option to send your newsletter from a [custom domain](https://docs.buttondown.email/getting-started/getting-a-custom-domain). It’s totally up to you, but if you choose to do this, then make sure your email address matches your domain in order to avoid any delivery issues.


### Devise your password

You know the drill—use lots of numbers, letters, and symbols.

Once you’ve completed these three steps, click “Create an Account” and you’ll be well on your way.

![Buttondown registration page](https://github.com/madelinezday/buttondown/blob/registration-&-setup/Buttondown%20registration%20page.gif?raw=true)


### Confirm your account

Keep an eye out for a confirmation email from “notifications@buttondown.email.” Then click the link in that email to make your account official!

![Buttondown confirmation email](https://github.com/madelinezday/buttondown/blob/registration-&-setup/Buttondown%20confirmation%20email.gif?raw=true)


## Crafting Your Newsletter's Look and Feel

### Fill out your general newsletter details

Boom, you’re in! After perusing your administrative [settings](https://buttondown.email/settings), scroll down to the “General” section to start shaping your newsletter.

With your username and email taken care of, we can move on to the fun part: Coming up with your newsletter’s name, author, description, and more. This is your time to shine—customize this section however you like! Just three quick things to note:

-   What you put in the “Author” field will populate your newsletter’s “From” field
    
-   Your newsletter “Description” can be written in Markdown, HTML, or plaintext
    
-   Your time zone will be used for scheduled newsletter recommendations, as well as for timestamps in your archives

When you’re done filling out the details, your “General” settings should look a little something like this.

![“General” settings section](https://github.com/madelinezday/buttondown/blob/registration-&-setup/%E2%80%9CGeneral%E2%80%9D%20settings%20section.gif?raw=true)


### Build out your newsletter's "Scaffolding"

Your “Header” and “Footer” will appear at the top and bottom (respectively) of every newsletter that you send. These fields can be written out in Markdown, HTML, or plaintext.
  
In this section, you also have the option to customize each newsletter’s CSS, or style, with HTML. You can learn more about building out your newsletter’s CSS [here](https://docs.buttondown.email/advanced-features/customizing-your-emails).

![“Scaffolding” settings section](https://github.com/madelinezday/buttondown/blob/registration-&-setup/%E2%80%9CScaffolding%E2%80%9D%20settings%20section.gif?raw=true)


### Establish your newsletter's "Branding"

Your newsletter’s branding includes its color palette, or “Tint Color,” as well as its logo, or “Icon.” Your “Tint Color” will pop up as an accent in places like hyperlinks or your “Subscribe” button. Your “Icon” will appear on top of your newsletters, in your archives, and as part of your social “Share” button. Upload a square image (ideally a PNG) with a 300 x 300 resolution for the best results.

![“Branding” settings section](https://github.com/madelinezday/buttondown/blob/registration-&-setup/%E2%80%9CBranding%E2%80%9D%20settings%20section.gif?raw=true)


## Sending Your First Newsletter

### Import your subscribers

Already have a list of subscribers? Have no fear! You can upload that list to Buttondown as a [CSV](https://docs.buttondown.email/odds-and-ends/glossary#csv) (or "comma-separated values") file. Buttondown can automatically import the following values for each of your subscribers:

-   Email address
    
-   Time joined (this can be imported in the standard “month/day/year” format)
    
-   Notes (these are completely open-ended, and don’t have to follow a specific format)
    
-   Tags (read more about tags [here](https://docs.buttondown.email/getting-started/building-your-subscriber-base#adding-tags-to-your-subscribers))
    
-   Metadata (read more about metadata [here](https://docs.buttondown.email/getting-started/building-your-subscriber-base#adding-metadata-to-your-subscribers))

Let’s say you have your subscriber database loaded into a Google or Excel spreadsheet. Toggle to “File,” and select “Download.” Then select “Comma-Separated Values (.csv)” to export your CSV file.

![Exporting a CSV from Google Sheets](https://github.com/madelinezday/buttondown/blob/registration-&-setup/Exporting%20a%20CSV%20from%20Google%20Sheets.gif?raw=true)

Now let’s move back to Buttondown—specifically, the “Subscribers” page. From here, click the “Import” button to upload your CSV file. Once your file uploads, you’ll be guided through a series of questions to identify the columns of your CSV file.

![Guided questions for importing subscribers](https://github.com/madelinezday/buttondown/blob/registration-&-setup/Guided%20questions%20for%20importing%20subscribers.gif?raw=true)

Once you’ve completed each of the guided questions, click “Done,” and Buttondown will start importing your subscribers. Note that if you’re uploading a large quantity of subscribers, it may take a few hours to process. But when Buttondown is ready, you should see your newly imported subscribers (along with their accompanying notes, tags, metadata, and more) in the “Subscribers” page.

![“Notes” for an imported subscriber](https://github.com/madelinezday/buttondown/blob/registration-&-setup/%E2%80%9CNotes%E2%80%9D%20section%20for%20an%20imported%20subscriber.gif?raw=true)

Visit our “[Importing Your Data](https://docs.buttondown.email/getting-started/importing-your-data)” doc to learn even more about downloading CSVs and importing subscribers, as well as importing past newsletter archives.


### Draft your first newsletter

So you’ve found yourself in the “Emails” page. You may not have any newsletters there yet, but you will soon! Click the “New” button in the upper right corner to get started.

You’ll be transported to Buttondown’s intuitive writing interface, where you can easily toggle between “Preview Mode” and “Editor Mode.” "Preview Mode" renders your Markdown or HTML draft in a more readable format. "Editor Mode" provides a tool bar for formatting your text, adding links, adding images, and more. When you’re ready, jump in to code your newsletter in either Markdown or HTML. Buttondown will automatically save your progress as you go!

![Buttondown’s “Email” page and writing interface](https://github.com/madelinezday/buttondown/blob/registration-&-setup/Buttondown%E2%80%99s%20%E2%80%9CEmail%E2%80%9D%20page%20and%20writing%20interface.gif?raw=true)

Once you’re happy with your newsletter’s subject and body text, you’ll be ready to send a draft. Click “Send Draft” and enter your preferred email address for previewing your newsletter. Then click “Add Recipient,” and off it goes!

![Pop-up for choosing draft recipients](https://github.com/madelinezday/buttondown/blob/registration-&-setup/Pop-up%20for%20choosing%20draft%20recipients.gif?raw=true)

Wait just a few moments, and your draft should pop up in your inbox with “[PREVIEW]” in the subject line.

![Newsletter draft](https://github.com/madelinezday/buttondown/blob/registration-&-setup/Newsletter%20draft.gif?raw=true)


### Send your first newsletter

After you make any necessary edits to your draft, you’re almost ready to click “Send”—there are just a few other quick details to attend to. Here’s a checklist to make sure everything’s ship shape:

-   Have you checked all of your links?
    
-   How many subscribers are you sending your newsletter to? Will you be sending to all of your subscribers, or only those with certain [tags](https://docs.buttondown.email/getting-started/sending-your-first-email#tags-and-segmentation)?
    
-   Are you ready to send this newsletter immediately, or would you rather [schedule it for later](https://docs.buttondown.email/getting-started/scheduling-an-email)?

Once you’ve double checked all the little details, it’s time to click “Send.” You’ll see a congratulatory pop-up with buttons to share your newsletter via social media or a copy-and-paste-able URL. And, in case of emergency, you’ll also have an option to “Undo” sending your newsletter.

![Pop-up after sending newsletter](https://github.com/madelinezday/buttondown/blob/registration-&-setup/Pop-up%20after%20sending%20newsletter.gif?raw=true)

You’ve done it! For further information about uploading images, adding custom unsubscribe links, sending out mail merges, and more, check out our detailed guide for “[Sending Your First Email](https://docs.buttondown.email/getting-started/sending-your-first-email).”


## Going Above and Beyond

### Schedule your newsletter

You may want to schedule your newsletter to send at a specific date or time. You can do this by clicking the “Scheduling” button at the bottom of your draft. Set your target date and time, and double check your time zone before clicking “Save.” One last step: Make sure you click “Send” in the bottom right corner before exiting your draft. Buttondown will still send it at the time you specified, but it needs to get the official go-ahead from you clicking “Send”!

![Pop-up for scheduling newsletter](https://github.com/madelinezday/buttondown/blob/registration-&-setup/Pop-up%20for%20scheduling%20newsletter.gif?raw=true)

Take a look at our “[Scheduling an Email](https://docs.buttondown.email/getting-started/scheduling-an-email)” doc for FAQs and further information.


### Build your subscriber base

You’ve sent your first newsletter, and now you’re ready to cultivate your subscriber base. You can start by [sharing your Buttondown URL](https://docs.buttondown.email/getting-started/building-your-subscriber-base#sharing-your-buttondown-url), [embedding an HTML form](https://docs.buttondown.email/getting-started/building-your-subscriber-base#embedding-an-html-form) across your platforms, or [embedding an iFrame](https://docs.buttondown.email/getting-started/building-your-subscriber-base#embedding-an-iframe) on your website. Our doc on “[Building Your Subscriber Base](https://docs.buttondown.email/getting-started/building-your-subscriber-base)” is a great place to start.


### Organize your subscriber base

[Tags](https://docs.buttondown.email/getting-started/building-your-subscriber-base#adding-tags-to-your-subscribers) can be used to sort your subscribers, as well as to send out targeted email blasts. Like tags, [metadata](https://docs.buttondown.email/getting-started/building-your-subscriber-base#adding-metadata-to-your-subscribers) can also provide additional context for subscribers. That context can come in handy if you’re searching for a specific set of subscribers.

Want to learn more about tags and metadata? Our “[Building Your Subscriber Base](https://docs.buttondown.email/getting-started/building-your-subscriber-base)” doc is the best way to do so.


### Use a custom domain

You may choose to send and archive newsletters through a custom domain in order to consolidate your brand presence. Learn more about custom domains by checking out our docs for “[Getting a Custom Domain](https://docs.buttondown.email/getting-started/getting-a-custom-domain),” “[Hosting on a Custom Domain](https://docs.buttondown.email/getting-started/hosting-on-a-custom-domain),” and “[Sending From a Custom Domain](https://docs.buttondown.email/getting-started/sending-from-a-custom-domain).”


### Upgrade to a paid account

Buttondown is free for your first hundred subscribers. After that, we charge a small fee to help keep the lights on. Pay a visit to our and “[Billing](https://docs.buttondown.email/getting-started/billing)” doc to explore all of Buttondown’s [pricing](https://buttondown.email/pricing) options.


### Schedule a chat with us

We’re here in case you need to ask any questions or talk through your account. Reach out to us at support@buttondown.email. We’re always excited to speak with you!







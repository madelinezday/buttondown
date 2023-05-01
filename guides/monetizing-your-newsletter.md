# Monetizing Your Newsletter

Whether you’d like to set up a formal paid subscription program or a fluid pay-as-you-wish model, Buttondown offers a number of different ways to collect revenue from your subscribers—while also rewarding them with exclusive perks!

## Getting Started

To jump-start your paid newsletter, you’ll need:

-   A [Stripe](https://stripe.com/docs/tax) account. Don’t worry if you don’t have one yet—we’ll guide you through the process of setting it up!
    
-   A [paid](https://buttondown.email/pricing) Buttondown account, starting at our “[Basic](https://buttondown.email/pricing)” tier. Buttondown keeps the lights on by charging for premium tools, including “Paid Subscriptions.” This business model not only incentivizes us to create the best writing tool possible, but it also means that we’ll never need to take a cut of your hard-won newsletter earnings.

Got it? Good! Now let’s dive in.

## Setting Up Paid Newsletters

### Review Buttondown's standard practices

So you’re thinking of switching your newsletter from a free subscription model to a paid one. Here’s what you need to know about Buttondown’s default settings for paid newsletters:

-   Paid subscriptions will automatically renew at the end of your billing cycle, whether that’s once a month or once a year. This spares your subscribers from having to manually renew their subscriptions—while also generating more revenue for you!
    
-   If you’re a subscriber and you decide that you no longer want to receive a paid newsletter, simply click “Unsubscribe” as you would with any other newsletter. Pro tip: You can always downgrade your subscription by unsubscribing and then re-subscribing for free.

While these settings can’t be changed in Buttondown, you can customize your payments by using software like [Stripe](https://stripe.com/).

### Integrate Buttondown with Stripe

Earning money through your newsletter can be fun. Figuring out the logistics, less so. But [Stripe](https://stripe.com/) is here to help by automatically collecting payments and reporting taxes on your behalf.

Buttondown integrates seamlessly with Stripe. We’ve even built a shortcut right into the “Paid Subscriptions” section of your Buttondown settings.

![Link to sign up for Stripe through Buttondown](https://github.com/madelinezday/buttondown/blob/main/images/settings/monetizing:link-to-sign-up-for-stripe-tax-hi-res.gif?raw=true)

Once you confirm your new Stripe account’s email and password, you’ll be guided through a series of questions to activate payments. Stripe will ask for various personal details including your bank information as well as the last four digital of your social security number. You’ll also be prompted to enter business-related details such as a summary of your newsletter, along with a description of how often you’ll fulfill “orders” for your subscribers. For a step-by-step guide on completing this activation process, check out Stripe’s doc on how to “Activate Your Account.”

### Add your preferred payment methods

From credit cards to virtual wallets to bank debits and beyond, [Stripe](https://stripe.com/) works with dozens of different payment methods. You can select as many payment methods as your heart desires by navigating to the “Payment Methods” page from your “Product Settings.” Here’s a glimpse of what this page will look like:

![“Payment Methods” page in Stripe](https://github.com/madelinezday/buttondown/blob/main/images/stripe/monetizing:stripe-payment-methods-hi-res.gif?raw=true)

Once you’re satisfied with your choices, go to the “Payments” button in your dashboard to create a new payment link. For simplicity’s sake, let’s use Stripe’s no-code checkout page. 

![“Payment Links” page in Stripe](https://github.com/madelinezday/buttondown/blob/main/images/stripe/monetizing:page-to-create-payment-link.mp4?raw=true)

First, make sure that your checkout “Type” is set to “Products or Subscriptions.” Then add a new “Product” by filling in the name, description, price, and billing period for your newsletter.

When you’re ready, go ahead and publish your link. You’ll be directed to an overview page where you can copy your payment link as a URL, send it as a QR code, or configure it as a “Subscribe” button for your newsletter or website.

![Stripe’s payment link editor for subscriptions](https://github.com/madelinezday/buttondown/blob/main/images/stripe/monetizing:finished-payment-link-hi-res.gif?raw=true)

It’s almost time to pop open the bubbly and celebrate your brand-new business. There’s just one more detail we have to sort out! 

### Review your business settings

Stripe makes it exponentially easier to handle taxes related to your paid newsletter. We recommend checking out Stripe’s docs on “Setting Up Stripe Tax” and “Collecting Taxes For Recurring Payments” for a full overview on how to make sure your tax information is in ship shape. 

## Offering Perks for Paid Subscribers

### Share your paid newsletter archive

Did you know that you can reward paid subscribers by giving them VIP access to your paid newsletter archives? There are two ways to go about this: Using shortcode or inviting subscribers manually. 

Want to go with option number one? If so, If so, use this code snippet to generate a unique-per-subscriber link to your newsletter archive:

	{{premium_archive_url}}

Buttondown automatically adds an extended version of this shortcode to the footer of your paid newsletter emails. The additional code ensures that your archives link will only appear in your emails to paid subscribers.

	{% if subscriber.subscriber_type == "premium" %} You can always view your full archives [here]({{premium_archive_url}}). {% endif %}

You can always edit your footer in the “[Scaffolding](https://buttondown.email/settings#scaffolding)” section of your Buttondown settings. Here’s what that process looks like:

![Buttondown’s “Scaffolding” settings](https://github.com/madelinezday/buttondown/blob/main/images/settings/monetizing:email-footer-settings-hi-res.gif?raw=true)

And here’s how that code will translate to your email footer:

![Sample email with archive link for paid subscribers](https://github.com/madelinezday/buttondown/blob/main/images/emails/monetizing:sample-email-with-archive-link-in-footer-hi-res.gif?raw=true)

Is shortcode not your style? Instead, venture to your “Subscribers” page in Buttondown and click any given paid subscribers’ email address. Then select the “Archives” button from the menu that pops up. This button will generate a personalized link that you can use to manually invite that subscriber.

![Buttondown settings for premium subscriber](https://github.com/madelinezday/buttondown/blob/main/images/subscribers/monetizing:premium-subscriber-notes-hi-res.gif?raw=true)

One last thing: No matter the method you choose, any given link will expire when a subscriber’s paid subscription lapses. That means one less thing for you to worry about! 

### Send gift subscriptions

It’s someone’s lucky day! If you’d like to give a gift newsletter subscription to any friend, family member, or subscriber, reach out to support@buttondown.email, and we’ll happily sort it out for you. 

Your recipient will get a notification via email once the gift subscription goes through. As of right now, gift subscriptions last forever. Read on if you’d rather offer a short-term free trial! 

### Offer free trials

Want to give prospective subscribers a sneak peek of your paid content? You can do that through Stripe. 

Hop on over to your “Payment Links” page. Click the three dots next to your payment link in order to edit your link’s settings. Under the “Options” section of the link editor, find the box marked “Include a Free Trial.” Check that box and specify the number of days you’d like to include in that trial. 

![Free trial options in Stripe’s payment link editor](https://github.com/madelinezday/buttondown/blob/main/images/stripe/monetizing:free-trial-button-in-stripe-hi-res.gif?raw=true)

This setting in Stripe will allow all prospective subscribers to register for a free trial. 

### Send coupon codes

The Buttondown team is happy to help you create and send manual coupon codes for discount subscriptions. Reach out to us at support@buttondown.email, and we’ll get your coupon code set up ASAP. 

However, it’s also possible (and likely faster) to create coupon codes through Stripe. You can do that by Clicking “Allow Promotion Codes” in the advanced settings of your payment link editor. 

![Advanced settings in Stripe’s payment link editor](https://github.com/madelinezday/buttondown/blob/main/images/stripe/monetizing:promo-code-hi-res.gif?raw=true)

For further information, follow along with Stripe’s “Discounts For Subscriptions” doc.

## Setting Up Free Newsletters with Paid Features

There are several ways to earn money for your newsletter without charging for premium subscriptions. Talk about the best of both worlds, right?

### Send both paid and free newsletters

While Buttondown doesn’t explicitly offer different payment tiers, it does let you specify whether emails go to all your subscribers or just your paid subscribers. This trick can help you to create a loose approximation of “Paid” and “Free” tiers. 

### Set up a pay-as-you-wish model

The beauty of the pay-as-you-wish model is that it encourages subscribers to support your writing without limiting their access to your content. You can set up a pay-as-you wish model through Stripe by creating a new payment method or editing an existing payment method. However, note that this model does not support recurring payments. In other words, customers will only have to pay once to gain access to your paid newsletter, as opposed to once every billing period.

If you’re interested in switching to this model, you can start by changing your payment link “Type” from “Products or Subscriptions” to “Customers Choose What They Pay.” From here, you can enter your newsletter’s title and description. You can also add a suggested one-time payment amount, or alternatively, a payment limit. 

![Stripe’s payment link editor for pay-as-you-wish model](https://github.com/madelinezday/buttondown/blob/main/images/stripe/monetizing:pay-as-you-wish-settings-hi-res.gif?raw=true)

Curious to learn more about setting up and customizing your payments using the pay-as-you-wish model? We recommend Stripe’s doc on “Letting Customers Choose What to Pay.”


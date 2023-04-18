# Surveys

Whether you’ve got a casual question (“What’s your favorite Star Wars movie?”) or a debate that needs settling (“Who shot first: Han Solo or Greedo?”), Buttondown’s “Surveys” feature is a nifty way to get feedback from your subscriber base. Read on to discover how to create, send, and analyze surveys—and learn valuable insights about your subscribers along the way!

## Getting Started

Got a burning question that you want to ask in your next email? Here’s what you’ll need to send a survey:

-   A paid Buttondown subscription. Visit our “[Pricing](https://buttondown.email/pricing)” page to learn more about how to upgrade your account!

Now let’s get you the droids—er, answers—that you’re looking for.

## Creating Your Survey

### Determine your survey's question

Venture to the “[Surveys](https://buttondown.email/surveys)” tab of your newsletter and click “New.” You’ll encounter a pop-up that will guide you through the process of creating your survey. Your first task? Coming up with a question to ask your subscribers.

![Pop-up to create new survey](https://github.com/madelinezday/buttondown/blob/main/images/surveys/surveys:pop-up-to-create-new-survey.gif?raw=true)

Each survey has room for one question and one question only, so make it count! However, you can always include multiple surveys in a single email if you have more than one question to ask.

### Assign a code to your survey

Next up, devise an ID for your survey in the “Code” field using letters (A–Z) and numbers (0–9). Your subscribers won't see this code—it's just for your internal use—but we recommend making it identifiable so that you can retrieve and render your survey more easily.

![“Code” field in pop-up](https://github.com/madelinezday/buttondown/blob/main/images/surveys/surveys:code-field-in-pop-up.gif?raw=true)

### Provide your survey's responses

The “Answers” field is where any and all possible survey responses should go. List out each of your responses (e.g. “R2-D2,” “C-3PO,” and “BB-8”) on separate lines without any punctuation. Buttondown will take care of the formatting for you!

![“Answers” field in pop-up](https://github.com/madelinezday/buttondown/blob/main/images/surveys/surveys:answers-field-in-pop-up.gif?raw=true)

### Preview your survey

Get a sneak peek of your survey in the “Preview” section. This is also a good opportunity to glance back at your “Question,” “Code,” and “Answer” fields, as once you publish your survey, these fields can’t be changed.

Down the line, if you’d like to make an adjustment to your survey, feel free to reach out to us at support@buttondown.email for assistance. However, whether your changes are big or small, the best way to edit your survey will be to create a new survey from scratch.

![“Preview” section in pop-up](https://github.com/madelinezday/buttondown/blob/main/images/surveys/surveys:preview-section-in-pop-up.gif?raw=true)

### Copy your survey code

At this point, your preview’s looking good and you’re ready to publish your survey. Before clicking “Create,” take a moment to copy your survey’s code in the “Usage” section. You’ll need this code to render your survey in your email.

Each survey’s code will always follow the same format. Here’s a quick example:

	{{ survey.ID }}

In this case, “ID” refers to the text you used to populate your survey's “Code” field. Here’s a more “real world” example:

![“Usage” section in pop-up](https://github.com/madelinezday/buttondown/blob/main/images/surveys/surveys:usage-section-in-pop-up.gif?raw=true)

Once you’ve copied your code, all that’s left to do is to click “Create”! In just a few moments, your survey will be published and ready to share with your subscribers.

## Sending Your Survey

### Preview your survey in an email

You’ve drafted up your email and now all it needs is the cherry on top: Your survey!

Here’s where that code you copied from the “Usage” section will come in handy. Simply paste the code where you’d like your survey to appear.

![Email draft in writing interface](https://github.com/madelinezday/buttondown/blob/main/images/email-interface/surveys:email-draft-in-writing-interface.gif?raw=true)

Your writing interface won't render your survey in its entirety, so we recommend sending an email draft in order to make sure your survey’s ship shape. (Need a refresher on sending email drafts? Our “[Getting Started](https://docs.buttondown.email/getting-started/registration-and-setup#draft-your-first-newsletter)” page is the best place to go!)

Here’s what your survey might look like as part of your email draft:

![Sample email draft with survey](https://github.com/madelinezday/buttondown/blob/main/images/emails/surveys:email-draft-in-inbox.gif?raw=true)

Note that if you try to click through the survey in this draft email, the buttons won’t work. That’s totally normal! Your survey will only record responses from subscribers who receive your finished email. This ensures that your survey results are as accurate as possible—more on this later!

### Style your survey

Feel free to customize the look and feel of your survey by modifying Buttondown’s basic HTML markup. Our standard styling is as follows:

	<div class="survey">

	<p><strong>Who is your favorite droid?</strong></p>

	<p>

	<ul>

	<li><a href="...">R2-D2</a></li>

	<li><a href="...">C-3PO</a></li>

	<li><a href="...">BB-8</a></li>

	</ul>

	</p>

	</div>

Pro tip: Buttondown automatically assigns a “survey” div class to your code, so if you’re having trouble finding your survey in your CSS, all you have to do is search for the “survey” wrapping div! Convenient, right?

### Send your survey

If the rest of your email is all set, that means it’s time to click “Send”! (Sending your very first email with Buttondown? Our “[Getting Started](https://docs.buttondown.email/getting-started/registration-and-setup#send-your-first-newsletter)” guide will walk you through the process.)

Here’s an example of what any given subscriber will see when they engage with your survey:

![Completed email with survey](https://github.com/madelinezday/buttondown/blob/main/images/emails/surveys:completed-survey.gif?raw=true)

## Analyzing Your Survey

### Understand your survey's responses

There are two things to keep in mind as you comb through your survey’s responses:

-   Surveys are not available in the web version of your email. This ensures that responses will only come from subscribers who received the survey from you directly.
    
-   Subscribers can only complete your survey once. No duplicate responses here!
    
We put these measures in place to ensure that your survey responses are an accurate reflection of your subscriber base. With that in mind, let’s take a look at your survey’s results!

### Read your survey's responses

Toggle to the “[Surveys](https://buttondown.email/surveys)” tab of your newsletter and click on the three dots to the far right of your survey’s ID. When the drop-down menu appears, select “Answers” to view a breakdown of your survey’s responses to date, as well as an accompanying graph.

![Survey responses](https://github.com/madelinezday/buttondown/blob/main/images/surveys/surveys:survey-responses.gif?raw=true)

### Export your survey's responses

Want to analyze your survey’s responses in more detail? We recommend exporting your survey’s data as a CSV file so that you can cross-reference it with your subscribers’ tags, metadata, and more.

If you’re already in your newsletter’s “[Surveys](https://buttondown.email/surveys)” tab, you can export this data by clicking the little check mark next to your desired survey and then clicking “Export” in the upper right hand corner.

![“Export” button](https://github.com/madelinezday/buttondown/blob/main/images/surveys/surveys:export-button-2.gif?raw=true)

Shortly after you hit the “Export” button, you’ll be prompted to download your data.
  
Alternatively, you can navigate to the “[Exports](https://buttondown.email/settings#exports)” section of your general settings. Click on your most recent export, and your download will begin automatically.

![“Export” section in Buttondown “Features” settings](https://github.com/madelinezday/buttondown/blob/main/images/settings/surveys:exports-section-in-settings.gif?raw=true)

Within a few moments, you'll have a detailed CSV file containing your subscribers’ emails and survey responses.

![Exported CSV file of survey responses](https://github.com/madelinezday/buttondown/blob/main/images/spreadsheets/surveys:exported-csv-file.gif?raw=true)

## Going Above and Beyond

### Add tags and metadata

Looking for new ways to organize your subscribers? Check out our guides on [tags](https://docs.buttondown.email/advanced-features/tags-vs-newsletters) and [metadata](https://docs.buttondown.email/advanced-features/metadata)!



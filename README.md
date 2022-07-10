


## Web Marketing

### Content Marketing

Relevant internal advert sections with links have been included across user-facing pages to promote the music lessons and store products available. The aim of the adverts is to direct the attention of the user to the relevant pages and convert them to customers.

### Social Media Marketing

A Facebook business page for the studio has been set up to ensure organic growth of the business. The site is linked to the business account through the facebook social media link. The Facebook page includes a link back to the site.

<a href="https://github.com/Claire-Potter/Belle-Musique-Studio/tree/main/project-files/facebook-business-page" target="_blank">Click here</a> to access images of the Facebook page.

### Email Marketing

The Student Showcase feature is used as an email marketing tool. It is a weekly update from the studio and includes a link to view the featured student of the week. It includes music lessons and music store advertisements, ensuring that users who have signed up for emails are directed to access our lessons and products. Users will opt-in to receive emails when they register for an account.

## GDPR

A privacy policy was generated through https://www.privacypolicygenerator.info/ and a link to the policy is available in the page footer.


## Business Model

### B2C – Business-to-consumer

B2C businesses sell to their end-user. This is the business model selected and utilised for Belle Musique Studio. 

![e-commerce business model](https://github.com/claire-potter/belle-musique-studio/blob/main/project-files/design/e-commerce-model.jpg)

* Who is the customer? 
    * The customer is the consumer, the individual by whom the purchased good or service will be used.
* What will they buy?
    * Belle Musique studio supplies music lesson subscriptions and music products. A customer would purchase a recurring subscription for a weekly music lesson or make a once off purchase from the store.
* And how will they pay?
    * All payments will be processed online through stripe.com.
    * They will be secure.
    * Products would require a once off payment to be made.
    * Subscriptions would require a recurring payment set up. The customer will have the choice to set up a weekly, monthly or annual subscription and would be billed accordingly.
* What data would need to be collected and stored?
    * The required data to purchase a product would be:
        * Full Name
        * Email Address
        * Credit Card Details
        * Delivery Address Details
        * Phone Number
    * The required data to take out a recurring subscription:
        * Full Name
        * Email Address
        * Credit Card Details
        * Phone Number
* Would the customer need to be authenticated?
    * For a once off purchase from the store, the customer would not need an account. However, if they wish to store any of their information within the database they would need to register for an account with Belle Musique Studio.
    * To take out a subscription for a weekly music lesson, as recurring payments are required, the customer will need to register and create an account in order to manage the subscription going forward.
* Roles within the e-commerce process:
    * Customer:
        * Subscribes to a lesson or
        * Orders a product
    * Belle Musique Studio Site:
       * Creates the customer and subscription record on Stripe and the database
       * Processes payment with stripe and sets up recurring payments
       * Creates the order and processes the payment through Stripe
       * Collects address details for delivery
    * Site Owner / Administrator:
        * Schedules the weekly online lesson with the customer
        * Provides the service
        * Arranges delivery of the product to the customer





































































































pip3 install Django==3.2 <br>
pip3 install django-crispy-forms <br>
pip3 install django-countries==7.2.1 <br>
pip3 install django-allauth==0.41.0 <br>
<br>
pip3 install stripe <br>
pip3 install pillow <br>
pip3 install oauth lib <br>
pip3 install django-summernote <br>
pip3 install cloudinary <br>
npm i -g heroku <br>
pip install heroku3 <br>
<br>
pip3 install dj_database_url <br>
pip3 install psycopg2-binary <br>
pip install heroku3 <br>
heroku login -i <br>
<br>
pip3 freeze > requirements.txt <br>
pip3 install gunicorn <br>
pip3 install boto3 <br>
pip3 install django-storages <br>
<br>
python3 manage.py makemigrations --dry-run <br>
python3 manage.py makemigrations <br>
python3 manage.py migrate --plan <br>
python3 manage.py migrate <br>
<br> 

python3 manage.py loaddata categories <br>
python3 manage.py loaddata manufacturers <br>
python3 manage.py loaddata products <br>
<br>

python3 manage.py createsuperuser <br>
python3 manage.py startapp appname <br>
































![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

Welcome BrianStritch,

This is the Code Institute student template for Gitpod. We have preinstalled all of the tools you need to get started. It's perfectly ok to use this template as the basis for your project submissions.

You can safely delete this README.md file, or change it for your own project. Please do read it at least once, though! It contains some important information about Gitpod and the extensions we use. Some of this information has been updated since the video content was created. The last update to this file was: **September 1, 2021**

## Gitpod Reminders

To run a frontend (HTML, CSS, Javascript only) application in Gitpod, in the terminal, type:

`python3 -m http.server`

A blue button should appear to click: _Make Public_,

Another blue button should appear to click: _Open Browser_.

To run a backend Python file, type `python3 app.py`, if your Python file is named `app.py` of course.

A blue button should appear to click: _Make Public_,

Another blue button should appear to click: _Open Browser_.

In Gitpod you have superuser security privileges by default. Therefore you do not need to use the `sudo` (superuser do) command in the bash terminal in any of the lessons.

To log into the Heroku toolbelt CLI:

1. Log in to your Heroku account and go to *Account Settings* in the menu under your avatar.
2. Scroll down to the *API Key* and click *Reveal*
3. Copy the key
4. In Gitpod, from the terminal, run `heroku_config`
5. Paste in your API key when asked

You can now use the `heroku` CLI program - try running `heroku apps` to confirm it works. This API key is unique and private to you so do not share it. If you accidentally make it public then you can create a new one with _Regenerate API Key_.

------

## Release History

We continually tweak and adjust this template to help give you the best experience. Here is the version history:

**September 1 2021:** Remove `PGHOSTADDR` environment variable.

**July 19 2021:** Remove `font_fix` script now that the terminal font issue is fixed.

**July 2 2021:** Remove extensions that are not available in Open VSX.

**June 30 2021:** Combined the P4 and P5 templates into one file, added the uptime script. See the FAQ at the end of this file.

**June 10 2021:** Added: `font_fix` script and alias to fix the Terminal font issue

**May 10 2021:** Added `heroku_config` script to allow Heroku API key to be stored as an environment variable.

**April 7 2021:** Upgraded the template for VS Code instead of Theia.

**October 21 2020:** Versions of the HTMLHint, Prettier, Bootstrap4 CDN and Auto Close extensions updated. The Python extension needs to stay the same version for now.

**October 08 2020:** Additional large Gitpod files (`core.mongo*` and `core.python*`) are now hidden in the Explorer, and have been added to the `.gitignore` by default.

**September 22 2020:** Gitpod occasionally creates large `core.Microsoft` files. These are now hidden in the Explorer. A `.gitignore` file has been created to make sure these files will not be committed, along with other common files.

**April 16 2020:** The template now automatically installs MySQL instead of relying on the Gitpod MySQL image. The message about a Python linter not being installed has been dealt with, and the set-up files are now hidden in the Gitpod file explorer.

**April 13 2020:** Added the _Prettier_ code beautifier extension instead of the code formatter built-in to Gitpod.

**February 2020:** The initialisation files now _do not_ auto-delete. They will remain in your project. You can safely ignore them. They just make sure that your workspace is configured correctly each time you open it. It will also prevent the Gitpod configuration popup from appearing.

**December 2019:** Added Eventyret's Bootstrap 4 extension. Type `!bscdn` in a HTML file to add the Bootstrap boilerplate. Check out the <a href="https://github.com/Eventyret/vscode-bcdn" target="_blank">README.md file at the official repo</a> for more options.

------

## FAQ about the uptime script

**Why have you added this script?**

It will help us to calculate how many running workspaces there are at any one time, which greatly helps us with cost and capacity planning. It will help us decide on the future direction of our cloud-based IDE strategy.

**How will this affect me?**

For everyday usage of Gitpod, it doesn’t have any effect at all. The script only captures the following data:

- An ID that is randomly generated each time the workspace is started.
- The current date and time
- The workspace status of “started” or “running”, which is sent every 5 minutes.

It is not possible for us or anyone else to trace the random ID back to an individual, and no personal data is being captured. It will not slow down the workspace or affect your work.

**So….?**

We want to tell you this so that we are being completely transparent about the data we collect and what we do with it.

**Can I opt out?**

Yes, you can. Since no personally identifiable information is being captured, we'd appreciate it if you let the script run; however if you are unhappy with the idea, simply run the following commands from the terminal window after creating the workspace, and this will remove the uptime script:

```
pkill uptime.sh
rm .vscode/uptime.sh
```

**Anything more?**

Yes! We'd strongly encourage you to look at the source code of the `uptime.sh` file so that you know what it's doing. As future software developers, it will be great practice to see how these shell scripts work.

---

Happy coding!

# navu-gtm-template
This project contains the template for a Google Tag Manager tag for adding Navu into a website.

Navu is a SaaS for business websites.  We add guides to web pages that are personalized to the visitor.  For more information, visit https://navu.co.

Navu depends on an embed code on each page on the site.  First you go to navu.co, sign up, and add your site.  That will assign a unique site code that needs to be added to the embed code.   The embed code adds the site code as a global variable
and then adds a script that loads the Navu functionality.

One way to add the embed code is by adding a corresponding tag using Google Tag Manager.  The steps to do this are as follows:

- Ensure that you have Google Tag Manager installed on your website.  If you have multiple subdomains where guides and tracking are required, you will need to do this for each one.
- Sign into Google Tag Manager and choose the appropriate account and container.
- Click "Add a new tag"
- Click Tag Configuration, then open the Community Template Gallery, find Navu Embed Code
- Click Add To Workspace and confirm that you want to add the tag
- Paste the site code from the "Code" field on the Site tab in your Navu dashboard into the Site Code field
- Click Save
- Add a trigger for All Pages so that the Navu embed code will appear on all pages
- Accept the default name, or adjust it if you prefer, and click Save
- In the banner of the Wordspace page, you should now see several changes that are pending.  Click Submit to apply these changes to your site.  Then describe the update (something like "Adding Navu embed code") and click Publish.

That's it.  You should get notified shortly from Navu about the embed code being detected on your site.

If you ever decide that you no longer want to have Navu on your site.  You can return to Google Tag Manager and delete the Navu tag and submit that change.  

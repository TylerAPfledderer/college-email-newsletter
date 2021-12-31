# College Small Business Newsletter
![Screenshot](https://user-images.githubusercontent.com/65234762/147802599-195f6df2-e2ee-46d8-98a1-13afe74b1896.png)

This is a demo email for a local community college's small business center newsletter. The design is an update from the one actually used, and based on the scheme from their website.

Links in the newsletter intentionally lead nowhere.

HTML file created in [Parcel](https://useparcel.com) with basic email testing, and validated with the [HTML Check Validation Tool](https://www.htmlemailcheck.com/)

## Observations

This is the first project that covers building an HTML Email, along with making it responsive. It considers all known email clients, including the Outlook Windows application by using commented if statement to wrap table cells around elements that employ `display: inline-block` and `max-width` properties.

Templating of the HTML structure came from the following:
- Mark Robbin's [Good Email Code Site](https://www.goodemailcode.com/email-code/template)
- Tutsplus article covering a tutorial on [building a template from scratch](https://webdesign.tutsplus.com/articles/build-an-html-email-template-from-scratch--webdesign-12770?ref=reallygoodemails)
- The page [Bulletproof Email Button](https://buttons.cm/) that generate cross-compatible button links

Building emails provide a great challenge in overcoming the inconsistencies between email clients while still being able to make some that is as responsive as website, while maintain fundamental accessibility for screen readers.

### Copyright Info
*All logos and images are owned by the Johnston Community College and are used only for the purposes of this demo and are not used and will not be used in any publication for monetary gain without expressed permission by said college.*

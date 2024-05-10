
# HTML Email Template

Straightforward, minimalist template for HTML emails

Based in [Base Template](https://www.goodemailcode.com/email-code/template.html)

[![version](https://img.shields.io/badge/version-0.1.0-yellow.svg)](https://semver.org)

## Installation

Coding HTML emails is complicated, especially when it comes to making them look good in Outlook. When it comes down to creating beautiful, responsive emails, Outlook will usually take those templates we worked so hard on and render them with broken links, missing pictures, and a misaligned layout.

Here you are a HTML template. It works quite well, however if they are sent from Outlook sometimes **unwanted spaces are inserted, especially in the GMail client**

The best way to create a HTML signature is building the element in a decent HTML editor, then copy the preview of the signature (copy the rendered HTML in the browser, not the code!)and paste it in a new signature in the Mail Client.  
For instance, in Outlook that can be achieved in `Preferences -> Signature`.

  

### Tips

-   Use the HTML no breaking space symbol ( **&****n****b****s****p;** ) between words to avoid wrapping in small devices (_white-space:nowrap_ usually does not work in most email clients).  
    Example: `Commercial&nbsp;Director`
-   Use the HTML no breaking space symbol ( **&****n****b****s****p;** )  to fill empty spaces. **Do not use blank gifs**
-   If you find problems in **iOS Mail App**, with the font color on **<****span****>** or **<****p****>** tags use **a** link tags
-   Use **minified HTML** to build the signatures ([minifier tool](https://codebeautify.org/htmlviewer))
-   Use `<span>` tagis instead of `<p>` tags to avoid unwanted spaces (this usually happens if the email is sent from Outlook),

	-	 i.e.: 

		
        Instead of 

        <p style="margin: 0;font-family:Arial,Helvetica,sans-serif;mso-line-height-rule:exactly;line-height:16px;font-size:14px;font-weight:bold;color:#4f5444;">Enter Projects Asia</p>
        <p style="margin: 0;font-family:Arial,Helvetica,sans-serif;mso-line-height-rule:exactly;line-height:18px;font-size:14px;color:#4f5444;">49/15 Boat Avenue, Cherngtalay</p>
        <p style="margin: 0;font-family:Arial,Helvetica,sans-serif;mso-line-height-rule:exactly;line-height:18px;font-size:14px;color:#4f5444;">Thalang, Phuket 83110, Thailand</p>
	
        use

        <p style="margin: 0;font-family:Arial,Helvetica,sans-serif;mso-line-height-rule:exactly;line-height:16px;font-size:14px;">
            <span style="font-family:Arial,Helvetica,sans-serif;mso-line-height-rule:exactly;line-height:16px;font-size:14px;font-weight:bold;color:#4f5444;">Enter Projects Asia</span>
            <span style="margin: 0;font-family:Arial,Helvetica,sans-serif;mso-line-height-rule:exactly;line-height:18px;font-size:14px;color:#4f5444;">49/15 Boat Avenue, Cherngtalay</span>
            <span style="margin: 0;font-family:Arial,Helvetica,sans-serif;mso-line-height-rule:exactly;line-height:18px;font-size:14px;color:#4f5444;">Thalang, Phuket 83110, Thailand</span>
        </p>
  

### External  Tools

-   [Email checker](https://www.htmlemailcheck.com/check/)
-   [Email signature generator](https://www.mail-signatures.com/signature-generator/)
-   [HTML Email Signatures and Spam Filters](https://emailsignaturerescue.com/support/general-faq/html-email-signatures-and-spam-filters)
-   [Spamhaus: Spam domain checker](https://check.spamhaus.org/)
-   [Barracuda: Spam domain checker](https://www.barracudacentral.org/lookups/lookup-reputation)

### Read more:

[Extra space added to HTML e-mail when sent from Outlook to Gmail](https://stackoverflow.com/questions/15122625/extra-space-added-to-html-e-mail-when-sent-from-outlook-to-gmail)

[Outlook Rendering Issues: 5 Tips to Ensure Your Emails Display Properly](https://medium.com/email-design/outlook-rendering-issues-5-tips-to-ensure-your-emails-display-properly-9520b2456166)

[Outlook Email Signature adding extra space when sent to Gmail iOS](https://litmus.com/community/discussions/8758-outlook-email-signature-adding-extra-space-when-sent-to-gmail-ios)

[Does anyone know where the signature file is stored on a Mac using Outlook 2016?](https://answers.microsoft.com/en-us/outlook_com/forum/all/does-anyone-know-where-the-signature-file-is/b65a9400-70e9-4670-a641-8f148ece5ca0)

## License

MIT

## Versioning

We use [SemVer](http://semver.org/) for versioning.
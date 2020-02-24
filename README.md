<div align="center">
  <h2>Create Google Shared Drive</h2><br />


![Create-Google-Shared-Drive](https://cdn.jsdelivr.net/gh/ParveenBhadooOfficial/Create-Google-Shared-Drive@master/screenshot.png)


</div>
## Get Required Data from 
* Open https://console.developers.google.com/apis/credentials
* After creating project or if you already have one.
* Click create credentials.
* Select OAuth client ID.
* Select Web application.
* Give it a name. (anything for your own reference)
* In Authorized JavaScript origins add https://developers.google.com
* In Authorized redirect URIs add https://developers.google.com/oauthplayground
* Save and note down your Client ID and Secret
* Open https://developers.google.com/oauthplayground
* On Right Top Side click on Setting Icon ![Settings](https://developers.google.com/oauthplayground/assets/images/settings.png)
* Click on Use your own OAuth credentials.
* Enter OAuth Client ID: and OAuth Client secret:
* Now back to same page https://developers.google.com/oauthplayground left side Step 1 i.e. Select & authorize APIs
* Find Drive API v3
* Select First Option i.e. https://www.googleapis.com/auth/drive
* Click on Authorize API. and give permissions using your google account.
* It will turn to Step 2 Exchange authorization code for tokens at the end of authentication.
* Click on Exchange authorization code for tokens, if it goes to step 3, click on Step 2 yourself.
* Select the option Auto-refresh the token before it expires.
* Copy the refresh token and paste in Line 6 of [workers.js](https://github.com/ParveenBhadooOfficial/Create-Google-Shared-Drive/blob/master/workers.js) along with your own Client ID and Secret at Line 4 and Line 5.
* Copy the Code and paste it into https://workers.cloudflare.com Site.

## Credits
* Theme from [Colorlib](https://colorlib.com)
* Source: [yyuueexxiinngg](https://github.com/yyuueexxiinngg/some-scripts/blob/master/workers/google/drive/create-share-teamdrive.js)
* Special Thanks: [donwa](https://github.com/donwa/goindex)
* Another Thanks: [Sumit Bot](https://t.me/isumitbot)
* CDN used: [jsDelivr](https://jsdelivr.com)

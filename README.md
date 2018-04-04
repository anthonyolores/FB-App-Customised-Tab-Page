# FB-App-Customised-Tab-Page

Some facebook pages just need to have a page that is personalised and not facebook themed. This little steps will guide the facebook page owner to add it's own tab in facebook using a page from secured website(https). It can be an about us, items for sale, contact us, or whatever you want to emphasize in your facebook page.


## 1. Create a facebook page where you will add the customised page tab. 
https://www.facebook.com/pages/create

## 2. Customised page to be added
Create an HTML page that will be displayed in the tab. The page must be up and running in a secured(https) domain.
The page will display as part of the facebook page in an iframe and is only available for desktop in browsers, it won't be available in mobile browser and facebook mobile app. Make sure the page is 820px or 520px width compatible because that's the normal width of facebook page in browsers, if the page goes beyond or less the said width facebook won't adjust the iframe and will display according to what was been set.

## 3. Facebook Developer Page
Go to facebook developer dashboard(https://developers.facebook.com/apps) and login using the account that has an Administrator privilege to the facebook page.

## 4. Create a new facebook app
- Click [Add a new App]
- Enter [Display Name]
- Click [Create App ID]

## 5. Set facebook app platform
- In the dashboard's left hand side, select [settings]->[Basic]
- Choose Category [Business and Pages]
- Click [+ Add Platform], select [Website]
- Enter the URL of the website in [Site URL]
- Click [+ Add Platform] this time it will be [Page Tab] 
- Enter the URL of the customised page in [Secure Page Tab URL] 
- Enter the name of the tab [Page Tab Name]
- Set the page width to 820px in [Wide Page Tab] (To maximise the full width of fb page) 

## 6. Add the customised tab in facebook page
- Make sure you're logged-in in facebook as Administrator in the page
- Open the browser and enter the customised page URL 
http://www.facebook.com/dialog/pagetab?app_id=FB_APP_ID&next=CUSTOMISIED_PAGE_URL
- In the popup, choose the facebook page where the customised page will be added
- Click [Add Page Tab]

## 7. In facebook page
- There's a new tab added
- Click the new tab and it should show the content of the page

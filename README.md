This is an example of a Next app that is connected to Builder and has a custom component registered. For the most part, this is used for quick troubleshooting, since this requires minimal config. 

## Configure

* Once you download these app files, run `npm install`, then `npm run dev` on the root folder. Take note of the Localhost port used to run the dev server.

* Create a new Space at [www.Builder.io] (Builder.io). 

* To copy the API key of the Space, go to [www.builder.io/account/spaces] (the Space account settings). 

* Place the API key in the single quotes found on line 10 of `PAGES > [[..pages]].tsx`. 

* Go to (www.builder.io/models) [Builder Models] and click the Page model. Edit the Preview URL to match the Localhost port of the dev server. 

* Go to (www.builder.io/content) [Builder Content] and create a page. 

At this point, you should see a custom "Header" component in the Custom Components folder. If you don't see it, please confirm that all steps have been followed. Reach out to me at support@builder.io if needed. 



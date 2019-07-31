[Back to Index](./index.html)

## Contents
- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Adding a Vote Site](#adding-a-vote-site)
- [Vote site Configuration](#vote-site-configuration)
- [Finishing Up](#finishing-up)

## #Introduction

> Before you follow this guide, please make sure you have [Created a Listing](./listing.html).
> This step is important as you will require a uniquely generated API link.

Our API system is built with the idea of simplicity, a minimalistic approach to setup and usage, it is of great concern that many vote for points systems that are currently being used do not use any sort of json call-backs or any tracking to validate the users actually vote once they click the link, your website in return rewards players points for the click and not the voting, Our API system aims to implement a unique way of correcting this problem, once a user clicks a link to vote, you can be safe in knowing that that click actually mattered, and their vote was contributed towards your server listing, this is done by using a uniquely generated API token that exists only for your account, that allows your website to authenticate itself and vote on your behalf, each vote is tracked by IP Address, meaning even with authentication, anyone can vote for your listing. To make things even easier we have created a guide with images that you can follow to successfully use such feature.

### #Getting Started
- First things first, using your flux control panel click the `vote for points` module. ![alt text](./images/v4p/step1.png "Step 1: Clicking the vote for points module.")

### #Adding a Vote Site
- Next we must add a new voting site, this can be done using the menu presented underneath your admin actions. ![alt text](./images/v4p/step2.png "Step 2: Select add new voting site.")

### #Vote site configuration
- Now the easy part, adding ragnaranks to your vote list, To complete this we must enter some information that corresponds to our website and your specific instance that was created there. ![alt text](./images/v4p/step3.png "Step 3: Viewing the form.")
- Visit [My Account](http://www.ragnaranks.test/account) on [Ragnaranks.com](http://www.ragnaranks.com) and scroll down to `API Direct Vote For Point Links` section, this will display a list of your currently created sites and the uniquely generated link that has been made just for your listing, you will need to copy the link inside the input textbox that corresponds to the listing you wish to have direct interaction with on your `vote for points` module, this will be used as the information required on the flux cp panel. `vote url`, example url of how it should look is as follows: `http://www.ragnaranks.test/api/ragnarok-server/vote4points?api_token=29e37846f3f2138af85960c7477522e81219e9e24e0395ea91de5c2660aa1220` ![alt text](./images/v4p/step5.png "Step 5: Grabbing your vote for points api link.")
- Last step is to finally fill in the information using the api link we retrieved in the last step and by setting up the time constraint and reward amounts, our server as of this current time allows votes every `12 hours` & `recommended value of 7 points`, this is subject to change so its in your best interest that you keep up to date by following our [facebook page](https://www.facebook.com/ragnaranks/), the image url should resemble your own website design and layout as such please add a suitable image. ![alt text](./images/v4p/step6.png "Step 6: Filling out the form.")
- Finishing up the form, you are required to select add site, allowing your new entry to be pushed to your collection of other vote for point sites. ![alt text](./images/v4p/step7.png "Step 7: Click the add site button to finish.")

## #Finishing Up
- Once you have successfully added the new vote site by following the guide in the above section, you should select the `Listing Voting Sites` button found on the menu, underneath the admin control action, this will present a list of all the available vote sites on your website that players can interact with. ![alt text](./images/v4p/step8.png "Step 8: Click Listing Voting sites to see your new listing.")
- And that's everything, you should now see your new vote site added to your website and functioning correctly ! ![alt text](./images/v4p/step9.png "Step 9: Verifying the finalised new vote site.")

[Done? Lets go Back to Index](./index.html)
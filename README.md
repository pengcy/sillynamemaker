# Google Actions Example - Silly Name Maker

## Service Components
**Google Actions**
https://console.actions.google.com/

**DialogFlow**
https://console.dialogflow.com/

**Google Cloud Functions**
https://console.cloud.google.com/home/dashboard

Google Firebase **Cloud Functions Log**
https://console.firebase.google.com/

## Work Flow
1. User talks to **Google Assistant**: "Hey Google, talk silly name maker."
2. Google Assistant routes the request to **Google Actions**.
3. Google Actions routes the request to **DialogFlow**.
4. DialogFlow either process the request itself or route it to **cloud functions**, or any other **backend services**.
5. DialogFlow finished process the request and came up with an response or the cloud function or any other backend service finished the process and sent the response back to **DialogFlow**.
6. DialogFlow sends response back to **Google Actions**.
7. Google Actions sends the response back to **Google Assistant**.
8. Google Assistant reads the response to the **user**.


## Deployment
```
firebase init      #Command for initialize the firebase project
firebase use --add #Command for adding the firebase cloud project
firebase deploy    #Command for deploying the firebase cloud functions
```

## Other examples: https://developers.google.com/actions/samples/
https://github.com/actions-on-google/dialogflow-silly-name-maker-webhook-nodejs

https://github.com/actions-on-google/dialogflow-facts-about-google-nodejs

https://github.com/actions-on-google/dialogflow-name-psychic-nodejs

https://github.com/actions-on-google/conversation-components-nodejs

https://github.com/actions-on-google/dialogflow-number-genie-nodejs

https://github.com/actions-on-google/dialogflow-transactions-nodejs

https://github.com/actions-on-google/dialogflow-ssml-nodejs

https://github.com/actions-on-google/dialogflow-helper-intents-nodejs

https://github.com/actions-on-google/dialogflow-updates-nodejs




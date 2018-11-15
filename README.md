## Zapier en Adafruit setup

Follow the steps carefully - Its easy don't worry 

### Setup

Make if needed a Google account(Calendar), Adafruit account and Zapier account.
Also Download zapier Chrome extension you can find this here: hier:https://chrome.google.com/webstore/detail/zapier/ngghlnfmdgnpegcmbpgehkbhkhkbkjpj

### Step 1 - Adafruit IO setup

- Make a new feed in Adafruit. Here:https://io.adafruit.com/ (To create a new feed click on 'Action')
- When created remember your feed key. If nested then use: {group}.{feedname})
- You wil need the name of your created feed Remember it carefully!

### Step 2 - Zapier Trigger setup

- Make a new Zap in zapier. Here https://zapier.com/ (click on 'Make a Zap!')
- As trigger we choose the New  Push button from Zapier.
- Connect your Google account to it.
- Test The trigger!


### Step 3 - Google Calendar Action setup

- Next on we choose Google Calendar with the action: Create Detailed Event.
- Fill in the fields to your liking.
- Test the action!

### Stap 4 - Adafruit Action link

- Connect Adafruit to Zapier with https://zapier.com/app/editor?template__0__selected_api=App25310API&template__0__title=My+First+Zap+with+Adafruit+IO&template__0__type_of=read
- After that you can make a new action with Adafruit
- choose for (enige) the option "send value to feed"
- In "edit template" tab fill in by Value: "1"(To your choosing) and Feed: "{Name of the feed}.
- (To make it work you have to complete the setup in Adafruit -- see step 1!) 
- Test The Action! 

Floris Elders 
- part 1 For Ivy

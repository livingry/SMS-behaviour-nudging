# SMS-behaviour-nudging
This project is based on an initial design and implementation concept worked on at the 2017 Healthhack hackathon in Sydney. Using simple web forms, programmable SMS notification with Twilio, a RESTful like API using node.js and dynamic web content.

### Purpose
Rather than having an another app or account to manage the user is able to recieve SMS notifications that link them to relevant web content at times that suit them. The outcome of this is to enable a person to find the best evidence based strategies for behavioural change that work based on the context in which they are used. 

### Process Description
The user is able to sign up for SMS notifications and have preferences set for when they are received. The SMS notification would contain shortlinks with a JSON web token than enables variable and dynamic web content to be displayed. In the initial concept the web content presented strategies to use when interacting with someone who has a substance abuse problem, along with another notification preference for followup. This followup is for the strategy to be rated for effectiveness in the situation it was used. Editing time preferences for subsequent notifications can be set when the followup rating is done.

### Proposed Discrete User Steps
1. User comes to a webform and enters mobile phone number
2. User presses the submit button on the webform
3. User receives SMS asking to confirm by replying 'yes'
4. User receives SMS with a message notifying them they have registered and a link
5. User presses the link in the SMS
6. User is directed to a webpage that displays some content and a webform for selecting time preferences when they recieve notifications
7. User selects their preference and submits the form
8. User receives SMS notification at time chosen with a message containing a link
9. User presses the link
10. User is directed to webpage containing a animation to guide them through some basic breathing to reduce any anxiety being experienced 
11. User finishes basic breathing activity and is presented content indicating a variety of behavioural change strategies
12. User cycles through strategies until they find the most appropriate one to test
13. User presses a CTA button to 'try' strategy
14. User is then presented with a webpage to choose a time for a followup SMS to rate the effectiveness of the selected strategy
15. User engages in context to use the strategy
16. User receives SMS notification at followup time chosen in step 13 with a simple message and a link
17. User presses link in SMS
18. User is directed to a webpage and presented with content containing a simple visual rating scale on the effectiveness of the previously used strategy
19. User presses the rating reflecting effectiveness of the previously used strategy
20. User is then presented with a webpage that enables SMS notification time preferences to be edited or continued to be sent at current preference time 'Do you want to continue with the current notification schedule or edit the time you receive the next one?'
  * (A) User presses edit button
  * (A) User is presented with same webform as step 6
  * (A) User selects their preference and submits the form
  * (A) User is presented with toast message that confirms preferences have been changed
  * (A) User is then presented with a webpage with a positive and inspiring message
  * (B) User presses continue button
  * (B) User is presented with a toast message confirming they will receive notification as normal
  * (B) User is then presented with a webpage with a positive and inspiring message

This is then repeated from step 8 as the user cycles through testing different behavioural change strategies.

### Considerations 
There are a few areas not yet considered in this approach. Opting out of the services and having data deleted from the service (right to be forgotten). Being able request a visualisation or some type of view of the strategies used and tested.

We envision that this design approach and implementation may be useful for other behavioural change where stand-alone apps are not needed or appropriate.

### Technical Implementation
Yet to update this README
### Wireframes
Yet to update this README


### *1. Patients can message Karuna from various media (Facebook Messenger, SMS, etc.)*
### This will neeed to be extensible but should start with a well-defined list.

### *2. The same patient can contact us on different media at different times, and receive responses on the last medium they used*
### This begs for an API for both sending and receiving messages.
### What happens if the user changes protocols between messages?  

### *3. Messages from patients can get routed to the correct coordinator, based on a set of rules*

### Again with the API from Issue 2.
### This will need a sort of "contact manager" for patients and providers alike.
### What are the rules?
### How can rules be added / changed

### *4. Coordinators have a UI which shows all their routed messages in one place*
### API again
### And also patients?
### 

### *5. Coordinators can respond to messages without worrying about which medium will be used*
### Would there be restrictions though?  If a patient wants to receive messages on media that can't handle certain protocols
### Error checking

### *6. Coordinators can "hand off" a patient to another coordinator*
### API

### *7. Audio and video interactions are recorded and transcribed*
### Where and how?  How are they uploaded?  What formats does this support?  Is this for messaging only?  

### *8. Both incoming and outgoing messages are delivered in-order and exactly-once*
### API

### *9. The external systems for delivering messages can be easily changed*
### Again, limits?

### *10. Various metrics (such as the maximum time a patient waits for a response) can be reported and alerted on*

### Also whether a provider or patient has received a messages, messaging drafts....
</ol>

## General Questions
<ul>
    <li>Who is the target audience?  Caregivers / service providers are not mentioned.</li>
</ul>

## Notes to Self
<ul>
    <li>The API must encapsulate the business logic.  Build from business goals and not technological ones.</li>
    
    <li>Plan for complexity</li>

</ul>

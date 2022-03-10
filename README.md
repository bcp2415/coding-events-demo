# coding-events-demo

1. Purpose:

The app allows a user to store and retrieve lists of events, to store, retrieve, and add *types* of events, and to list events, either all at once, or filtered by type.

2. Current state:

The app currently stores this information about each event created:  name, description, a contact email, and type of event.  New event types can be created and then used as new events are added.  Event types can only be created (not deleted).  Events can be created and deleted.  

3. Future development:

It is planned to add the ability to create and store accounts for people, who will then be able to follow events of interest.  

Each person object will store:  name, contact email, password (hashed), methods for getting and setting these three fields, and a list of events the account is following (along with getter and setter for this list).  Person will be set up with a OneToMany relation to the Event class.

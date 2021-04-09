Who - admin
1) As an admin, I want users to sign up and login to the website/app 
2) As an admin, I want to restrict item requests to only five for different items

 Who - users(requesting)
 1) As a user, I want to requst for an item of my choice by filling a form that shows why I want that item
 2) As a user, I want to recieve a notification if someone has accepted my request
 3) As a user, I want to confirm that I recieved the item so that the donor knows that their item has reached its destination
 
Who - users(donor)
 1) As a donor, I want to look at all active requests by the people so that I know why they want my item
 2) As a donor, I want to filter the requests using the search field so that I can look for any requests for that certain item
 3) As a donor, I want to look at the address of the requests so that I can send them the item
 4) As a donor, I want to send an update to the user about the item so that they know that their request as been fulfilled
 5) As a donor, I want to notified if the user has recieved the item so that I can be satisfied

 Workflow(item requests)
 1) The user should login to their account
 2) The user sees two tabs (barter, request)
 3) User clicks on requst
 4) If the user has no pending requests, he will be taken to a page where he can fill the form to get a item(name, reason)
 5) If this is the first time the user is requesting, the user has to fill in other detials(to show they are not a bot)
 6) If this is not the first time, the user can immediatly request to comfirm the address.
 7) If the user has a pending request, he will see a message that the earlier request is still pending and cannot request for another item until the request is accepted of has been deleted.
 8) Upon submitting the request, the user can see the request live on the page 
 
 Workflow(donor)
 1) The donor should login to their account
 2) The donor sees two tabs (barter, request)
 3) Donor clicks on Barter to see requests
 4) Donor can choose filters by the item name 
 5) Donor can see all the details of the request and respond to any request by sending the item or dening
## Place Picker Website
Place Picker is simple website that offers users to choose, save and remove Touristic Locations they want to visit. It utilizes connection with DataBase using HTTP requests. This website offers certain features such as: 
* Displaying place names and images from connection with backend by sending _**HTTP REQUESTS**_,
* Transforming fetched Data according to user's location via _**geolocation**_ , _**useEffect**_ and _**async/await**_ without causing infinite loops,
* Sending and storing user's Data to dataBase by _**PUT**_ method,
* Ability to delete desired part of User's Data from dataBase from User Interface,
* Handling Loading and Error states,
* Using Optimistic updating method to display dataBase changes

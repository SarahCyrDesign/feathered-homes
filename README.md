# feathered-homes
This is a REACT and Rails project that allows users to anonymously place their birds up for adoption. Once birds are listed, potential adoptees can look through the list of available birds and filter their search by a bird's breed. This project was made to bring awareness to the all-time high number of unwanted parrots in the U.S. who in return remain permanently homeless.

# [REACT with Redux Client](https://github.com/SarahCyrDesign/feathered-homes-client)
The client makes use of Redux to return state based off of actions that are
dispatched for immutable state. We can then share the state amongst a container and it's 
components. The App renders out components such as 'About', 'Birds' and 'Sanctuaries'.
You can even show some love to the birds by 'Adding hearts' to their profiles in real time.

# [Ruby API](https://github.com/SarahCyrDesign/feathered-homes-api)
This API serves as a a tool to return JSON and the database stores created birds and user accounts.
The Geocoding Gem is used by looking up addresses against the Google Places API.
The Paperclip-cloudinary Gem utilizes the Cloudinary server to store bird photos
for potential adoptions.

#Instructions
- Be sure to clone down both the client and the API repositories and run the servers
- For the API: Run the local server separate

```
rails server -p 3001
```

Set up the database

This application may require gems not installed on your local machine. Run

```
bundle install
```
```
rake db:migrate
```

Fill the database with fake users, project, and category info.
```
rake db:seed
```

- For the Client:
This application may require dependencies not installed on your local machine. Run
```
npm install
npm start
```

## Running the tests

There are currently no tests for this repository. If you would like to contribute, please see below.

## Deployment

This app will be deployed to heroku in the future. This section will be updated with the link.

## Contributing

To contribute/ please fork and send me a pull request with any changes

   1) Fork the this repository
   2) Create a local development branch for the new additions/debugging, please rename branch to something along the lines go 'bug_fixes' or 'new_features'
   3) Commit a change, and push your local branch to your github fork
    Send me pull request for your changes to be included

## Authors

* **Sarah Cyr** - *Initial work* - [sarahcyrdesign](https://github.com/sarahcyrdesign)

## License

This project is licensed under the MIT License

## Acknowledgments

* Thank you to all the instructors at Flatiron School for their support, knowledge and utmost passion for code!

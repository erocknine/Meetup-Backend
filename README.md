# README

Tired of being invited to places that are too far for comfort? Well, Hangouts allows friended users to conveniently schedule get-togethers with Yelp suggested restaurants in areas mutually close to all parties.

#Start. 
To begin, run 'bundle install'.  
Then run 'rails db:create', and 'rails db:migrate' to create the postgreSQL database.  
Then run 'rails s' to start local server. This will create endpoints /meetups, /friends, and /users.  

#Hangouts/Meetup Frontend uses React along with styling framework Semantic UI React and CSS Transition Group library. API's included are Geolocation API and Leaflet API. Hangouts/Meetup Backend uses Rails, where our Yelp Search API makes its requests. Be sure to have your own Yelp API key included in an env to be read in the request.

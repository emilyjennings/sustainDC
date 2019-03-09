# SustainDC Planning

The user wants to find out how to live more sustainably in DC through ideas and knowledge of locations that they can visit. For instance, if they want to know which businesses are plastic free, or where there is recycling/composting, or where public transportation makes a car unnecessary.

I can use the foursquare or yelp api to import locations and businesses to choose from.

Users have many comments and likes
Likes belong to users and comments
Comments belong to users, categories and locations
Comments have many likes
Locations have many comments
categories have many comments

migrations:
Users - username, password, tagline
Locations - title
categories - name, comment_id
comments - content, user_id, location_id
Likes - user_id, comment_id

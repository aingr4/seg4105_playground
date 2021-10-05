# Brightspace
### Demand
I receive many notifications on brightspace with many different types. Types can include accouncements, grades, upcomming submission, etc. A lot of the information is important, but some of it is not. I have always wanted to be able to sort my notifications by type. For example, I would like to be able to see all my grade notifications. Or more importantly, see only notifications of type upcomming submission.

### Supply
A simple solution to this problem would be to add a filter function to the drop down notifications. This would allow me to select a property to be used by the filter. I could also mix filters. Ex: Filtering all grade notifications after September 8th.
#
#
# Project
### Demand
My project is called Gamer Matchmaking and the basic premise of the application is to allow users to find other people to play video games with. One of the features we have right now is the ability to select a video game, and a list of potential users to play with is shown. However, similarly to the issue with brightspace, there is no way to filter this list. For example, if I wanted to find a person who speaks french, I would have to scroll down the list and look for someone who spoke french.

### Suply
To solve this problem, I can simply add filters to the search page. I would first add drop down menus at the top of the page (these will be the filters). Then, once the user selects a filter (ex. only people that speak french) the list automatically removes anyone who does not speak french. This function would be implemented client side in Javascript. After receiving the list of users from the db, I can decide to only show those that pass through the supplied filters.
**Eatrium App**

In my school, students have been complaining about the crowds in the Eatrium and 7th Floor Cafe during snack and lunch times. So, I proposed that the best way to combat this was to have a dedicated service that lets students pre-order food. The idea is that by preordering, both of the eating spaces will have food ready to be picked up, limiting the amount of time that students have to queue. The old system had a few downsides: 

- Queueing takes a big percentage of the time that students have to eat. 
- Certain items were often out of stock quickly into the break times.
- Social distancing makes it hard for many students to queue safely. 
- Students are not always clear on which items will be available. 

To solve this problem, I built a server to update the requests from users. This server was written in Java and it used the ACM graphics library. Because mobile phones have limited power, it is much better to send the hard work to a server where the computer hosting it can do the heavy computing. The server then returns the information to the Eatrium App so it can be displayed. Having a fast mobile application will help with tackling the crowding in the eating areas and will also inform students what items are available on any given day. While I could have created a web-based solution, Android Studio is used because it provided a way to publish this app through the Google Play Store. Java as a language provided a helpful framework to create software through an Object Oriented Approach and allowed me to create modular designs that could connect across a network. 

# real-time-processing
utilize websockets to provide realtime alerts between users entering inventory

### Summary:
Our inventory process has a number of steps in order to get a product live and on the floor
- Enter
- Photo
- Price
- Tag
Some steps require coordination and hand off
- Ex: Pricing and photography

### Problem:
Product information is being duplicated or overwritten between member of the team.

### Solution:
In order to keep thing organized and avoid duplicating or overriding work we need an easy way to communicate and alert each other when processing.

### Tasks:
[ ] Create a websocket server
[ ] Update product inventory forms to connect to websocket server
[ ] Send message when product inventory changes
[ ] Receive and display message from websocket when changes occur

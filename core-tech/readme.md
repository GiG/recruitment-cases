#The Core-Tech Challenge

## Create two microservices for real time messages using websockets.

### Functionality
1. The first service should listen for incoming messages through the websocket protocol and when a new one arrives, the message should be published into message queue
1. The second service should listen for incoming messages through the message queue and when a new message arrives, the message should be published to all the subscribers through the websocket protocol

### Other Requirements
* At least one of the services should have tests
* Make sure your code is well structured and maintainable (including tests)
* You can use frameworks and technologies by your choice, but the language for the microservices should be Javascript (node) or Go (or both).
* The source code should be hosted online using github (or similar service)

When you are done, send us a link to your repository on Github/Bitbucket (preferred) or email us your project as a zip.

Note, if you want to shine you can include authentication, use any CI, container based deployment or whatever you think will grab our attention. This is your chance to impress us!

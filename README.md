# Pictionary app

## How to start the different version
|   Scenario   |   Version    |    Commands   |
|:-------------|:------------:|---------------|
|Non-shared        |Cloud         | 1. cd 'Scénario non partagé\Cloud<br>2. node .\server.js |
|Non-shared        |Edge          | 1. cd 'Scénario non partagé\edge\socket.io-p2p-master\examples\pictionary'<br>2. browserify .\src\indes.js -o bundle.js<br>3. node .\server.js |
|Shared    |Cloud         | 1. cd 'Scénario partagé\Cloud<br>2. node .\server.js |
|Shared    |Edge          | 1. cd 'Scénario partagé\edge\socket.io-p2p-master\examples\pictionary'<br>2. browserify .\src\indes.js -o bundle.js<br>3. node .\server.js |

To stop the server the command is ctrl-c.

The traffic controler must be used. If its the case, the client must connect to the port of the traffic controler.

To connect to the game, you must use the ip address of the server device followed by the port used. 

```ip-address:port```

In this table you can found the port of each version

|   Scenario   |   Version    |    Port   |
|:-------------|:------------:|---------------|
|Non-shared    |Cloud         |  8081  |
|Non-shared    |Edge          |  8080  |
|Shared        |Cloud         |  8082  |
|Shared        |Edge          |  8083  |


The client and server scripts can be found by clicking the link in the following table. 

|   Scenario   |   Version    |    Scripts    |
|:-------------|:------------:|---------------|
|Non-shared    |Cloud         | [Client script](\Scénario%20non%20partagé\Cloud\public\main.js)<br>[Server script](\Scénario%20non%20partagé\Cloud\server.js) |
|Non-shared    |Edge          |  [Client script](\Scénario%20non%20partagé\Edge\socket.io-p2p-master\examples\Pictionary\src\index.js)<br>[Server script](\Scénario%20non%20partagé\Edge\socket.io-p2p-master\examples\Pictionary\server.js)  |
|Shared        |Cloud         |  [Client script](\Scénario%20partagé\Cloud\public\main.js)<br>[Server script](\Scénario%20partagé\Cloud\server.js) |
|Shared        |Edge          |  [Client script](\Scénario%20partagé\Edge\socket.io-p2p-master\examples\Pictionary\src\index.js)<br>[Server script](\Scénario%20partagé\Edge\socket.io-p2p-master\examples\Pictionary\server.js)  |


The three setting has to be set : Display draw at False, Display guess box at True for user personal device (device with the guesser or drawer role only)
For the display role, the device has to be set: Display draw at True, Display guess box at Fals eand allow to use the drawing area at False
For the drawing role, the device has to be set: Display draw at True, Display guess box at False and allow to use the drawing area at True
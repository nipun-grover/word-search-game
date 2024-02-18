# Word Search game #

A WPF based word search game where user has to find as many words as they can from a long string within a specified amount of time.

### How it works? ###
This is a game that utilizes TCP/IP connection to connect server and client. The server listents for any connection on a given port
The client connects using the IP of the machine and the port of the server. The server grabs a random file from the game file and 
parses the data. Using a custom protocol, it sends data to the client upon request. 
<br/>


### Tools and languages Used ###
C# for back-end 
WPF (.NET framework 4.8) for front-end
<br/>


### Features ###
<ul>
  <li>TCP/IP connection to handle communicaion</li>
  <li>Multi-page WPF application</li>
  <li>Can play again without having to reconnect</li>
  <li>utilized multi-threading to handle operations, made thread safe using dispatcher</li>
  <li>used config file to store data</li>
  <li>Can handle multiple client connections at once</li>
  <li>Can establish connection over physically different devices</li>
</ul>
<br/>

### Interface ###
#### Game ####
![image](https://github.com/nipun-grover/word-search-game/assets/160381582/4996f3d7-7050-43f7-b9ef-5cba9187c50f)

<br/>

#### final page ####
![image](https://github.com/nipun-grover/word-search-game/assets/160381582/5bf9c788-7fa1-4e72-9f0b-ccfa1cc8e797)




* Writing tests
* Code review
* Other guidelines

### Who do I talk to? ###

* Repo owner or admin
* Other community or team contact

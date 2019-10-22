MTurkAgent

run NewAgentRunner.java
change static prompts: plan_steps.xml
change dynamic prompts: Register.java

In the Bazaar Agent interface, change Room name, e.g., if Room name is test

use this URL to test the agent:
http://bazaar.lti.cs.cmu.edu/chat/test/0/Xu/0/?html=xu
chat/[Room name]/[user ID]/[user name]/[perspective for Mturk agent]/html file [can modify Etherpad, etc.]

In WebsocketChatClient.properties
change this url:
socket_url=http://bazaar.lti.cs.cmu.edu:80

This is the url that the agent enters


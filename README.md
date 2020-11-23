# pndc-proj
order management system
# Introduction:
We are introducing an ordering system with amendments using socket programming which will
help over many things which normal services lacks. Firstly, all systems including order, kitchen,
waiting system they are connected over a network using socket these messages just don’t loss
data if a system is not connected to internet or if connection drops due to any malfunction and
resend it after a connection build this feature quite useful and data is not loss if any system is
turned off as well. Socket programming is a way of connecting two nodes on a network to
communicate with each other. Basically, it is a one-way Client and Server setup where a Client
connects, sends messages to the server and the server shows them using socket connection. One
socket (node) listens on a particular port at an IP, while other socket reaches out to the other to
form a connection. Server forms the listener socket while the client reaches out to the server
# Working and Methodology:
Lets discuss working here first we create client’s socket but before creating client’s socket a user
must decide what ‘IP Address‘ that he want to connect to, in this case, it is the local host. At the
same time, we also need the Family method that will belong to the socket itself. Then, through
the connect method, we will connect the socket to the server. Before sending any message, it
must be converted into a byte array. Then and only then, it can be sent to the server through the
send method. Later, thanks to the receive method we are going to get a byte array as answer by
the server. In the same way, we need an ‘IP address’ that identifies the server in order to let the
clients to connect. After creating the socket, we call the bind method which binds the IP to the
socket. Then, call the listen method. This operation is responsible for creating the waiting queue
which will be related to every opened ‘socket‘. The listen method takes as input the maximum
number of clients that can stay in the waiting queue. As stated above, there is a communication
with the client through send and receive methods.
# Project Domain:
Our project domain will be of a windows form application which will be using, c# .Net socket
programming and for our database we will be using MsSql for backend storage.
# Features:
The features in our project which will be included are that our application will be made on
windows form application and it will have two end which will be a client end and a server end.
The client end will have the option of selecting the whole menu and ordering your food and will

be displayed the whole bill and a confirmation message to proceed for the order to be complete.
That message will be forwarded to the server end where the whole order will be displayed and
there will be three screens a waiting screen, order competition screen and a kitchen screen where
the order will be display.
# Conclusion:
Very useful system minimizes waiting time and helps customer in many ways like the system
display the current expected waiting time in waiting area and show customer when order is
made.
# Run:
Open McDonaldOrderProcess.exe from "OrderProcess/OrderProcess/bin/debug" folder.


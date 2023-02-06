# edairyDistributedSystem
The Edairy Distributed System is a project aimed at providing an efficient and effective way for students to access their assignment list. It eliminates the need for manual compilation of such assignments by automating the process. With this system, students can access their assignment list in a centralized, secure and user-friendly manner. The goal of this project is to make it easier for students to keep track of their assignments and help them stay organized in their studies.

# Instruction
1.Download the file.

2.open project in Netbeans(JAVA).

3.Run Edairy client.

4.Run Edairy Server.

# Running
There is a Java code for an Edairy client application called "Edairy client". The Edairy client is a graphical user interface (GUI) that allows the user to enter data about their daily plan. The user can enter the day, time, activity, description, and plan ID for a particular plan. The data is then sent to a server using a socket connection, and the server stores the information. The application is built using Java Swing for GUI creation, and it uses socket programming for communication with the server.

There is also a simple Java code for a server-side application called "Edairy Server". The code creates a GUI with a JTextArea where messages can be displayed and a ServerSocket that listens on port 4444 for incoming connections. When a client connects, the code creates a PrintWriter and a BufferedReader to send and receive data from the client. The received data from the client is read from the BufferedReader and displayed on the JTextArea until the connection is closed.

## 42 minitalk project

<p align="center"> 
  <img src="minitalk.jpeg" alt="Libft Logo" style="max-width: 100%; height: auto;">
</p>

## Project Overview

<p>
The <strong>Minitalk 42</strong> project focuses on creating a simple client-server communication program using Unix signals. The objective is to implement a messaging system where a client can send messages to a server, one character at a time, and the server can reconstruct and display the message. This project enhances understanding of inter-process communication (IPC), signal handling, and low-level C programming.
</p>

## Features

<ul>
  <li>Implements communication between a client and server using Unix signals <code>SIGUSR1</code> and <code>SIGUSR2</code>.</li>
  <li>Handles the transmission of text messages, one character at a time, via signal-based communication.</li>
  <li>Ensures reliable message delivery by confirming reception of each signal.</li>
  <li>Manages edge cases such as slow message reception and large messages.</li>
  <li>Includes error handling for signal failures and invalid input.</li>
</ul>

## Installation

<p>To install and run this project:</p>

<pre>
git clone https://github.com/mahmoudskhairi/minitalk_42.git
cd minitalk
make
</pre>

## Usage

<p>Here’s an example of how to run the server and client in the Minitalk project:</p>

<pre>
# In one terminal, run the server
./server

# In another terminal, run the client and send a message
./client <server_pid> "Hello, 42!"
</pre>

<p>The client sends the message "Hello, 42!" to the server by transmitting one bit at a time using signals.</p>

## Real examples

<p align="center">
  <img src="minitalk1.png" alt="Libft Logo" style="max-width: 100%; height: auto;">
</p>

<p align="center">
  <img src="minitalk2.png" alt="Libft Logo" style="max-width: 100%; height: auto;">
</p>


<h2 id="contact">Contact</h2>
<p>For any questions, feedback, or issues, feel free to reach out:</p>
<ul>
  <li>Email: <a href="mailto:mahmoud.skhairi@gmail.com">mahmoud.skhairi@gmail.com</a></li>
  <li>LinkedIn: <a href="https://www.linkedin.com/in/mahmoud-skhairi" target="_blank">mahmoud skhairi</a></li>
</ul>

<h2>Happy Coding!</h2>

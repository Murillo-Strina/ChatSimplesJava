# Java Project - TwoUserChat

PT-BR

Este projeto consiste em um sistema de chat simples que utiliza Java para implementar tanto o servidor quanto os clientes. Ele foi projetado para ser uma aplicação de chat com restrição de até dois usuários simultâneos. O sistema oferece as seguintes funcionalidades:

Servidor (Server):

Gerencia conexões dos clientes.
Notifica todos os usuários quando alguém entra ou sai do chat.
Limita o número de conexões a dois usuários simultâneos.
Reaproveita os IDs de clientes desconectados.
Cliente (ClientGui):

Interface gráfica amigável para os usuários.
Permite enviar mensagens para o servidor e receber mensagens de outros usuários.
Implementa ações via teclado:
Pressione Enter para enviar uma mensagem.
Pressione Esc para sair do aplicativo.
Limitações e Mensagens:

O terceiro cliente que tentar se conectar será rejeitado com uma mensagem "Limite de conexões atingido".
Mensagens informando entradas e saídas dos usuários são exibidas no chat de todos os clientes conectados.

EN

This project is a simple chat system developed in Java, featuring both server and client implementations. It is designed as a chat application with a restriction of up to two simultaneous users. The system offers the following functionalities:

Server (Server):

Manages client connections.
Notifies all users when someone joins or leaves the chat.
Limits connections to two simultaneous users.
Reuses IDs from disconnected clients.
Client (ClientGui):

User-friendly graphical interface.
Allows sending messages to the server and receiving messages from other users.
Keyboard actions implemented:
Press Enter to send a message.
Press Esc to exit the application.
Limitations and Messages:

The third client attempting to connect is rejected with a "Connection limit reached" message.
Messages notifying when users join or leave are displayed in the chat of all connected clients.



 client                                                                     webSocket
  socket.onopen() //  create socket                                             MessageHandler
  socket.send()   //  send to server                                            afterConnectionEstablished() // handshake with client 
  socket.onMessage() // receive from server                                     handleTextMessage()            // receive message from client                
                                                                                WebSession.send()              // send message to client
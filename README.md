# chat-application-2-way
In this we can send and receive message using socket programming
in further we all add file transfer and chat it will be user choice and it uses huffman to make it more secure.

do this following on different terminal for same machine

during compile of server code use port
ex: filename portno
    step 1:gcc server.c
    step 2: ./a.out 9898
during compilation of client use ip address and portno
ex: filename ip portno
  step 1: gcc client.c 
  step 2: ./a.out 127.0.0.1 9898(for same machine)
          ./a.out ip address on which server is installed and portno

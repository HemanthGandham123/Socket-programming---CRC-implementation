# Socket-programming---CRC-implementation
Setting up a server and a client side using socket programming and implementing the crc algorithm after converting the data stream to binary form.

The Server is made to be a concurrent server without the use of multithreading.

Also implemented is an error generating algo for the bits in the data being sent from the client to the server and the ACK/NACK sent to the client from the server.

CRC-8 is being used in this current implementation.
(x^8+x^2+x+1)


Running the program :
Open 2 terminals
gcc -o cl.c client in T1
gcc -o se.c server in T2

./server <port_no> in T2
./client <host_name> <port_no> in T1

port_no  : any valid port number eg: 2654,8888,.....
host_name: valid host name/address




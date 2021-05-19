# Banking-System

### Step 1: Compile and store the initailize.c code file using
#### `gcc intitalize.c -o intitalize.out `



### Step 2: Compile and store the server.c code file using
#### ` gcc server.c -o server.out `



### Step 3: Compile and store the client.c code file using
#### ` gcc client.c -o client.out `



### Step 4: Run the initalize.out file (this is used to create the admin account that we will further use to access the the server through the client.out and create and modify further accounts).
#### Use: ` ./intitalize.out `



### Step 5: Run the server.out file with the Port Number (in which you would like the server to run) as the command line argument.
#### Use: `./server.out 3000 `



### Step 6: Execute the client.out file with the Loop back IP Address and the port number in which the server is running as the command line arguments.
#### Use: `./client.out 127.0.0.1 3000 `



### Step 7: Firstly login to the server using the admin details (from the client window), then create some user accounts to access using these created user id’s.

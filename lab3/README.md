If you have not cloned the repository, please input the following command:
```
git clone https://github.com/HydraZeng/COMP4621.git
```
Otherwise, please move to the source repository and pull as follows:
```
git pull
```

Move to directory of lab 3 and compile:
```
cd COMP4621/lab3
gcc pthread_server.c -lpthread -o pthread_server
gcc server.c -o server
```

To run the program
```
./pthread_server
```

You can use the client in lab2 to build the connection

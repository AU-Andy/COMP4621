If you have not cloned the repository, please input the following command:
```
git clone https://github.com/HydraZeng/COMP4621-2019S.git
```
Otherwise, please move to the source repository and pull as follows:
```
git pull
```

Move to directory of lab 4 and compile:
```
cd COMP4621-2019S/lab4
gcc proxy.c -o proxy.o
```

To run proxy.o
```
./proxy.o
```
Set proxy configuration in your browser.
Address is 127.0.0.1
Port should be same as listening port in proxy.c, i.e. 12345 here.

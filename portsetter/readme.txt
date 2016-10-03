Read Me for portsetterTest

1. In the directory that contains portsetter and testportsetter run the following commands to build them:
    g++ -o portsetter.cpp.o portsetter.cpp -std=c++11
    g++ -o testportsetter.cpp.o testportsetter.cpp -std=c++11
    
2. In the bash window type:
    sudo vi /bin/setport

3. Add the a path such as the following that includes the path to the portsetter.cpp.o
    /home/ubuntu/workspace/portsetter/portsetter.cpp.o $1 $2 $3 $4

4. In a bash window type:
    sudo chmod 777 /bin/setport
    
5. Call the program by typing "testportsetter.cpp.o" in the bash window

6.The program should run at this point

*Because testportsetter uses a temporary file it should be included
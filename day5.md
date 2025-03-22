# Task 5

## Install Maven
```bash
sudo apt install maven
```
![image](https://github.com/user-attachments/assets/a1c7b760-d02d-403d-8213-48898f1ce463)


## Configure Jenkins
 - In Jenkins go to `configure jenkins` > `tools`
 - Locate JDK section
 - Uncheck `Install Automatically`
 - Name `Java 17`
 - Go to terminal and enter the command and get the java 17 path:

```bash
update-java-alternatives --list 
```

 - paste the java path in `JAVA_HOME`

![425303064-e71ecf62-8ba8-4cf5-8cd5-1ef1e1cb694e](https://github.com/user-attachments/assets/534b2677-8064-4616-be5d-2198b78ca02d)

## Fork The Repo and build the pipeline
![425414432-f2e44ee3-189b-47cf-9a10-c1d205661051](https://github.com/user-attachments/assets/e852ae16-67ed-408d-82af-85afa43898ac)

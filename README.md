1. download paper server jar file
2. Install java runtime
3. Create link to jar file as `paper.jar`
4. Run:

```console
$ java -Xms2G -Xmx2G -jar paper.jar --nogui
Downloading mojang_1.20.1.jar
Applying patches
Starting org.bukkit.craftbukkit.Main
System Info: Java 17 (OpenJDK 64-Bit Server VM 17.0.8+7-LTS) Host: Linux 4.18.0-425.13.1.el8_7.x86_64 (amd64)
Loading libraries, please wait...
[16:27:11 WARN]: Failed to load eula.txt
[16:27:11 INFO]: You need to agree to the EULA in order to run the server. Go to eula.txt for more info.
```

after first run, you get:

```console
$ tree -L 1
.
├── cache
├── eula.txt
├── libraries
├── logs
├── paper-1.20.1-193.jar
├── paper.jar -> paper-1.20.1-193.jar
├── plugins
├── README.md
├── server.properties
└── versions

5 directories, 5 files
```

5. Edit eula.txt to agree EULA.
6. 

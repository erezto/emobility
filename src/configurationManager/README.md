# Introduction 

The configuration manager generates the configuration files for the charging points and the users of the system. In these files, the personalities of the charging points are defined as well as the user names and their behavior. After generating those files (in the directory generated), the configuration manager inserts the necessary information in the database of the central system. That is, relevant information about the charging points and the user names get registered in the central system.

The configuration manager was mainly developed at the Communication Networks Institute (CNI - Prof. Dr.-Ing. Christian Wietfeld) at Technische Universitaet Dortmund, Germany  in cooperation with the Deutsche Telekom. It is distributed under [GPL](LICENSE.txt) and is free to use.

# Requirements 

1. You need JRE 8.


# How to use?

run: `java -cp ./lib/com.mysql.jdbc_5.1.5.jar:./bin de.tudortmund.cni.ict4es.config.MainGenerator`

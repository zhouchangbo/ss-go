# ss-go
the go language version of SS (Conference's message forwarding server)


1)about    program structure:
package config  #define  util  variable and comm funct
package sslog   #potting   std library " log"
package socket  #most import architecture code
package  db2mysql #potting mysql's api 
package module #proxy forwarding module implementation 
ss_server.go  #the entrance of ss-go

2)build and run
go build ss_server.go #will create a  executable file named ss_server  at this current directory of centos
go run ss_server.go #run ss-go program as foreground
# INCOMPLETE


Go Blockchain - Basic
Copyright 2018 Nathaniel Rand

Update Go Version
- Remove current Go vesion
- $ sudo rm -rf /opt/go
- $ wget https://dl.google.com/go/go1.10.3.linux-amd64.tar.gz
- $ sudo tar -C /opt -xzf go1.10.3.linux-amd64.tar.gz
- Remove Go zipped package

Third-Party Packages - Go
- $ go get github.com/davecgh/go-spew/spew
- - Spew allows us to view structs and slices cleanly formatted in our console.
- $ go get github.com/gorilla/mux
- - Gorilla/mux is a popular package for writing web handlers.
- $ go get github.com/joho/godotenv
- - Gotdotenv lets us read from a .env file that we keep in the root of our directory so we don’t have to hardcode things like our http ports. 

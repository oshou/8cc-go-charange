8gg: 8cc.go
	GOOS=linux GOARCH=amd64 go build -t 8gg 8cc.go

8cc: 8gg
	cp -f 8gg 8cc

clean:
	rm -f 8cc *.o tmp.*
	rm -f 8gg
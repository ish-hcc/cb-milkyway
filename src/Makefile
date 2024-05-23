default:
	CGO_ENABLED=0 go build -o cb-milkyway
cc:
	CGO_ENABLED=0 GOOS=linux GOARCH=arm go build -o cb-milkyway-arm
run:
	./cb-milkyway
clean:
	rm -v cb-milkyway cb-milkyway-arm

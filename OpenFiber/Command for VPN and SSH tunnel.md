- **Instalirati** 
	[Globalprotect openconnect](https://github.com/yuezk/GlobalProtect-openconnect)

- **Komanda iz CLI-a**
```
	sudo gpclient --fix-openssl connect vpnof.openfiber.it
```

	Then an ms sso window should pop up, and after you authorize with your ms account select Italy as the region in the cli.

- **SSH Tunel**
```
	ssh -L 5432:10.246.129.2:5432 -L 8080:10.246.128.126:8080 frinx@10.40.62.156
```

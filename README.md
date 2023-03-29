# Generate JSON for ZCore Network (ZCN) validator

### Download Docker Desktop
https://www.docker.com/products/docker-desktop/

### Download repository:
https://github.com/mosqueiro/zcore-getkey/archive/refs/heads/main.zip

### Commands
- Open ```genkey/pass.pwd``` with text editor and edit with your password

- Run ```docker-compose up``` in the folder where you downloaded the repository

- The JSON will be generated in the folder ```genkey/keystore```

- Copy the the generated address:
![address](https://github.com/mosqueiro/zcore-getkey/raw/main/images/address.png)

- Copy the contents of the folder ```genkey/keystore```:
```
- keystore (folder with your JSON)
- pass.pwd (file)
```
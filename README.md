# Platypus
This is my small project, that I created while I'm learning Go programming language. It's a simple TCP port scanner with two modes. The first mode (TOP-PORTS) scan only 1000 most used ports, and the second mode (ALL-PORTS) scan 65535 existing ports.

This tool is only for educational purposes and fun, works good for perform scans in vulnerable virtual machines. Don't expect good results with real hosts over the net.

![Screenshot](https://img.shields.io/badge/Platform-Linux-brightgreen)
![Screenshot](https://img.shields.io/badge/License-GPL-red)
![Screenshot](https://img.shields.io/badge/Language-Go-blue)

![Screenshot](/Screenshots/screen2.png)
## Installation
```bash
git clone https://github.com/intrackeable/Platypus-Scanner.git
cd Platypus-Scanner
./Platypus
```
![Screenshot](/Screenshots/CAP1.png)
## Example of usage

```go
./Platypus -t 192.168.0.177 -s TOP-PORTS
./Platypus --target 192.168.0.177 --scan ALL-PORTS
```


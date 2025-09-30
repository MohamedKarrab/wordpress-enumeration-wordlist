# wordpress-enumeration-wordlist

![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)
![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)
[![Twitter](https://img.shields.io/twitter/url/https/twitter.com/cloudposse.svg?style=social&label=%20%40_karrab)](https://x.com/_Karrab)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555)](https://www.linkedin.com/in/mohamedkarrab/)

A curated collection of high-value WordPress endpoints, files, and directories for security reconnaissance and penetration testing. 

Avoids noisy, unnecessary entries to give pentesters exactly what they need.

## Usage examples

With `Dirsearch` (recommended)
```
dirsearch -u https://example.com -w wp-karrab.txt
```
<img width="1203" height="649" alt="image" src="https://github.com/user-attachments/assets/65e963e1-0978-458d-98df-5b5df700ad32" />

With `ffuf` 

```
ffuf -u https://example.com/FUZZ -w wp-karrab.txt
```

With `Gobuster`
```
gobuster dir -u https://example.com -w wp-karrab.txt
```


## Contributing

Contributions are welcome — submit issues or pull requests.


## License

This project is licensed under the Apache License, Version 2.0. See the `LICENSE` file for details.


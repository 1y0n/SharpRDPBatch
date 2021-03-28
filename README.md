# SharpRDPBatch

在三好师傅 [SharpRDPCheck](https://github.com/3gstudent/SharpRDPCheck) 的基础上加了批量检测，原版权属于三好师傅。

[直接下载](https://github.com/1y0n/SharpRDPBatch/releases/download/0.1/SharpRDPCheck.zip)即可使用，下载地址：https://github.com/1y0n/SharpRDPBatch/releases/download/0.1/SharpRDPCheck.zip

```
Usage:
      SharpRDPCheck.exe <RDP ServerIP> <RDP ServerPort> <mode> <user> <password>
      <mode>:
      - plaintext
      - ntlmhash

Eg:
      SharpRDPCheck.exe 192.168.1.1 3389 plaintext user1 password1
      SharpRDPCheck.exe 192.168.1.1 3389 ntlmhash user1 c5a237b7e9d8e708d8436b6148a25fa1
      SharpRDPCheck.exe 192.168.1.1-255 3389 plaintext user1 password1
      SharpRDPCheck.exe 192.168.1.1-255 3389 ntlmhash user1 c5a237b7e9d8e708d8436b6148a25fa1
```

![image](https://user-images.githubusercontent.com/17820255/112757900-36ef4080-901e-11eb-9153-01742061aaa3.png)

# SharpRDPBatch

在三好师傅 [SharpRDPCheck](https://github.com/3gstudent/SharpRDPCheck) 的基础上加了批量检测，原版权属于三好师傅。

直接下载即可使用。

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

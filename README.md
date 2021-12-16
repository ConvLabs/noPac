# noPac

## This Fork now supports more encryption schemes (default is now AES256) for better OPSEC and improved usage in cases that the target domain disabled RC4 support.

CVE-2021-42287/CVE-2021-42278 Scanner & Exploiter. Yet another low effort domain user to domain admin exploit.

If a Domain Controller is vulnerable it will return a TGT without a PAC, so keep an eye on small size tickets.

![](Images/scan.png)

![](Images/exploit.png)

## Mitigation

Patch your Domain Controllers!

## Credits

[cube0x0](https://twitter.com/cube0x0) for the [original noPac](https://github.com/cube0x0/noPac) code

[Charlie Clark](https://twitter.com/exploitph) for his Rubeus fork and [Kevin Robertson](https://twitter.com/kevin_robertson) for SharpMad

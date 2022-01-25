+++
categories = ["tech"]
date = "2022-01-25T09:40:00-05:00"
description = ""
tags = [
  "devops",
  "infrastructure"
]
title = "My Yubikey setup"
draft = true

+++

[liyanchang-yubikey-setup]: https://github.com/liyanchang/yubikey-setup
[disable-otp]: https://github.com/liyanchang/yubikey-setup#turn-off-otp---aka-the-random-letters-when-you-accidentally-touch-it


```
% ykman config usb --list
OTP
FIDO U2F
FIDO2
OATH
PIV
OpenPGP
YubiHSM Auth
% ykman config usb --disable OTP
Disable OTP.
This will cause the YubiKey to reboot.
Configure USB? [y/N]: y
% ykman config usb --list
FIDO U2F
FIDO2
OATH
PIV
OpenPGP
YubiHSM Auth
```

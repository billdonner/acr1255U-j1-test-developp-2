#  Demo Project to interact with ACR 1255 and ACR 3901Readers

The ACS manufacturer produces RFID card readers compatible with iOS. On its website (), it is possible to download the SDK with a project demo coded in Objective C. This project is a complete translation into Swift 3.

## Links
https://www.acs.com.hk/en/products/403/acr1255u-j1-secure-bluetooth%C2%AE-nfc-reader/#downloads 

##### upgraded to xcode10.1, ios 12.1, and swift 4.2 
Dannys code 8 mar 2019

Goal = upgrade to current Swift and Xcode and see what runs

https://github.com/welovehangers/acr1255U-j1-test

downloaded , because cloning wanted Xcode-beta


running Xcode 10.1 from mac app store

builds with one error - ABDHex.h not found even though I see it, but this is only needed by test.h AND THE build carries on successfully


there 16 warnings about deprecations etc, and an offer to upgrade to swift 4.2


10 Mar 2019

— removed UIAlertView to build with no deprecations

- crashed at         if  (bluetoothReader?.isKind(of: ABTAcr1255uj1Reader.self))!{  when modifying TxPower in btdemo

stashed in github
moving to laptop

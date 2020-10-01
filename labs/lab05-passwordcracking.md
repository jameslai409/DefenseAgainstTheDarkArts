# Lab: The Fall 2020 Password Cracking Contest

## Instructions

Crack as many of the password hashes (below) that you can.

For students in the COMP / OMSCS 116 Introduction to Security courses at Tufts University, submit your pot of passwords using `username:password` format for each password that you crack on Canvas.  One `username:password` per line.  Be sure to describe your cracking methodology.  You will have unlimited submissions and an entire month to do this lab.  Only inline (cut-and-paste) submissions will be accepted for this lab.

## The Password Hashes

`morocco:$1$vg8PBEJ7$ivM1BTtIJzZkgLBGElBQ61:1003:1003:,,,:/home/morocco:/bin/bash
tunisia:$1$GpnNHYmW$Z7A9RWC3GlqTlMDuL4cuE/:1004:1004:,,,:/home/tunisia:/bin/bash
columbia:$1$VG.s5MUf$qkgFOcYZViJ5ZDfXtumWd1:1005:1005:,,,:/home/columbia:/bin/bash
germany:$1$tqzG31dC$6h4sc9SYz1gYSuG6pW4390:1006:1006:,,,:/home/germany:/bin/bash
japan:$1$i4D6lAHD$LzC5sjtda1q93Gy9s99nE.:1007:1007:,,,:/home/japan:/bin/bash
denmark:$1$P0KrA4kP$XSU3ZL.HqFZa/wyeokJCD1:1008:1008:,,,:/home/denmark:/bin/bash
serbia:$1$UOQSHvjV$V9Wn/IW8zyMS0l2zg2gdb.:1009:1009:,,,:/home/serbia:/bin/bash
belgium:$1$DajT9Q7N$zkOrFuQnsg7fWOYGpwtJe.:1010:1010:,,,:/home/belgium:/bin/bash
uruguay:$1$aaPR99jr$1V2ijvzLNQCWRhUBbgziM1:1011:1011:,,,:/home/uruguay:/bin/bash
portugal:$1$bBZ262cY$fwKbPMaKbMnoZcg6ra8Wk/:1012:1012:,,,:/home/portugal:/bin/bash
panama:$6$diypI1PcL0TVj6U7$XfrpfXl/k3UHt2JFh.Il.6Jwq8.Fy3FsscubcOP9e8u6IUvx0XFNIBvQzL8vUd6tlpW5.lx7vPfEcJOUcxjs5.:1002:1003:,,,:/home/panama:/bin/bash
saudiarabia:$6$LI/Z7fa2BRRcGfDL$mdBsTeGAE.fr1PAazfFfZPoOSUfQ9vD2l1OvuAfYgraKwD4Rwx2Xi8sxKgL.7Kuz9XEhbNwnI0Yq3EQHO7G6A0:1003:1004:,,,:/home/saudiarabia:/bin/bash
egypt:$6$X4dTOMfZLSPGuYgF$LzM84eu.RdvrOY5rG6lk9BhJBkNBrBQzNDdMI9/AFzxHmjyVRlfCzs6HTtGw6xwijv9sdHpu3qebBrwWG9HsV.:1004:1005:,,,:/home/egypt:/bin/bash
argentina:$6$KOTowzvITs2wRp9c$C38sXIewTdzwlGkXvqqPvpkp6cosbZ2GpQ83vEId0FiT9OJq4G93YHqJ52fLoXpOw5eExidtgPcngpSF5TfrM/:1005:1006:,,,:/home/argentina:/bin/bash
mexico:$6$9MarWt5tQKngxBE0$f4/lAP61h6KHlH8pagDOTyG7qRGvH9dcoxDx7/7j6NSipQyoY4CSN.ds8tjdwEd3saldnNiOD9TdFUMIBdRgn1:1006:1007:,,,:/home/mexico:/bin/bash
france:$6$oFUCFd59p7FK/uLV$qvO6XkZY5tVL2rnmRVSShc2FLV3mf7pIpNo.LICRAilHlBFszDXMiwe/NsxsjL6GXlWoygU9a7sRqtgMTcC2H/:1007:1008:,,,:/home/france:/bin/bash
switzerland:$6$TKPFr/MahRd/qsNm$5e4YKbMj54OSTGV4/h4pGmAgGMz3w/wayADKNt36.eGxEQ0vHf6nOTdo5wehz6vLIzLazt8214jq4vmRXKEBr1:1008:1009:,,,:/home/switzerland:/bin/bash
australia:$6$7FnuGKJ1tOoQTTQx$2MHs0EX29Bz5edJGeVd4EMMmG80SbhBGfhn/6lJNAtKOKDWPuzgBcbUZbhe4Dgy9CCGtwHYsfKEEHDFW9IxZP.:1009:1010:,,,:/home/australia:/bin/bash
sweden:$6$/5DMsJvsctGN0.E1$sDjqfGiqj290vI2YyMi/.cI5p4OMeGMUTjfsXX5TIht0lb9lUBhBo5gg/LV347tzXD5qmOyHYAkbAxdfDN4zo/:1010:1011:,,,:/home/sweden:/bin/bash
peru:$6$n91QW5uCJxjxGGxB$SsHokDU9Oh8YXEYxS2ewvs0b5O0dFPjcHBE90P1YIrHkOTMvAXsDRWWxEC9sniRyEJw..LYEUPrua0nk2FjNv1:1011:1012:,,,:/home/peru:/bin/bash
brazil:1010:aad3b435b51404eeaad3b435b51404ee:8855a8072eefc1b41d77f8ef46db42e1:::
costarica:1003:aad3b435b51404eeaad3b435b51404ee:735636e07397f11a6b658543d12f2bce:::
croatia:1004:aad3b435b51404eeaad3b435b51404ee:a46b4f30962158c6f78ac8b3a88629cd:::
england:1008:aad3b435b51404eeaad3b435b51404ee:959bbfc0eafaa19721282077899b572c:::
iceland:1006:aad3b435b51404eeaad3b435b51404ee:b09679d24e67343b6650049f0eb854f7:::
iran:1001:aad3b435b51404eeaad3b435b51404ee:3637d26785ba5327d3dff5a3b2c8fa50:::
nigeria:1005:aad3b435b51404eeaad3b435b51404ee:2071cd3891d0ad5bc2b38f80274d8c85:::
senegal:1009:aad3b435b51404eeaad3b435b51404ee:c8a188f6c0c4e55d66d3d51cf2fe5103:::
southkorea:1007:aad3b435b51404eeaad3b435b51404ee:28ed64da632d774ad45f17acc851a643:::
spain:1002:aad3b435b51404eeaad3b435b51404ee:3c19c71d5726e1f3008b040c394219ce:::`

## Rules

* Absolutely no collaboration of any kind.  This is an individual lab.
* Please be sure to keep records of your cracked passwords, including password pot, screenshots, and logs in case you are questioned.
* You are allowed to use as many password crackers and word lists that you want and that you can find.
* You are allowed to use any infrastructure to crack the passwords (e.g., Amazon Web Services, as many graphic cards that you can afford). Please note that you are responsible for all costs.
* While you have unlimited submissions, be sure to also submit previously submitted passwords.
* You are strongly urged to submit early and often. Only last submission will count.
* The number of passwords to crack in order to get full points on this lab won't be announced until the final week of the competition.
* This contest will end on Thursday, November 5th at 11:59 PDT.
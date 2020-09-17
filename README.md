# TakeMyFlag
An Android based CTF to improve and hone your dynamic analysis skills!
![CTF](https://d19ta9rijs3cxg.cloudfront.net/wp-content/uploads/2019/05/Nulab-Capture-the-Flag-CTF-Challenge-Blog.png)

## Rules:
1. No using Frida for dynamic modification / hooking.
2. No manual invoking of **activities** via drozer / AM.

## Goal:
Your goal is to pop the FinalActivity activity on your device, keeping rule number 2 in mind.

## Note to player:
This isn't an Android CTF where you can just decompile the APK, de-obfuscate some encrypted keys from strings.xml, read some static values from a random class etc. In order to solve this CTF, you will need to think very creatively, as most of the stages need to be solved via pure dynamic analysis. I have neither hidden any "gotchas" in the code, nor have I obfuscated the code. 

Good luck and have fun!

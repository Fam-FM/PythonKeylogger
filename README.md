# PythonKeylogger

Keyloggers are programs that capture a user's keystrokes. They can be used to keep logs of everything you press on the keyboard but also for malicious purposes.

The keylogger shown here is a basic keylogger with not as much functionality as the ones available in the market today. It captures your keystrokes and saves them in a file "keylogger.txt".

It then sends the file's contents (i.e. the keystrokes) to your email id.

With some extra lines of code, it can also send the keystrokes at regular intervals.

**** This is not executable, so you have to explicitly call it ****

SYNTAX : python keylogger.py

[NOTE: You need to press ESC key to exit out the keylogger.]

You need to have pynput , smtplib and ssl installed.

While python comes with the library smtplib and ssl preinstalled, you can install pynput with : pip install pynput

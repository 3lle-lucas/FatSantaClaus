# FatSantaClaus🎅🏼

A tool to get cookies using chromium debug mode and Discord to exfiltrate them. Built for **security research** and **educational purposes only**, not for shady stuff.
Second module of the final project, the functions are more defined and granular to allow you to add them easily to your own projects.

# Demo👀



https://github.com/user-attachments/assets/b1263d26-0bc9-4adc-bf92-f8b42bf795b0

# Why Discord❓

From the first module I've done some improvements (I will soon update the first module with this feature).
Now, instead of sending a bunch of records at a time to not reach the rate limit, now a file get uploaded allowing us to dump everything with just one call.
Currently the limit is 25Mib but in January 2025 will be decrased to 10Mib🥹 (not a big issue, using this tool the files I've uploaded don't reach 1Mib )

Doc: https://discord.com/developers/docs/change-log#default-file-upload-limit-change

# How does it work?⚙️

- It opens the specified browser in debug mode that provides an API where you can extract all the cookies.

- It sorts the cookies by domain.

- It creates a file on the host system with the cookies (not encrypted) and upload it to a Discord webhook.

- It removes the file (We like clean works)

# Improvements 🙏🏼
Adding the flag **--headless** you can start the debug mode without opening the GUI of the browser but the cookies don't get loeaded so you dump nothing.
I've tried many methods but none of them worked. Do you wanna help me improve this tool?


# Disclaimer 🚨
This tool is provided strictly for educational and research purposes. I am not responsible for any misuse. Unauthorized access to systems and data is illegal. Use this responsibly and only in environments where you have explicit permission.

👾 Enjoy hacking (ethically)! If you find bugs or have suggestions, feel free to contribute!

💬 Join the community! Have questions or want to chat? Join my Discord server: Join here

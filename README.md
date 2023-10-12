# NovoLoader - A Remote Access Trojan (RAT)

**Note: The original repository for NovoLoader is currently private, as it is actively being developed. Updates and additional resources will be made available soon.**

**Disclaimer: This project is created for educational purposes only. It is not encouraged or endorsed for use in any malicious activities. The creator is not responsible for any misuse of this software. Any unlawful use may result in criminal charges.**

## Overview

NovoLoader is a Remote Access Trojan (RAT) designed for research purposes. It should not be used for any unauthorized, harmful, or malicious activities. This project is meant to help individuals understand the potential security risks associated with RATs and learn about cybersecurity from a defensive standpoint.

The RAT consists of three main components:

1. **Command and Control (C2):** This component is responsible for managing the RAT and controlling its actions. It serves as a centralized point of communication for the client and server components.

2. **HTTP Server:** The HTTP server is responsible for handling incoming connections, providing the necessary infrastructure for communication, and facilitating data exchange between the client and the C2.

3. **Client:** The client, also known as the Test Client, is a basic implementation of the RAT. It serves as an example of how to interact with the C2 and how a new client can be built directly from the C2.

## Features

As of the current state of the project, NovoLoader does not offer an extensive range of features. The primary goal of this project is to provide a foundation for research purposes and to help users learn about RATs from a defensive perspective.

## Legal Disclaimer

This project is developed with the intention of enhancing knowledge about cybersecurity, ethical hacking, and defending against cyber threats. It is essential to emphasize that the usage of NovoLoader for any illegal, unethical, or malicious activities is strictly prohibited. The creator of NovoLoader will not be held responsible for any misuse of this software. Any individual who uses NovoLoader for malicious purposes may face legal consequences, and the responsibility will fall entirely on the individual who engaged in such activities.

## License

This project is distributed under the MIT License © 2023 ZribeDev. Please review the license to understand your rights and responsibilities when using or modifying this software.

## Credits

The executable and DLL merging in this project was made possible by the "netz" tool, available at the [netz GitHub repository](https://github.com/madebits/msnet-netz-compressor). We acknowledge and thank the creators of "netz" for their invaluable contribution. Additionally, we credit Quasar RAT for the design inspiration; no code was borrowed, but the design draws from Quasar RAT.

# Change Log
## Version 0.9.0
Version 0.9.0 marks the first beta release and introduces the foundational components of the application, including:
* Command and Control (C2)
* * Builder
* * Client Control
* * Settings Page
* * Action
* * * Message Box
* * * Shutdown / Restart
* * * Run Shell Commands
* * * Download and Run Files on Disk
* * * Run .NET Files in Memory
* HTTP Server
* Demo Client

## Version 0.9.1
Version 0.9.1 is the second beta release, addressing and resolving several issues from the initial 0.9.0 version. Changes and additions include:
* The requirement to include "http://" or "https://" at the start of the host has been eliminated. In the new update, you can simply check the "Secure" box.
* The "Compile as DLL" option has been concealed due to concerns of potential misuse. It's important to be aware that this option is presently non-functional. The reason behind this is that the RAT necessitates a DLL to be located in the same folder as the compiled DLL, and enabling this feature will cause the DLL to fail in connecting to the server.
* The "Hidden Task" option has been added to conceal the Console Window in the compiled EXE. This enables the generation of Test Stubs with a shown/hidden console.
* Operating System information display has been fixed to accurately reflect the operating system, such as "Microsoft Windows 11 Pro - 64-bit."
* A notification option has been included for user connection alerts.
* Port modification is now possible within the settings.
* A sending issue has been resolved, allowing communication with computers that aren't your own.
* The "Test Connection" option is now available in the settings.

## Version 0.9.1.1
Version 0.9.1.1 added the following:
* Task Manager
* BSOD Action (Administrator Only)

## Version 0.9.1.2
Version 0.9.1.2 added the following:
* Remote Desktop (View Only)
* UDP Flood
* VM Checker

# Social:
[NovoLoader Reddit](https://www.reddit.com/r/novoloader)
[NovoLoader Gitbook](https://zribedev.gitbook.io/novoloader/)

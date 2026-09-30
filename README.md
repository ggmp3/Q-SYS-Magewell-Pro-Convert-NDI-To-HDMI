# Q-SYS-Magewell-Pro-Convert-NDI-To-HDMI

- Magwell Pro Convert NDI To HDMI Q-Sys User Component (REST API)
- Written by Glen Gorton
- Tested with Firmware version: 1.1.938

### 30th September 2026 - Glen Gorton
- Found that the 'NDI to HDMI' device, when upgraded to firmware v1.3.24, was responding with addtional data in the 'Set-Cookie' response. Within the Result() function, modified the 'if headers["Set-Cookie"] then' function so only the sid is set as the session_id variable.
- Also added a loop in the Result() function to print the headers table.
- Tested with Firmware version 1.3.24
- Tested with Q-Sys Designer v10.4.1

![image](https://github.com/ggmp3/Q-SYS-Magewell-Pro-Convert-NDI-To-HDMI/assets/98933978/141e8230-b271-47a1-9177-290c0328987c)

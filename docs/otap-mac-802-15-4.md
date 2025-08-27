# OTAP MAC 802.15.4

To perform a MAC 802.15.4 demo, follow the next steps:

1. Download the latest [Software Development Kit](https://mcuxpresso.nxp.com/en/select) for your board.

2. Flash the OTA server application onto the server device using Firmware Loader.

3. Flash the OTA bootloader and the OTA client applications onto the client device using Firmware Loader.

4. If the client device is plugged in, you can optionally open a PuTTY serial session to monitor the OTA transfer from the server.  
After the transfer from server to client begins, a progress bar appears in PuTTY.  
After the transfer is complete, the client device is reset, and a message appears.

5. Press any switch on the OTAP Server.

6. Press any switch on the OTAP Client.

7. Select the server COM port from the left panel and then click the **`Connect to OTAP Server`** button.

8. Drag and drop or browse for a file to be sent OTA. After selecting a file, a new window appears prompting to choose the processor of the development board.

9. To begin the OTAP transfer process, click **`Start OTAP`** . After the transfer begins, RX/TX messages appear in the log on the right side.

[⬅️ Back to Table of Contents](README.md/#table-of-contents)
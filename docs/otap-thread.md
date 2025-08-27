# OTAP Thread

To perform a Thread demo, follow the next steps:

1. Download the Software Development Kit for FRDM-KW41 from [MCUXpresso](https://mcuxpresso.nxp.com/en/select).

2. Write the OTA server application onto the OTAP server device using Firmware Loader.

3. Write the OTA bootloader and OTA client applications onto the OTAP client device using Firmware Loader.

4. Plug in the OTAP server device and click the **`Connect to OTAP Server`** button.

5. Start a new network using the **`Create Thread Network Command`** button.\
![Create Thread network command](../images/image-3.png)

6. Start the commissioner using the **`Start Commissioner Request Command `**button.\
![Sync Steering Data Request command](../images/image-1.png)

7. Add expected joiner using the **`Add Expected Joiner Request Command`** button.\
![add expected joiner request command](../images/image-2.png)

8. Synchronize steering data using the **`Sync Steering Data Request Command`** button.\
![synchronize steering data request command button](../images/image-4.png)

9. Plug in the OTAP client device and press any switch to allow it to join the network.

10. Add the file to be sent OTA using the interface, or simply drag and drop it.

    ![OTAP Thread Processor Selection Window](../images/image.png)

11. To start the OTA transfer process, click **`Start OTAP`**.

[⬅️ Back to Table of Contents](README.md/#table-of-contents)
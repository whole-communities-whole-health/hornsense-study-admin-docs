## How to set up new admin panel administrators
Existing admins must create accounts for new admins and help with the initial multi-factor authentication set up. This process can be done with these steps:

### 1. Existing admin creates the account credentials for the new admin
  <img width="1438" alt="image" src="https://user-images.githubusercontent.com/23275363/236326820-6f335444-3187-4048-9239-db29210c0c47.png">

### 2. Existing admin links the new admin's MFA device
After the new admin account is created, the existing admin who created the account will need to assist with MFA setup.

- In a video call, the existing admin clicks `Link Device`:
    <img width="1410" alt="image" src="https://user-images.githubusercontent.com/23275363/236327113-3f862383-2ce4-4a0a-bd5e-e5e369e9e954.png">
  
- The **new** admin will need to use use an MFA app to scan the QR code. [Authy](https://www.authy.com/download/) is more user-friendly than DUO and is recommended for this purpose. After the new admin scans the QR code, the new admin gives the generated code to the existing admin. The existing admin then enters the code in the `Token` field:
    <img width="1399" alt="image" src="https://user-images.githubusercontent.com/23275363/236327971-77b4eb89-dd06-4289-97ce-893249f4a5c3.png">

- The existing admin clicks `Confirm` and the MFA set up is complete. The new admin can now log into the admin panel and can change the password using the link next to the username at the top right of the page.


### How to change device
After the initial setup, the device can only be changed by the account owner. Other admins won't be able to change the MFA device. The `MFA SETUP` link on the top right header is used for this purpose:
<img width="1420" alt="image" src="https://user-images.githubusercontent.com/23275363/236329655-ca045910-a3fe-472b-9403-562769d10f77.png">

Use the new device to scan the QRCode, and enter the code in the `Token` field, and then you are done.

`Note: If you lose your old device or forget your password, you won't be able to log into your account. In this case, you will need to have a new admin account created for you.`
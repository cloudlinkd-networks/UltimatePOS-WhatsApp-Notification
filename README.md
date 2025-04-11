<p align="center">
<img alt="Logo banner" src="https://github.com/cloudlinkd-networks/whatsapp-notification/blob/main/logo.png"/></p>
</br>

# CloudLinkd Ultimate POS WhatsApp Notification

![Example dashboard](https://raw.githubusercontent.com/cloudlinkd-networks/WHMCS-WhatsApp-Notification/refs/heads/main/screenshot-4.png)
</br></br>

-> Step 1 : Go to Settings Tab -> SMS Settings

-> Step 2 : SMS Service: -> Other

-> Step 3 :

- URL: https://wa.cloudlinkd.com/api/send/whatsapp

- Send to parameter name : recipient

- Message parameter name : message

- Request Method : POST

- Parameter 1 key : secret
- Parameter 1 value : YOUR-CLOUDLINKD-API-SECRET from your https://wa.cloudlinkd.com account

- Parameter 2 key: account
- Parameter 2 value: YOUR-CLOUDLINKD-WHATSAPP-ACCOUNT-UNIQUE-ID from your https://wa.cloudlinkd.com account

-> Step 4 : Testing -> enter-your-whatsapp-number -> Send Test SMS

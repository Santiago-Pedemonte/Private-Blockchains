# Transaction Guide

After connecting to the custom network in MyCrypto, it can be tested by sending money between accounts.

  * Select the `View & Send` option from the left menu pane, then click `Keystore file`.

  ![select_keystore_file](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/References/Images/select_keystore_file.png)

  * On the next screen, click `Select Wallet File`, then navigate to the keystore directory inside your Node1 directory, select the file located there, provide your password when prompted and then click `Unlock`.

  * This will open your account wallet inside MyCrypto. **Note:** The account can also be unlocked with the `Private Key`.
    
  * When you log into a pre-funded wallet, you will see the balance that was allocated to this account in the genesis configuration; however, these are just for testing purposes.   

  ![keystore_unlock](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/References/Images/keystore_unlock.gif)

  * In the `To Address` box, type the account address from Node2, then fill in the amount of ETH you want to send:

   ![transaction send](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/References/Images/transaction-send.png)

  * Confirm the transaction by clicking "Send Transaction", and the "Send" button in the pop-up window.  

  ![Send transaction](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/References/Images/send-transaction.gif)

  * Click the `Check TX Status` when the green message pops up, confirm the logout:

  ![check tx](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/References/Images/check-tx-status.png)

  * You should see the transaction go from `Pending` to `Successful` in around the same blocktime you set in the genesis.

  * You can click the `Check TX Status` button to update the status.

  ![successful transaction](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/References/Images/transaction-status.png)


# ProteccButWithMasterKey
It protecc stronger with master key

Protecc your 2FA with additional layer of master password.

![](https://media.discordapp.net/attachments/753345992543305808/997802740203933758/unknown.png)

## Difference from Protecc

You also need to type in the master password

## How to set master password

1. On First Run, you can type in the master password that you will use forever.

2. After the first run, you should type in the password you typed in the first time.

## How Master Key Works

All 2FA keys will be encryped using AES encryption with the hash of master password you typed when you open the app. Therefore, in order to get the correct 2FA 1-time-password code, you need to type in the correct password.

You can technically use multiple master password for each of the 2FA account. To do this, you can clsoe and enter a different master password and add account.

## Behavior

Note that if you

1. typed in an incorrect password OR
2. use two or more of different master passwords OR
3. both

You will not get the code for all accounts until you unfocus/refocus the window or you need to wait for several seconds until you get the code.

If the master password is the different password you use to create the specific 2FA account, you will get an incorrect 2FA code. This is becasue there is no way the app knows if you typed in the correct password or not.
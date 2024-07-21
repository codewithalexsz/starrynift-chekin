- Before using this script, make sure you have OpBnB in the wallets for gas fee 0.1$OpBnb is eonugh

- Open Github Codespace/Gitpod/Any Other Terminal

Paste this below command, also before pasting command, you should verify these codes in `starry.sh` file

```bash
wget https://raw.githubusercontent.com/codewithalexsz/starrynift-chekin/blob/main/starry.ph && touch privatekeys.txt && nano privatekeys.txt
```

You need to import your private Key here (1 Private key in each line)

Now press Ctrl+X then Y and then press Enter

You can verify whether you have successfully entered your wallets' private key or not using cat privatekeys.txt

Now use these commands

chmod +x Plume.sh && ./starry.sh

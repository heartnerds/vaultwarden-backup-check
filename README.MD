# **Check your self hosted vaultwarden backups**

This tool automatically copies the latest backup, decrypts it, launches a vaultwarden session and destroy all of the data generated.

### **Configuring docker-compose**

Match the `user` with your **UID** and **GID**.

### **Configuring check script**

Update `BACKUP_PATH` to match the location of your backups.

### **Run the script**

Run with `./check`

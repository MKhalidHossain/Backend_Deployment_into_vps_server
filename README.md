# Backend Server Information

> ⚠️ **Important:** Never commit this file to a public GitHub repository. Add it to `.gitignore` or keep it in a private repository because it contains sensitive credentials.

## 🖥️ Server Details

| Item | Value |
|------|-------|
| SSH Host | `YOUR_SERVER_IP` |
| SSH User | `root` |
| SSH Port | `22` |
| Root Password | `YOUR_ROOT_PASSWORD` |

---

## 🔑 SSH Key

### Public Key
```text
PASTE_YOUR_PUBLIC_KEY_HERE
```

### Private Key
```text
PASTE_YOUR_PRIVATE_KEY_HERE
```

---

## 📂 Project Directory

```bash
cd /var/www
```

---

## 🔌 Connect to Server

### Using Password
```bash
ssh root@YOUR_SERVER_IP
```

### Using SSH Key
```bash
ssh -i ~/.ssh/YOUR_KEY root@YOUR_SERVER_IP
```

---

## 📋 Useful Commands

### Go to Project Folder
```bash
cd /var/www
```

### List Files
```bash
ls -la
```

### Check Current Directory
```bash
pwd
```

### Restart Nginx
```bash
sudo systemctl restart nginx
```

### Restart Apache
```bash
sudo systemctl restart apache2
```

### Restart PM2
```bash
pm2 restart all
```

---

## 📝 Notes

- Replace all placeholders (`YOUR_SERVER_IP`, `YOUR_ROOT_PASSWORD`, etc.) with your actual values.
- Keep this file **private**.
- Never share your root password or private SSH key publicly.

# Linux Users and Groups

## What I Learned

Linux uses users and groups to manage access to files,
directories, and system resources.

## Creating a User

I created a user called `developer`.

```bash
sudo useradd developer
```

## creating a group
```bash
sudo groupadd developers
```

## Adding a User to a Group
```bash
sudo usermod -aG developers developer
```
## Checking User Information
```bash
id developer
```

## What I Learned
I learned how Linux users and groups are used to manage
access and permissions on a Linux system.

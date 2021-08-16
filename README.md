# Change-User-Profile
Change user profile folder name (When you give your laptop to another person)

### Check Accounts 

Steps :

1. Delete all the apps & clear the folders in the Users Account corresponding folder.

2. Open `Command Prompt` in `Admin` 

```cmd
net user
```

3. Actiavte Administrator Account

```cmd
net user administrator /active:yes
```

4. Sign Out from existing account & Sign in through Administrator Account

5. Rename the user account name 

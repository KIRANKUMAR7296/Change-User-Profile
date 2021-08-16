# Change-User-Profile
Change user profile folder name (When you give your laptop to another person)

### Check Accounts 

Steps :

1. Delete all the apps & clear the folders in the Users Account corresponding folder.

2. Open `Command Prompt` in `Admin` 

```cmd
net user
```

3. `Activate` Administrator account.

```cmd
net user administrator /active:yes
```

4. `Sign out` from existing account & `Sign` in through Administrator account.

5. `Rename` the user account name. 

![Manage User Account](https://user-images.githubusercontent.com/61859813/129513337-d67c5c95-9577-412f-8cb4-51feaf808073.png)

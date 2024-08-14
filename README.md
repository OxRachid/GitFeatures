## GitFeatures

## Git Features and Commands for Pushing Changes

✳️ **Configure Git:**

- *Set Your Username :*
```sh
git config --global user.name "Your Name"
```

- *Set Your Email:*
```sh
git config --global user.email "your_email@example.com"
```


✳️ **Add Changes:**

⦁ *Stage a specific file*
```sh
git add <file>
```

⦁ *Stage all changes in the current directory*
```sh
git add .
```

✳️ **Commit Changes:**
⦁ *Create a Commit with a Message:*
```sh
git commit -m "Your commit message"
```

✳️ **Push Changes:**
⦁ *Push to the Remote Repository:*
```sh
git push origin <branch>  # Push changes to the specified branch
```

✳️ **Pull Updates:**
⦁ *Fetch and Merge Changes from the Remote Repository:*
```sh
git pull origin <branch>  # Pull changes from the specified branch
```

✳️ **Check Status:**
⦁ *View Current Status of Your Repository:*
```sh
git status
```

✳️ **View Commit History:**
⦁ *Show Commit History:*
```sh
git log
```

✳️ **Configure Credential Caching:**

If you're being prompted for your username and password each time you push changes, it means Git is not using credential caching. You can set up Git to cache your credentials or use alternative methods for authentication. Here’s how you can address this:

⦁ *Cache Credentials Temporarily (default 15 minutes):*
```sh
git config --global credential.helper cache
```
⦁ *Cache Credentials for a Longer Duration (e.g., 1 hour):*
```sh
git config --global credential.helper 'cache --timeout=3600'
```

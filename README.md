## GitFeatures
1. Git Features and Commands for Pushing Changes

## Git Features and Commands for Pushing Changes

1. **Configure Git:**
   - Set Your Username :
```sh
git config --global user.name "Your Name"
```
   - Set Your Email:
```sh
git config --global user.email "your_email@example.com"
```

2. **Add Changes:**
   - Stage Files for Commit:
⦁ Stage a specific file
```sh
git add <file>
```
⦁ Stage all changes in the current directory
```sh
git add .
```

3. **Commit Changes:**
   - Create a Commit with a Message:
```sh
git commit -m "Your commit message"
```

4. **Push Changes:**
   - Push to the Remote Repository:
```sh
git push origin <branch>  # Push changes to the specified branch
```

5. **Pull Updates:**
   - Fetch and Merge Changes from the Remote Repository:
```sh
git pull origin <branch>  # Pull changes from the specified branch
```

6. **Check Status:**
   - View Current Status of Your Repository:
```sh
git status
```

7. **View Commit History:**
   - Show Commit History:
```sh
git log
```

8. **Configure Credential Caching:**
   - Cache Credentials Temporarily (default 15 minutes):
```sh
git config --global credential.helper cache
```
   - Cache Credentials for a Longer Duration (e.g., 1 hour):
```sh
git config --global credential.helper 'cache --timeout=3600'
```

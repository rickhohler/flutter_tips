# Tips

## Git Unsafe Repository

"This security issue started showing up in Git v2.35.2 and later, where Git now checks for ownership of the folder trying to ensure that the folder you are using Git in has the same user as the owner as your current user account."

[Fix that damn Git Unsafe Repository](https://weblog.west-wind.com/posts/2023/Jan/05/Fix-that-damn-Git-Unsafe-Repository)

```powershell
git config --global --add safe.directory <Git folder>
```

## 🛠️ Start Rename :-

<h3 align="center"> Rename Files Ubnutu </h3>

`Step 1` : Rename Ubnutu.

```
sudo apt install rename
```

```
rename 's/ \[DownSub\.com\]//g; s/\[Arabic\] //g; s/\(720P_HD\)//g' *
```

`Step 2` : Rename Windows.

```
Get-ChildItem "E:\00\10\*.*" | Rename-Item -NewName { $_.Name -replace '.zip', '' }
```

```
Get-ChildItem "E:\20-\42-django\a301-learn\3-\*.*" | Rename-Item -NewName { $_.Name -replace ' \[DownSub.com\]', '' }
```

```
Get-ChildItem "E:\20-\42-django\a301-learn\3-\*.*" | Rename-Item -NewName { $_.Name -replace '\[Arabic\] ', '' }
```

```
Get-ChildItem "E:\8=web\55=database\supbase\9=\*.*" | Rename-Item -NewName { $_.Name -replace ' \[DownSub.com', '' }
```

```
Get-ChildItem "E:\20-\42-django\a301-learn\3-\*.*" | Rename-Item -NewName { $_.Name -replace '\(720P_HD\)', '' }
```

```
Get-ChildItem "E:\20-\42-django\a301-learn\3-\*.*" | Rename-Item -NewName { $_.Name -replace '\(1080P_HD\)', '' }
```

```
Get-ChildItem "E:\8=web\13-2=\a3=Material UI Hour\*.*" | Rename-Item -NewName { $_.Name -replace '_', '#' }
```

```
Get-ChildItem "E:\8=web\55=database\supbase\*.*" | Rename-Item -NewName { $_.Name -replace ' _', ' #' }
```






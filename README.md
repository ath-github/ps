# ps
Change shell to powershell:
```cmd
powershell
```
Setting todo variable
```cmd
$todo = 'some-task'
```
Specifying url to fetch code from
```cmd
$url = 'https://raw.githubusercontent.com/ath-github/ps/master/' + $todo
```
To download code from specified url and execute it
```powershell
IEX (New-Object Net.WebClient).DownloadString($url)
```

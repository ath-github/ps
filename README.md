# ps
Change shell from cmd to powershell:
```cmd
powershell
```
Setting todo variable
```ps1
$todo = 'some-task'
```
Specifying url to fetch code from
```ps1
$url = 'https://raw.githubusercontent.com/ath-github/ps/master/' + $todo
```
To download code from specified url and execute it
```ps1
IEX (New-Object Net.WebClient).DownloadString($url)
```

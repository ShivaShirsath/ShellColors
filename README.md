# ShellColors
### Install in TermUX ( Android )
```bash
pkg install git -y && PWDx=$PWD && cd ~ && git clone https://github.com/ShivaShirsath/ShellColors.git && bash ~/ShellColors/install && cd $PWDx
```
### Generate Code 
```bash
getColorCode FONT LAYER RED GREEN BLUE 'TEXT'
```

<details><summary>Use code</summary>
```bash
echo -e "`getColorCode FONT LAYER RED GREEN BLUE 'TEXT'`"
```
<p align=center>Or</p>

```bash
printf  "`getColorCode FONT LAYER RED GREEN BLUE 'TEXT'`\n"
```
</details>
##### when you use this, each time new color code generate & copied on your clipboard. 

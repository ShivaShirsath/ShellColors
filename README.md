# ShellColors
<details>
  <summary>Installation</summary>
  
+  TermUX ( Android )
```bash
pkg install git -y && PWDx=$PWD && cd ~ && git clone https://github.com/ShivaShirsath/ShellColors.git && bash ~/ShellColors/install && cd $PWDx
```
+ Ubuntu
```bash
sudo apt install git -y && PWDx=$PWD && cd ~ && git clone https://github.com/ShivaShirsath/ShellColors.git && bash ~/ShellColors/install && cd $PWDx
```

</details>

<details>
  <summary>Generate Code</summary>
  
|| F | L | R | G | B |
| --- | --- | --- | --- | --- | --- |
| 0 | * | | * | * | * |
| 1 | * | | * | * | * |
| 2 | * | | * | * | * |
| 3 | * | * | * | * | * |
| 4 | * | * | * | * | * |
| 5 | * | | * | * | * |
| 6 | * | | | | |
| 7 | * | | | | |
| 8 | * | | | | |
| 9 | * | | | | |
  
```bash
getColorCode FONT LAYER RED GREEN BLUE 'TEXT'
```
</details>
<details>
  <summary>Use code</summary>
  
```bash
echo -e "`getColorCode FONT LAYER RED GREEN BLUE 'TEXT'`"
```
<p align=center>Or</p>

```bash
printf  "`getColorCode FONT LAYER RED GREEN BLUE 'TEXT'`\n"
```
</details>

##### when you use this, each time new color code generate & copied on your clipboard. 

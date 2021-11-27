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
  
|| FONT | LAYER | RED | GREEN | BLUE |
| --- | :--- | ---: | :---: | :---: | :---: |
| 0 | Normal | | [x] ‎ | * | * |
| 1 | **Bolt** | | * | * | * |
| 2 | Dim | | * | * | * |
| 3 | *Itallic* | Foreground | * | * | * |
| 4 | Underlined | Background | * | * | * |
| 5 | Blink | | * | * | * |
| 6 | Intense | | | | |
| 7 | Reverse | | | | |
| 8 | Invisible | | | | |
| 9 | ~Strike~ | | | | |
  
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

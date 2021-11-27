#  ShellColorsShellColors
hello
=
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
  
<table>
<thead>
<tr>
<th></th>
<th>FONT</th>
<th style="text-align:right">LAYER</th>
<th style="text-align:center">RED</th>
<th style="text-align:center">GREEN</th>
<th style="text-align:center">BLUE</th>
</tr>
</thead>
<tbody>
<tr>
<td>0</td>
<td>Normal</td>
<td style="text-align:right"></td>
<td style="text-align:center">*</td>
<td style="text-align:center">*</td>
<td style="text-align:center">*</td>
</tr>
<tr>
<td>1</td>
<td>Bolt</td>
<td style="text-align:right"></td>
<td style="text-align:center">*</td>
<td style="text-align:center">*</td>
<td style="text-align:center">*</td>
</tr>
<tr>
<td>2</td>
<td>Dim</td>
<td style="text-align:right"></td>
<td style="text-align:center">*</td>
<td style="text-align:center">*</td>
<td style="text-align:center">*</td>
</tr>
<tr>
<td>3</td>
<td>Itallic</td>
<td style="text-align:right">Foreground</td>
<td style="text-align:center">*</td>
<td style="text-align:center">*</td>
<td style="text-align:center">*</td>
</tr>
<tr>
<td>4</td>
<td>Underlined</td>
<td style="text-align:right">Background</td>
<td style="text-align:center">*</td>
<td style="text-align:center">*</td>
<td style="text-align:center">*</td>
</tr>
<tr>
<td>5</td>
<td>Blink</td>
<td style="text-align:right"></td>
<td style="text-align:center">*</td>
<td style="text-align:center">*</td>
<td style="text-align:center">*</td>
</tr>
<tr>
<td>6</td>
<td>Intense</td>
<td style="text-align:right"></td>
<td style="text-align:center"></td>
<td style="text-align:center"></td>
<td style="text-align:center"></td>
</tr>
<tr>
<td>7</td>
<td>Reverse</td>
<td style="text-align:right"></td>
<td style="text-align:center"></td>
<td style="text-align:center"></td>
<td style="text-align:center"></td>
</tr>
<tr>
<td>8</td>
<td>Invisible</td>
<td style="text-align:right"></td>
<td style="text-align:center"></td>
<td style="text-align:center"></td>
<td style="text-align:center"></td>
</tr>
<tr>
<td>9</td>
<td>Strike</td>
<td style="text-align:right"></td>
<td style="text-align:center"></td>
<td style="text-align:center"></td>
<td style="text-align:center"></td>
</tr>
</tbody>
</table>

  
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

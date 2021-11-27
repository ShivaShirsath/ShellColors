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
<th>LAYER</th>
<th>RED</th>
<th>GREEN</th>
<th>BLUE</th>
</tr>
</thead>
<tbody>
<tr>
<td>0</td>
<td>Normal</td>
<td></td>
<td>*</td>
<td>*</td>
<td>*</td>
</tr>
<tr>
<td>1</td>
<td>Bolt</td>
<td></td>
<td>*</td>
<td>*</td>
<td>*</td>
</tr>
<tr>
<td>2</td>
<td>Dim</td>
<td></td>
<td>*</td>
<td>*</td>
<td>*</td>
</tr>
<tr>
<td>3</td>
<td>Itallic</td>
<td style="text-align:center">Foreground</td>
<td>*</td>
<td>*</td>
<td>*</td>
</tr>
<tr>
<td>4</td>
<td>Underlined</td>
<td style="text-align:center">Background</td>
<td>*</td>
<td>*</td>
<td>*</td>
</tr>
<tr>
<td>5</td>
<td>Blink</td>
<td></td>
<td>*</td>
<td>*</td>
<td>*</td>
</tr>
<tr>
<td>6</td>
<td>Intense</td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr>
<td>7</td>
<td>Reverse</td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr>
<td>8</td>
<td>Invisible</td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr>
<td>9</td>
<td>Strike</td>
<td></td>
<td></td>
<td></td>
<td></td>
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

#  ShellColorsShellColors

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
<th>R</th>
<th>G</th>
<th>B</th>
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
<td><b>Bolt</b></td>
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
<td><i>Itallic</i></td>
<td><img src=https://user-images.githubusercontent.com/59221352/143685076-f1e20161-12cf-458e-ad60-ea281389e492.png></img></td>
<td>*</td>
<td>*</td>
<td>*</td>
</tr>
<tr>
<td>4</td>
<td><ins>Underlined</ins></td>
<td><img src=https://user-images.githubusercontent.com/59221352/143684886-9fee5249-cb54-4d7f-b5e2-4b94b4029902.png></img></td>
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
<td>Inverse</td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr>
<td>8</td>
<td><img src=https://user-images.githubusercontent.com/59221352/143685191-1a4721f8-30e9-4881-af9e-49a195c5d2d2.png alt=Invisible></img></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr>
<td>9</td>
<td><strike>Strike</strike></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
</tbody>
</table>

```bash
getColorCode FONT LAYER R G B 'TEXT'
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

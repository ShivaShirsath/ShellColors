# ShellColors

### Install in TermUX ( Android )

```bash
pkg install git -y 
PWDx=$PWD
cd ~
git clone https://github.com/ShivaShirsath/ShellColors.git
bash ~/ShellColors/install
cd $PWDx
```
### Generate Code 
```bash
getColorCode
```

### Use code
```bash
echo -e "`getColorCode FONT LAYER RED GREEN BLUE 'TEXT'`"
# Or
printf  "`getColorCode FONT LAYER RED GREEN BLUE 'TEXT'`\n"
```

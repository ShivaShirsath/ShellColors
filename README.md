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
```json
echo -e "`getColorCode font layer red green blue 'Text'`"
# Or
printf "`getColorCode font layer red green blue 'Text'`"
```

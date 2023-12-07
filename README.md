# Hakari
Small dice rolling script written in Python, made for the restless gamblers. A blatant copy of the dice rolling system in Avrae (the discord bot) but ported to a python script.

### Requirements
- Python 3.x+

### Install
```
git clone https://github.com/tsukki9696/hakari.git
cd hakari
chmod +x hakari
```
Optional (allows you to execute hakari from anywhere)
```
cp hakari ~/.local/bin
```

### Usage
Hakari has only three flags, you can consult them with `-h` but here's a resume of what they do;
- `-r` the amount of rolls to be performed
- `-d` the value of dice (e.g. a d20)
- `-l` optional label for dice rolls (e.g. `"Will I survive this critical hit?"`)

### Examples
```
./hakari -r10 -d2 -l 'rolling a d2 ten times'
```
This rolls a d2 ten times. The output;
```
rolling a d2 ten times: 10d2 [2, 2, 1, 1, 1, 1, 2, 1, 2, 1]
Total: 14
```
Flags can be omitted, none of them are mandatory, if you ran the script without any flags it will roll a d2 once with no label
```
./hakari
Result: 1d2 [2]
Total: 2
```

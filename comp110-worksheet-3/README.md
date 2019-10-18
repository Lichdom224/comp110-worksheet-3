# COMP110 Worksheet 3: Flowcharts and pseudocode

This is the base repository for COMP110 Worksheet 3.

Fork this repository, and edit `README.md` to show your pseudocode solving the worksheet task. Tip: use triple backticks to preserve spacing, e.g.:

```
press e to enter the terminal
First try = true
regen 1 life = false
exit = false

while first time = true
	search for letters
	click on the first letters
	guess = letters clicked
	if guess = password
		first time = false
		exit = true
	if guess != letter clicked
		remember how many letters were similar
		remember guess
		while regen 1 life = false
			check for debugs
			when found click on it
			if life = 4
				set first time to false
				set regen 1 life to true
			else
				redo while loop
while exit = false
	search for letters with letters you got correct
	if guess = password
		exit = true
	else
		remember how many letters were similar
		remember guess
```

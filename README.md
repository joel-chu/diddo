# diddo 

You know some time you just keep forgetting those command with lots of options. 
So I create this tiny tool to record them, then replay when I need to 

## Installation 

This is built with node.js

```sh
$ npm i -g diddo 
```

You get a command line name `diddo` 

## Use it 

The very simple way to record, and run it.

```sh
$ diddo ssh -o someverylongprop=somevalue -o someotherverylongprop=someothervalue user@host 
```

The above command will record everything after `diddo` and actually run the command 

To get it back 

```sh
$ diddo -l 
```
or 
```sh
$ diddo --list 
```

Will show the list of commands you recorded (order by the most recent one) 

Then pick a number 

```sh
$ diddo -r 1 
```

--- 

More TBC 

Joel Chu 2020 

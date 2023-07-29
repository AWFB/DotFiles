#Setup

or just use w3m and save youself a world of hassle

copy lynx.cfg and lynx.lss to home/.config/lynx

exect the lynx bash script (located in the scripts folder) dont forget chmod +x 

move lynx bash script to /.local/bin (create if it does not exist)

Easier searching:
copy duck script to .local/bin
copy urlencoder to .local/bin

chmod +x both scripts

I add "?" as an alias in my .bashrc for simplicity
```alias "?"='duck'```

Dont forget to ```exec bash -l``` to reload shell

If working on a machine with linux on it (rather than an ssh connection) you can use ```,``` to fire up the browser
What is wrong with this command?
tr A Z < $HOME/temp > $HOME/temp

You cant redirect to the same input. Instead it should be
tr A Z < $HOME/temp > $HOME/temp2

Then temp2 can be copied to temp


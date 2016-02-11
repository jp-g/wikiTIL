# Loop and a Half
This is a code that manipulate a collection, a process all items loop

Pseudo code:

read value
while (value != snetinel)
    process value
    read value

rewritten as:
while (true)
    read value
    if (value == sentinel) break;
    process value

while True;
    do_something()
    if condition();
        break

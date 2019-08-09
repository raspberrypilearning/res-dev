## Other markdown

### Scratch

Scratch blocks can be rendered using fenced code blocks. For testing purposes, you may find it helpful to use the [Scratchblocks](http://scratchblocks.github.io){:target="_blank"} website

```blocks3
when flag clicked
move (10) steps
turn cw (pick random (0) to (180)) degrees
```

was rendered using the following syntax

<html><pre>&#96;&#96;&#96;blocks3
when flag clicked
move (10) steps
turn cw (pick random (0) to (180)) degrees
&#96;&#96;&#96;</pre></html>

Additionally, inline scratch code can be coloured according to it's class.

`when flag clicked`{:class="block3events"} was rendered using the following syntax.

<html><pre>&#96;when flag clicked&#96;{:class="block3events"}</pre></html>

Options are:
```markdown
block3motion
block3looks
block3sound
block3extensions
block3variables
block3events
block3control
block3sensing
block3operators
block3myblocks
```

### Text based languages

You can use simple fenced blocks in markdown:

```python
for i in range(5):
    print(i)
```

was rendered using:

<html><pre>&#96;&#96;&#96;python
for i in range(5):
    print(i)
&#96;&#96;&#96;</pre></html>


Or you can use a more verbose form, for greater options:

--- code ---
---
language: python # required
filename: whoopee.py # optional
line_numbers: true # optional - default false
line_number_start: 3 # optional - default 0
highlight_lines: 3,5-6 # optional
---
while True:
    button.wait_for_press()
    parp = random.choice(trumps)
    os.system("aplay {0}".format(parp))
    sleep(2)
--- /code ---

Was rendered using the following syntax

<html><pre>&dash;&dash;&dash; code &dash;&dash;&dash;
&dash;&dash;&dash;
language: python # required
filename: whoopee.py # optional
line_numbers: true # optional &dash; default false
line_number_start: 3 # optional &dash; default 0
highlight_lines: 3,5&dash;6 # optional
&dash;&dash;&dash;
while True:
    button.wait_for_press()
    parp = random.choice(trumps)
    os.system("aplay {0}".format(parp))
    sleep(2)
&dash;&dash;&dash; /code &dash;&dash;&dash;</pre></html>

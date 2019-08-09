## Steps

By the end of each step the learner should have achieved something tangible, that succeively builds up to the completed project.

### Information / learning points

If the learner is expected to read a section for information / learning, the prose should be written using standard paragraph text in markdown.

### Tasks

If the learner is expected to perform some specific task, this should be written using the task syntax, which will colour the paragraph and add a checkbox

--- task ---
The task markdown is as follows:

<html>
<pre>
&dash;&dash;&dash; task &dash;&dash;&dash;
Task instructions go here goes here.
&dash;&dash;&dash; /task &dash;&dash;&dash;
</pre>
</html>
--- /task ---

### Hints

When asking the learner to complete a task with some level of independence, hints should be used so that a learner can always complete the project.

No more than one hint should be used per step.

--- hints --- --- hint ---
The first hint should just give additional guidance.
Here's the syntax for creating hints.
<html><pre>&dash;&dash;&dash; hints &dash;&dash;&dash; &dash;&dash;&dash; hint &dash;&dash;&dash;
A bit of guidance
&dash;&dash;&dash; /hint &dash;&dash;&dash; &dash;&dash;&dash; hint &dash;&dash;&dash;
Show them some code with bits left out or the blocks they will need
&dash;&dash;&dash; /hint &dash;&dash;&dash; &dash;&dash;&dash; hint &dash;&dash;&dash;
Show them the full solution
&dash;&dash;&dash; /hint &dash;&dash;&dash; &dash;&dash;&dash; /hints &dash;&dash;&dash;</pre></html>
--- /hint --- --- hint ---
The second hint should have more guidance, and optionally code that needs ordering or completing in some way
--- /hint --- --- hint ---
The third hint should contain the full solution to the problem.
--- /hint --- --- /hints ---

### Ingredients

See the sections on [Ingredients](../5) for information on creating ingredients.

No more than one ingredient should be included in each step. An ingredient will contain generic instructions on completing a task, such as creating a new file in a text editor.

The syntax for adding an ingredient is as follows:

<html><pre>&#91;&#91;&#91;name-of-ingredient-repo&#93;&#93;&#93;</pre></html>

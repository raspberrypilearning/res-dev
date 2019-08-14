## Introduction - step_1.md

- The Introduction should start as follow.

<html><pre>
## Introduction
A few lines describing what the user will create, beneath the level 2 header.

### What you will make
&dash;&dash;&dash; no&dash;print &dash;&dash;&dash;
![An animation/video/embedded representation of the finished project](images/finished&dash;project.gif)
&dash;&dash;&dash; /no&dash;print &dash;&dash;&dash;

&dash;&dash;&dash; print&dash;only &dash;&dash;&dash;
![A static image of the finished project](images/finished&dash;static.png)
&dash;&dash;&dash; /print&dash;only &dash;&dash;&dash;
</pre></html>

- The remaining content should be placed inside `--- collapse ---` blocks. These look like this

--- collapse ---
---
title: Title of the collapse - click me to expand
---
- Here's the markdown for collapsing blocks
<html>
<pre>
&dash;&dash;&dash; collapse &dash;&dash;&dash;
&dash;&dash;&dash;
title: Title of the collapse &dash; click me to expand
&dash;&dash;&dash;
Content of collapse goes here.
&dash;&dash;&dash; /collapse &dash;&dash;&dash;
</pre>
</html>
--- /collapse ---

- The required collapses are shown below with example content.

--- collapse ---
---
title: What you will need
---
### Hardware

+ A Quantum computer
+ An LED

### Software

+ [Emacs](https://www.gnu.org/software/emacs/emacs.html){:target="_blank"}
--- /collapse ---

--- collapse ---
---
title: What you will learn
---

+ How to use Quantum-mode in Emacs
+ How to calculate 6 x 7
--- /collapse ---

--- collapse ---
---
title: Additional information for educators
---

- If you need to print this project, please use the [printer-friendly version](https://projects.raspberrypi.org/en/projects/project-name/print){:target="_blank"}.

- You can [find the resources for this project here](http://rpf.io/project-name-go).

--- /collapse ---


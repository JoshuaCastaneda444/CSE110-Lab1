# Joshua Castaneda

This is my user page. *yay*...

I am currently a third year Computer Science student at UCSD.

## Lists About Me

### Programming Languages

- **JavaScript**
- **Rust**
- C++
- Python

### Top Spotify songs (April 2025)

1. Fever - Dua Lipa
2. Bye Bye Blues - Stela Cole
3. **Training Season - Dua Lipa**
4. Maria - Dua Lipa
5. These Walls - Dua Lipa

### CSE 168 Todo List

- [x]  Assignment 1 (Due: 4/14)
- [ ]  Assignment 2 (Due: 4/23)
- [ ]  Assignment 3 (Due: 5/5)
- [ ]  Assignment 4 (Due: 5/18)
- [ ]  Final Project Proposal (Due: 5/27)
- [ ]  Final Project (Due: 6/9)

## Quote I Like

> …the point of art, first and foremost, is to feel or to make the audience feel. [It's] the point of most media even, that we are feeling creatures first and thinking creatures second, and if you can take care of the first bit the audience will come with you for the second

― exurb2a, [talking cat film is extremely good](https://youtu.be/9O65k561f9U?t=321)

## Example Code

Some code I wrote in community college for an assembly class.

```arm
@ Define processors
.cpu cortex-a72
.fpu neon-fp-armv8

@ Code section
.text
.align 2
.global mod
.type mod, %function

@ r0: dividend
@ r1: divisor
@ returns: r0 % r1
mod:
	push {fp, lr}
	add fp, sp, #4

	udiv r2, r0, r1     @ r2 = floor(r0/r1)

	mls r0, r2, r1, r0  @ r0 = r0 - (r2 * r1)

	sub sp, fp, #4
	pop {fp, pc}
```

## Submission Images

![Screenshot demonstrating git usage via command line](/screenshots/command_line.png)
![Screenshot demonstrating git usage via the vscode ui](/screenshots/vscode_ui.png)

[Back To Top](#joshua-castaneda)

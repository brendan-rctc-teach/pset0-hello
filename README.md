# Hello
## To start this problem:

Click the green Code button and choose Open with Codespaces.
1. If this is your first time opening this assignment, click New codespace and then, if prompted, Create codespace.
2. If you have opened this assignment before, click main.
3. To submit this problem: 
   1. On the left hand side of VSCode, choose the "source control" button.
   2. Now, you want to write a "commit" message describing what you've done and click "commit."
   3. Finally, after the commit has finished, you must click to "sync" your changes with your repository. THIS MAKES THEM AVAILABLE FOR GRADING.
   4. You see a short video on the process here: https://youtu.be/9udBgTIbDLw

## Directions
Let's write our first program! Here's what you should do:

1. Execute `code hello.c`
to create a new file called hello.c, which should open automatically in your codespace’s text editor. As soon as you save the file with command-S (on macOS) or control-S (on Windows), it should also appear in your codespace’s explorer.

2. Proceed to write your first program by typing precisely these lines into hello.c:

```
#include <stdio.h>

int main(void)
{
    printf("hello, world\n");
}
```
Notice how VS Code adds “syntax highlighting” (i.e., color) as you type, though VS Code’s choice of colors might differ from this problem set’s. Those colors aren’t actually saved inside of the file itself; they’re just added by VS Code to make certain syntax stand out. Had you not saved the file as hello.c from the start, VS Code wouldn’t know (per the filename’s extension) that you’re writing C code, in which case those colors would be absent.

3. Now, before we can execute the hello.c program, recall that we must compile it with a compiler, translating it from source code into machine code (i.e., zeroes and ones). Execute the command below to do just that:

`make hello`


And then execute this one again:

`ls`

This time, you should see not only hello.c but hello listed as well? You’ve now translated the source code in hello.c into machine code in hello.

Now execute the program itself by executing the below.

`./hello`

Hello, world, indeed!

4. Getting User Input
Suffice it to say, no matter how you compile or execute this program, it only ever prints hello, world. Let’s personalize it a bit, just as we did in class.

Modify this program in such a way that it first prompts the user for their name and then prints hello, so-and-so, where so-and-so is their actual name.

As before, be sure to compile your program with:

make hello
And be sure to execute your program, testing it a few times with different inputs, with:

./hello

5. Once you are done, you can submit your work by "staging", "committing", and "pushing" (or "sycning") your changes. Your grade should show up within 5 minutes on the "action" tab of your repository.
6. You can find a short "walkthrough" from CS50 staff here: https://youtu.be/wSk1KSDUEYA
7. Walkthrough. You can find a short problm walktrgiy

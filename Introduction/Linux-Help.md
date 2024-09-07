# Getting Help

We will always stumble across tools whose optional parameters we do not know from memory or tools we have never seen before. Therefore, it is vital to know how we can help ourselves to get familiar with those tools. The first two ways are the man pages and the help functions. It is always a good idea to familiarize ourselves with the tool we want to try first. We will also learn some possible tricks with some of the tools that we thought were not possible. In the man pages, we will find the detailed manuals with detailed explanations.

**Syntax:**

```bash
Getting Help

root@fedora$ man <tool>

After looking at some examples, we can also quickly look at the optional parameters without browsing through the complete documentation. We have several ways to do that.

root@fedora$ <tool> --help

As we can see, the results from each other do not differ in this example. Another tool that can be useful in the beginning is apropos. Each manual page has a short description available within it. This tool searches the descriptions for instances of a given keyword.

root@fedora$ apropos <keyword>
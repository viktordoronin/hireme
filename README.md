Hey there, if you found your way here, you're most likely considering hiring me(please do!). This here is a collection of links to code I wrote, either in my university work or my personal projects. 

Regarding my uni projects, please note that this isn't nearly everything I've written(I picked out the interesting ones), I've gotten a lot better over the years, and more often than not deadlines forced me to hack together a quick solution without an opportunity to improve on it later. We were often graded on functionality first, lab report second, and code quality only third.

## Go
[learning-epbf-go](https://github.com/viktordoronin/learning-ebpf-go) - O'Reily "Learning eBPF" code rewritten for Go. I learned a lot and had lots of fun with that one, self-taught completely from scratch.
## Python
[This is a Python project I did for my Software Development class.](https://github.com/viktordoronin/python-sd) The class was focused on TDD(test-driven development) so naturally the project involved developing tests, it also dealt with things like developing and applying a code standard, using a linter and a build system, refactoring. We were graded on following the TDD process correctly so the commit history is a big part of this one.
## C
### OS
For my Operating Systems class we had to develop some programs using POSIX syscalls. The code gets hard to read for a bit, but we were obligated to treat each and every error and I was just so fed up with it all I resorted to one-liners. I obviously wouldn't write actual production code like this. 
- [The first project](https://github.com/viktordoronin/os_shell) consisted of developing a Bash shell complete with piping and I/O redirection.
- [The second project](https://github.com/viktordoronin/os_threads) is a typical producer/consumer problem solved with POSIX threads. I wanted to do it round robin like it's typically done, but the prof made me preemptively divide the task into chunks(so called monitor solution).
### Distributed systems
This class consisted of implemented a client-server architecture to do simple CRUDs with various communication methods. Note that the first 3 projects only required developing a library with required functions, which would then be linked against the prof's testing suite, so there's no main function or buildable executable.
- [Linux message queues](https://github.com/viktordoronin/mq)
- [Sockets](https://github.com/viktordoronin/SSDD_EE2)
- [Sockets+rpcgen](https://github.com/viktordoronin/rpcgen)
- [Back to sockets, but with a more elaborate Python client.](https://github.com/viktordoronin/SSDD_PRACTICA) I'm especially proud of this one as I got to do some wild stuff in there which would likely get me fired if it was an actual workplace.
### Compilers
For the only class I haven't finished yet, I'm currently developing a C->Lisp->Forth translator using yylex. Can't show it here yet as it isn't finished and I don't want it plagiarized, should be coming at around 8th of May.

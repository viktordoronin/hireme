Hey there, if you found your way here, you're most likely considering hiring me(please do!). This here is a collection of links to code I wrote, either in my university work or my personal projects. No AI was used, ever.

Regarding my uni projects, please note that this isn't nearly everything I've written(I picked out the interesting ones), I've gotten a lot better over the years, and more often than not workload and deadlines forced me to hack together a quick solution without an opportunity to improve on it later. We were often graded on functionality first, lab report second, and code quality only third.

## DevOps
[Gitlab CI/CD](https://gitlab.com/viktordoronin/devops) - this is an assignment for my university DevOps subject. The project code was provided to us, we were required to set up the pipeline to run some specific tools to produce some specific output(messages and stuff). The parts that are mine is the pipeline config and the bash scripts. I had to do some Bash magic in order to get the exact output the professor wanted, otherwise it's a simple project but it's not like Gitlab CI/CD is terribly complicated anyway.

[CKA practice](https://github.com/viktordoronin/cka-practice) - I wanted to get some hands-on Kubernetes experience so I found some practice exercises. They're brief, but cover just about everything you need to know to use Kubernetes. I don't actually intend to take CKA but it was nice to test my knowledge of K8s regardless. It took me around 5 hours in total to complete this.

## Go
[learning-epbf-go](https://github.com/viktordoronin/learning-ebpf-go) - O'Reily "Learning eBPF" code rewritten for Go. I learned a lot and had lots of fun with that one, self-taught completely from scratch.

[Fun with gRPC](https://github.com/viktordoronin/fun-with-grpc) - I took a short online course to teach myself gRPC and then I went a bit beyond what the course has covered. Soon I'll come back to it and do more.
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
- [This is a portion of the project I had to do for this subject.](https://github.com/viktordoronin/ctolisp). The whole project was to create a C to Lisp to Gforth translator using `bison`. I omitted the "Lisp to Gforth" bit since it's just more of the same, the C translator portion is way more interesting. It's a bit rough around the edges, but mostly does its job, including features such as sintactic and semantic analysis, type analysis and a symbol table to keep track of variables. However, since it's intended to be a translator and not parser/compiler/whatever, it assumes the input is valid C and therefore doesn't check many things a proper compiler would(all in accordance with project instructions). I intend to come back to this as I wasn't at all happy with the grade, and also just for the fun of working with it. 

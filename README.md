![philoexec](https://github.com/42rteles-f/philosophers/assets/89268663/efe32455-b46d-4551-a6f8-680f8e894f89)

The dining philosophers problem is a famous problem often used to illustrate synchronization issues and techniques for resolving them.<br>

The first and most important part of the project is understand how and when to use mutexes, once you understand the nature of data-races and the problems they can generate, using a mutex feel intuitive.

Once you protect your resources and guarantee that the threads aren't creating them, the challenge is to understand how the threads can cause dead-locks and live-locks when sharing resources, with a simple change in the order in which the philosophers pick their forks you already solve big part of the problem. Or in my case using a turn system based on how many philosophers have already eaten.

![philofunc](https://github.com/42rteles-f/philosophers/assets/89268663/ce78ab3f-aad6-4d9b-8dcb-91e14dc33d0c)


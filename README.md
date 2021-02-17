The Deadlock Empire
===

A game that teaches locking and concurrency. It runs on
[https://deadlockempire.github.io](https://deadlockempire.github.io).

Adaptation
===

This fork was adapted for KULeuven's 2nd bachelor Operating Systems and C course, which doesn't teach C# but plain C and pthreads.

The following exercises are NOT fit for these students and should be skipped:
- Everything in "High-Level Synchronization Primitives"
- Condition variables (.PulseAll)
- Boss fight (.Pulse)

Explain beforehand:
- What are threads?
- What is a critical section?
- What are atomic operations?

Progression in class:
- Show: Tutorial 1
- Show: Boolean Flags Are Enough For Everyone
- Show: Simple Counter
- Show: Tutorial 2
- Exercise: Confused Counter
- Explain: concepts behind locks
- Show: Insufficient lock
- Show: Deadlock
- Exercise: A more complex thread
- Explain: semaphores
- Show: Semaphores
- Show: Producer-Consumer
- Show: Producer-Consumer (Variant)
- Take-home task: Dragonfire
- Take-home task: Triple Danger

Contributing
===

We gladly welcome all contributions. Especially, we <3 pull requests, bug
reports and ideas for features or new challenges. We would also be happy to
hear about your experience with The Deadlock Empire: which parts you enjoyed,
which were too difficult, what confused you, or anything else - shoot us
an e-mail at `prvak.cnx+deadlockempire@gmail.com`.

For complete information on how to contribute to The Deadlock Empire, please
see the [CONTRIBUTORS](./CONTRIBUTORS.md) file.

Acknowledgements
===

We stand on the shoulders of giants.

We thank the numerous organizers, sponsors, judges and hackers of
[HackCambridge 2016](https://www.hackcambridge.com/) for the opportunity to
develop this idea and for their support.

We use [jQuery](https://jquery.com/) for manipulating the DOM and for
animations. The design is implemented using vanilla
[Bootstrap](https://getbootstrap.com/). The tutorial challenge uses
[Intro.js](https://usablica.github.io/intro.js/) to familiarize the player
with the controls. Keyboard shortcuts are implemented using [Mousetrap](https://craig.is/killing/mice).

The game uses the [Amatic SC](http://www.fontsquirrel.com/fonts/amatic) font
published by [Vernon Adams](http://www.fontsquirrel.com/fonts/list/foundry/vernon-adams)
published on [Google Fonts](https://www.google.com/fonts).

The logo is a combination of the dragon from
[the Welsh flag](https://commons.wikimedia.org/wiki/File:Flag_of_Wales_2.svg)
and a lock icon, both from Wikimedia Commons.

Credits
===
Made by [Petr Hudeček](http://hudecekpetr.cz) and [Michal
Pokorný](http://rny.cz) on [HackCambridge 2016](https://www.hackcambridge.com/).

License
===

This software uses the [Bootstrap framework](http://getbootstrap.com). Bootstrap is copyright Twitter, Inc. and available under the [MIT License](https://github.com/twbs/bootstrap/blob/master/LICENSE).

The Bootstrap framework ships with a no-cost version of the [GLYPHICONS](http://glyphicons.com/license/) icon/font set. The copyright of GLYPHICONS is retained by its creators.

All other software in this repository is licensed under the GNU General Public License Version 2. Please see the license file (`COPYING`) for complete information.

All contributors retain copyright to their contributions to this project.

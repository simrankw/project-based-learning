# Project Based Learning

A list of programming tutorials in which learners build an application from scratch. These tutorials are divided into different primary programming languages. Some have intermix technologies and languages.

To get started, simply fork this repo. Please refer to [CONTRIBUTING.md](CONTRIBUTING.md) for contribution guidelines.

## Table of Contents:

* [C#](#c)
* [C/C++](#cc)
* [Clojure](#clojure)
* [Elixir](#elixir)
* [Go](#go)
* [Haskell](#haskell)
* [HTML/CSS](#html-and-css)
* [Java](#java)
* [JavaScript](#javascript)
* [Kotlin](#kotlin)
* [Lua](#lua)
* [OCaml](#ocaml)
* [PHP](#php)
* [Python](#python)
* [R](#r)
* [Ruby](#ruby)
* [Rust](#rust)
* [Swift](#swift)
* [Additional resources](#additional-resources)

## C/C++:

* [Build an Interpreter](http://www.craftinginterpreters.com/) (Chapter 14 on is written in C)
* [Write a Shell in C](https://brennan.io/2015/01/16/write-a-shell-in-c/)
* [Write a FUSE Filesystem](https://www.cs.nmsu.edu/~pfeiffer/fuse-tutorial/)
* [Build Your Own Text Editor](http://viewsourcecode.org/snaptoken/kilo/)
* [Build Your Own Lisp](http://www.buildyourownlisp.com/)
* [How to Program an NES Game in C](https://nesdoug.com/)
* [Write an OS from scratch](https://github.com/tuhdo/os01)
* [How to Write an Emulator (CHIP-8 interpreter)](http://www.multigesture.net/articles/how-to-write-an-emulator-chip-8-interpreter/)
* [Beginning Game Programming with C++ and SDL](http://lazyfoo.net/tutorials/SDL/)
* [Implementing a Key-Value Store](http://codecapsule.com/2012/11/07/ikvs-implementing-a-key-value-store-table-of-contents/)
* Writing a minimal x86-64 JIT compiler in C++
  * [Part 1](https://solarianprogrammer.com/2018/01/10/writing-minimal-x86-64-jit-compiler-cpp/)
  * [Part 2](https://solarianprogrammer.com/2018/01/12/writing-minimal-x86-64-jit-compiler-cpp-part-2/)
  * [Part 3](https://solarianprogrammer.com/2018/01/12/writing-minimal-x86-64-jit-compiler-cpp-part-3/)
* [Build a Live Code-reloader Library for C++](http://howistart.org/posts/cpp/1/index.html)
* [Write a hash table in C](https://github.com/jamesroutley/write-a-hash-table)
* [Let's Build a Simple Database](https://cstack.github.io/db_tutorial/)
* [Let's Write a Kernel](http://arjunsreedharan.org/post/82710718100/kernel-101-lets-write-a-kernel)
* [Write a Bootloader in C](http://3zanders.co.uk/2017/10/13/writing-a-bootloader/)
* [Linux Container in 500 Lines of Code](https://blog.lizzie.io/linux-containers-in-500-loc.html)
* Write a C compiler
  * [Part 1: Integers, Lexing and Code Generation](https://norasandler.com/2017/11/29/Write-a-Compiler.html)
  * [Part 2: Unary Operators](https://norasandler.com/2017/12/05/Write-a-Compiler-2.html)
  * [Part 3: Binary Operators](https://norasandler.com/2017/12/15/Write-a-Compiler-3.html)
  * [Part 4: Even More Binary Operators](https://norasandler.com/2017/12/28/Write-a-Compiler-4.html)
  * [Part 5: Local Variables](https://norasandler.com/2018/01/08/Write-a-Compiler-5.html)
  * [Part 6: Conditionals](https://norasandler.com/2018/02/25/Write-a-Compiler-6.html)
  * [Part 7: Compound Statements](https://norasandler.com/2018/03/14/Write-a-Compiler-7.html)
  * [Part 8: Loops](https://norasandler.com/2018/04/10/Write-a-Compiler-8.html)
* [Implementing a Language with LLVM](https://llvm.org/docs/tutorial/#kaleidoscope-implementing-a-language-with-llvm)
* [High-Performance Matrix Multiplication](https://gist.github.com/nadavrot/5b35d44e8ba3dd718e595e40184d03f0)
* Space Invaders from Scratch
  * [Part 1](http://nicktasios.nl/posts/space-invaders-from-scratch-part-1.html)
  * [Part 2](http://nicktasios.nl/posts/space-invaders-from-scratch-part-2.html)
  * [Part 3](http://nicktasios.nl/posts/space-invaders-from-scratch-part-3.html)
  * [Part 4](http://nicktasios.nl/posts/space-invaders-from-scratch-part-4.html)
* [Tetris Tutorial in C++ Platform Independent](http://javilop.com/gamedev/tetris-tutorial-in-c-platform-independent-focused-in-game-logic-for-beginners/)
* Writing a Linux Debugger
  * [Part 1: Setup](https://blog.tartanllama.xyz/writing-a-linux-debugger-setup/)
  * [Part 2: Breakpoints](https://blog.tartanllama.xyz/writing-a-linux-debugger-breakpoints/)
  * [Part 3: Registers and memory](https://blog.tartanllama.xyz/writing-a-linux-debugger-registers/)
  * [Part 4: Elves and dwarves](https://blog.tartanllama.xyz/writing-a-linux-debugger-elf-dwarf/)
  * [Part 5: Source and signals](https://blog.tartanllama.xyz/writing-a-linux-debugger-source-signal/)
  * [Part 6: Source-level stepping](https://blog.tartanllama.xyz/writing-a-linux-debugger-dwarf-step/)
  * [Part 7: Source-level breakpoints](https://blog.tartanllama.xyz/writing-a-linux-debugger-source-break/)
  * [Part 8: Stack unwinding](https://blog.tartanllama.xyz/writing-a-linux-debugger-unwinding/)
  * [Part 9: Handling variables](https://blog.tartanllama.xyz/writing-a-linux-debugger-variables/)
  * [Part 10: Advanced topics](https://blog.tartanllama.xyz/writing-a-linux-debugger-advanced-topics/)

### Network programming

* Let's Code a TCP/IP Stack
  * [Part 1: Ethernet & ARP](http://www.saminiir.com/lets-code-tcp-ip-stack-1-ethernet-arp/)
  * [Part 2: IPv4 & ICMPv4](http://www.saminiir.com/lets-code-tcp-ip-stack-2-ipv4-icmpv4/)
  * [Part 3: TCP Basics & Handshake](http://www.saminiir.com/lets-code-tcp-ip-stack-3-tcp-handshake/)
  * [Part 4: TCP Data Flow & Socket API](http://www.saminiir.com/lets-code-tcp-ip-stack-4-tcp-data-flow-socket-api/)
  * [Part 5: TCP Retransmission](http://www.saminiir.com/lets-code-tcp-ip-stack-5-tcp-retransmission/)
  
* Programming concurrent servers
  * [Part 1 - Introduction](https://eli.thegreenplace.net/2017/concurrent-servers-part-1-introduction/)
  * [Part 2 - Threads](https://eli.thegreenplace.net/2017/concurrent-servers-part-2-threads/)
  * [Part 3 - Event-driven](https://eli.thegreenplace.net/2017/concurrent-servers-part-3-event-driven/)
  * [Part 4 - libuv](https://eli.thegreenplace.net/2017/concurrent-servers-part-4-libuv/)
  * [Part 5 - Redis case study](https://eli.thegreenplace.net/2017/concurrent-servers-part-5-redis-case-study/)
  * [Part 6 - Callbacks, Promises and async/await](https://eli.thegreenplace.net/2018/concurrent-servers-part-6-callbacks-promises-and-asyncawait/)

### OpenGL:

* Creating 2D Breakout game clone in C++ with OpenGL
  * [Breakout](https://learnopengl.com/In-Practice/2D-Game/Breakout)
  * [Setting up](https://learnopengl.com/In-Practice/2D-Game/Setting-up)
  * [Rendering Sprites](https://learnopengl.com/In-Practice/2D-Game/Rendering-Sprites)
  * [Levels](https://learnopengl.com/In-Practice/2D-Game/Levels)
  * Collisions
    * [Ball](https://learnopengl.com/In-Practice/2D-Game/Collisions/Ball)
    * [Collision detection](https://learnopengl.com/In-Practice/2D-Game/Collisions/Collision-detection)
    * [Collision resolution](https://learnopengl.com/In-Practice/2D-Game/Collisions/Collision-resolution)
  * [Particles](https://learnopengl.com/In-Practice/2D-Game/Particles)
  * [Postprocessing](https://learnopengl.com/In-Practice/2D-Game/Postprocessing)

  * [Powerups](https://learnopengl.com/In-Practice/2D-Game/Powerups)
  * [Audio](https://learnopengl.com/In-Practice/2D-Game/Audio)
  * [Render text](https://learnopengl.com/In-Practice/2D-Game/Render-text)
  * [Final thoughts](https://learnopengl.com/In-Practice/2D-Game/Final-thoughts)
* [Handmade Hero](https://handmadehero.org)
* [How to Make Minecraft in C++/OpenGL](https://www.youtube.com/playlist?list=PLMZ_9w2XRxiZq1vfw1lrpCMRDufe2MKV_)

)

## Clojure:

* [Build a Twitter Bot with Clojure](http://howistart.org/posts/clojure/1/index.html)
* [Bulding a Spell-Checker](https://bernhardwenzel.com/articles/clojure-spellchecker/)
* [Building a JIRA integration with Clojure & Atlassian Connect](https://hackernoon.com/building-a-jira-integration-with-clojure-atlassian-connect-506ebd112807)

## Elixir

* [Building a Simple Chat App With Elixir and Phoenix](https://sheharyar.me/blog/simple-chat-phoenix-elixir/)

## Java:

* [Build an Interpreter](http://www.craftinginterpreters.com/) (Chapter 4-13 is written in Java)
* [Build a Simple HTTP Server with Java](http://javarevisited.blogspot.com/2015/06/how-to-create-http-server-in-java-serversocket-example.html)
* [Build an Android Flashlight App](https://www.youtube.com/watch?v=dhWL4DC7Krs)
* [Build a Spring Boot App with User Authentication](https://scotch.io/tutorials/build-a-spring-boot-app-with-user-authentication)

## JavaScript:

* [Build 30 things in 30 days with 30 tutorials](https://javascript30.com)
* [Build an App in Pure JS](https://medium.com/codingthesmartway-com-blog/pure-javascript-building-a-real-world-application-from-scratch-5213591cfcd6)~

#### React:

* [Create Serverless React.js Apps](http://serverless-stack.com/)
* [Create a Trello Clone](http://codeloveandboards.com/blog/2016/01/04/trello-tribute-with-phoenix-and-react-pt-1/)
* [Create a Character Voting App with React, Node, MongoDB and SocketIO](http://sahatyalkabov.com/create-a-character-voting-app-using-react-nodejs-mongodb-and-socketio/)
* [React Tutorial: Cloning Yelp](https://www.fullstackreact.com/articles/react-tutorial-cloning-yelp/)
* [Build a Full Stack Movie Voting App with Test-First Development using Mocha, React, Redux and Immutable](https://teropa.info/blog/2015/09/10/full-stack-redux-tutorial.html)
* [Build a Twitter Stream with React and Node](https://scotch.io/tutorials/build-a-real-time-twitter-stream-with-node-and-react-js)
* Build a Serverless MERN Story App with Webtask.io
  * [Part 1](https://scotch.io/tutorials/build-a-serverless-mern-story-app-with-webtask-io-zero-to-deploy-1)
  * [Part 2](https://scotch.io/tutorials/build-a-serverless-mern-story-app-with-webtask-io-zero-to-deploy-2)
* [Build A Simple Medium Clone using React.js and Node.js](https://codeburst.io/build-simple-medium-com-on-node-js-and-react-js-a278c5192f47)
* [Integrate MailChimp in JS](https://medium.freecodecamp.org/how-to-integrate-mailchimp-in-a-javascript-web-app-2a889fb43f6f)
* [Build A Chrome Extension with React + Parcel](https://medium.freecodecamp.org/building-chrome-extensions-in-react-parcel-79d0240dd58f)
* [Build A ToDo App With React Native](https://blog.hasura.io/tutorial-fullstack-react-native-with-graphql-and-authentication-18183d13373a)
* [Make a Chat Application](https://medium.freecodecamp.org/how-to-build-a-chat-application-using-react-redux-redux-saga-and-web-sockets-47423e4bc21a)
* [Create a News App with React Native](https://medium.freecodecamp.org/create-a-news-app-using-react-native-ced249263627)
* [Learn Webpack For React](https://medium.freecodecamp.org/learn-webpack-for-react-a36d4cac5060)
* [Testing React App With Pupepeteer and Jest](https://blog.bitsrc.io/testing-your-react-app-with-puppeteer-and-jest-c72b3dfcde59)
* [Build Your Own React Boilerplate](https://medium.freecodecamp.org/how-to-build-your-own-react-boilerplate-2f8cbbeb9b3f)
* [Code The Game Of Life With React](https://medium.freecodecamp.org/create-gameoflife-with-react-in-one-hour-8e686a410174)
* [A Basic React+Redux Introductory Tutorial](https://hackernoon.com/a-basic-react-redux-introductory-tutorial-adcc681eeb5e)

#### Angular:

* [Build an Instagram Clone](https://hackhands.com/building-instagram-clone-angularjs-satellizer-nodejs-mongodb/)
* Build an offline-capable Hacker News client with Angular 2+

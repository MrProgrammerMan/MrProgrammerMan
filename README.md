# Hi there 👋
Welcome to my GitHub page. This is where you can see what I'm currently working on. Have a look around!

You can read about my focus or technologies I use(bottom of the page).

(I apologize for the mess)

## Who am I?
My name is Jonas and I am a software engineering student at Oslo Metropolitan University. I've always loved technology and programming, which is why I chose to study software engineering.
I love understanding how things work, and can never stop myself from investigating something I don't understand. **If you are a potential employer reviewing job candidates you may skip to the next paragraph.** That means I am probably sometimes a pain to deal with if I can't figure something out or if I'm forced to accept some technique or method without knowing _why_.

In addition to attending OsloMet, I am also the corporate contact and event manager at [Ditio, the student association for IT students.](https://www.linkedin.com/company/ditio-linjeforening)

## Focus - philosophical
I aspire to work as a software engineer. That means more than just writing programs for clients. It means taking into account ethical, societal and practical considerations to deliver software that's not only functonal, but also maintainable and well documented. Good software can evolve with the needs of the client and can be passed to other developers with little friction.

I have a great interest in finding "proper" solutions to problems. More and more I find myself prefering expert books and official documentation over less formal sources like blogs or guides. That is not to take away from the wonderful part of the software space that is sharing and helping each other - it's just often important to check and harden knowledge with official sources to avoid pitfalls like security holes and solutions that only work _sometimes_.

I also like efficiency. Even though we increasingly write software(such as web apps) that don't take performance into consideration, I find that stupid. There are often tools available that enable solving the same problem while doing so efficiently. Just because modern hardware is fast, there is still energy-consumption and scalability to consider. Of course there are situations where it's okay to write a webserver in Python(especially with cachieg, since optimizations only matter in bottlenecks), but I find more interest in compiled languages with static typing. It's more satisfying to work with, and it leaves less room for sloppy implementations. This will likely explain many of the technologies, languages and techniques I prefer using in my work.

## Focus - concrete
Currently, I am learning Rust. I like its unique position as a fast, compiled language with safeguards you would often only find in slower, interpreted languages. I am also trying to learn more about functional languages. This is not just about efficiency in terms of raw excecution speed, but about efficiency in terms of development time. Functional programming is a type of programming that can provide guarantees like safe concurrency, testability and more. Therefore, I consider it important to learn about(even if I may not end up working with it on a daily basis). I use Haskell.

In addition I should mention nix, which is a purely functional language drawing heavily on haskell for its inspiration. It is, however, not primarily intended as a general purpose language. It is turing complete, but its purpose is declaring and defining packages, system configurations, development environments, and much more. In general it provides a lot of great tooling involved in software development. I use it for all my projects, as well as for configuring all my machines, which run [NixOS](https://nixos.org/)(linux distro based on the Nix package manager that is used with the nix programming language).

Recently I've been focusing on learning more about the practical use cases of nix. My [portfolio page](https://jonas.baugerud.no) is built with a rust framework called leptos. The output binary and dependencies such as static files is built with nix. This guarantees it will build correctly every single time(sort of like docker, but more deterministic and robust). The portfolio(which is thus a nix package) is then wrapped in a NixOS module that specifies exactly how to run it, and allows specifying options to modify how it functions. This module is used in a NixOS VM that allows testing of the final server environment prior to deployment. This can also be used for automated NixOS integration tests with servers and clients running virtually. Finally, I use [my own deployment tool](https://github.com/MPM-Labs/nixos-deployment-template) to deploy a NixOS system running this same setup, including server bootstrapping, updates, and automatic secrets management integrated into GitHub Actions and repository/environment secrets. Nix will even seemlessly bridge the gap between source and binary deployment by providing crching of built packages. This reduces build times on the server, which may be resource constrained. As a bonus nix allows simple and deterministic development environments that are language- and tooling-agnostic and can be shared between developers as part of a git repo. Simple put, nix is f***ing awesome.

## Other focuses
Being a software engineering student, I learn about project management, development processeses, algorithms, data strucutres, databases, programming, operating systems, cloud services, networking and more.

## Work
I'm actively looking for a job opportunity within software engineering. I'd be happy to consider an offer, especially(but not exclusively) if it coincides with my interests in the field. You can reach me through my [LinkedIn profile](https://www.linkedin.com/in/jonas-baugerud/). I also have some contact info on [my website](https://jonas.baugerud.no).

## Technologies I use or have used

### Languages I know well
- ![rust](https://skillicons.dev/icons?i=rust) **Rust** — My personal goto. Can be used for almost anything, from low level systems to web servers. I even use it to compile WASM for my portfolio website.
- ![nix](https://skillicons.dev/icons?i=nix) **Nix** — This is more tooling-oriented. I use it in all my projects. It packages software and guarantees correct deployment.
- ![bash](https://skillicons.dev/icons?i=bash) **Bash** — Always useful.
- ![postgres](https://skillicons.dev/icons?i=postgres) **PostgreSQL** — You can do remarkably powerful things with SQL and PL/pqSQL.
- ![py](https://skillicons.dev/icons?i=py) **Python** — For certain quick prototyping and university courses.
- ![java](https://skillicons.dev/icons?i=java) **Java** — The main language taught at university.
- ![html](https://skillicons.dev/icons?i=html) **HTML** — Always important to keep in mind the basics.
- ![css](https://skillicons.dev/icons?i=css) **CSS** — I prefer writing my own css(SCSS) instead of using tools like Tailwind. That being said, design is not my main focus.
- ![js](https://skillicons.dev/icons?i=js) **JavaScript** — This is unavoidable in web... is what I would say if rust didn't have such great support for WASM.

### Languages I'm learning
- ![rust](https://skillicons.dev/icons?i=rust) **Rust** — Currently working on async understanding.
- ![nix](https://skillicons.dev/icons?i=nix) **Nix** — Currently working chapter 5 of [the thesis]((https://edolstra.github.io/pubs/phd-thesis.pdf)
- ![bash](https://skillicons.dev/icons?i=bash) **Bash** — I often bump into commands I haven't used before and try to get familiar with as many as possible.
- ![haskell](https://skillicons.dev/icons?i=haskell) **Haskell** — Currently reading [Programming in Haskell](https://people.cs.nott.ac.uk/pszgmh/pih.html).
- ![wasm](https://skillicons.dev/icons?i=wasm) **WebAssembly** — I am developing my portfolio site that runs on [Leptos](https://www.leptos.dev/), but would like to learn more about WASM itself.

### Tooling I use
- ![docker](https://skillicons.dev/icons?i=docker) **Docker** — Mostly when collaborating with others. In my personal projects, Nix has replaced Docker.
- ![figma](https://skillicons.dev/icons?i=figma) **Figma** — Prototyping UIs.
- ![git](https://skillicons.dev/icons?i=git) **Git** — Have to mention it.
- ![githubactions](https://skillicons.dev/icons?i=githubactions) **GitHub Actions** — Love this! Allows a ton of automation and free jobs on public repos.
- ![linux](https://skillicons.dev/icons?i=linux) **Linux** — I run NixOS(btw).
- ![maven](https://skillicons.dev/icons?i=maven) **Maven** — University work.
- ![nginx](https://skillicons.dev/icons?i=nginx) **Nginx** — Or Caddy. TLS and reverse proxying between sites.
- ![npm](https://skillicons.dev/icons?i=npm) **npm** — Shows up from time to time.
- ![postman](https://skillicons.dev/icons?i=postman) **Postman** — Manual HTTP testing.
- ![redis](https://skillicons.dev/icons?i=redis) **Redis** — Caching and refresh token storage.
- ![spring](https://skillicons.dev/icons?i=spring) **Spring** — University work.
- ![vite](https://skillicons.dev/icons?i=vite) **Vite** — We use it to build the frontend of the student accosiations website.
- ![vscode](https://skillicons.dev/icons?i=vscode) **VS Code** — My current IDE.

### Tooling I want to learn
- ![bevy](https://skillicons.dev/icons?i=bevy) **Bevy** — Game development in Rust.
- ![neovim](https://skillicons.dev/icons?i=neovim) **Neovim** — Next time I have a couple years to spare.

### Technologies I've tried or used in the past
- ![c](https://skillicons.dev/icons?i=c) **C** — Mostly for learning purposes.
- ![gitlab](https://skillicons.dev/icons?i=gitlab) **GitLab** — Self hostable as an alternative to Microsoft.
- ![kubernetes](https://skillicons.dev/icons?i=kubernetes) **Kubernetes** — Ran my own GitHub Actions Runner Controller once(but this is a bit overkill and unnecessary)
- ![processing](https://skillicons.dev/icons?i=processing) **Processing** — This is where I'd say I learned to program.
- ![tailwind](https://skillicons.dev/icons?i=tailwind) **Tailwind** — Have tried it, prefer SCSS personally.
- ![arduino](https://skillicons.dev/icons?i=arduino) **Arduino** — Have had some hobby interest in electronics.
- ![sketchup](https://skillicons.dev/icons?i=sketchup) **SketchUp** — Useful for simple design, like appartment plans or simple 3D-prints.

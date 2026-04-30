<p align="center">
  <img src="./banner.png" alt="Header" />
</p>

<h1 align="center">Hi there 👋</h1>

<p align="center">
  Welcome to my GitHub page. This is where you can see what I'm currently working on. Have a look around!
</p>

<p align="center">
  You can check out my showcase projects over on <a href="https://github.com/MPM-Labs">MPM-Labs</a>
</p>

<p align="center">
  <a href="#who-am-i">Who am I</a> •
  <a href="#focus--philosophical">Philosophy</a> •
  <a href="#focus--concrete">Current Focus</a> •
  <a href="#work">Work</a> •
  <a href="#technologies-i-use-or-have-used">Tech</a>
</p>

---

## Who am I?

My name is **Jonas** and I am a software engineering student at **Oslo Metropolitan University**.

I love understanding how things work, and can never stop myself from investigating something I don't understand.

In addition to attending OsloMet, I am also the corporate contact and event manager at [**Ditio**, the student association for IT students](https://www.linkedin.com/company/ditio-linjeforening).

---

## Focus — concrete

Currently, I am learning **Rust**. I like its unique position as a fast, compiled language with safeguards you would often only find in slower, interpreted languages.

I am also trying to learn more about **functional languages**. This is not just about efficiency in terms of raw execution speed, but about efficiency in terms of development time. Functional programming offers guarantees like safe concurrency, testability and more. Even if I don't end up working with it daily, it's worth learning. I use **Haskell**. On the side, I'm reading [Category theory for programmers by Bartosz Milewski](https://bartoszmilewski.com/2014/10/28/category-theory-for-programmers-the-preface/).

<p align="center">
  <img src="./image.png" alt="Quote" /><br>
  <em>"A monad is just a monoid in the category of endofunctors."</em><br>
  — Saunders Mac Lane, <em>Categories for the Working Mathematician</em> (1971)
</p>

Nix deserves its own mention. It's a purely functional language drawing heavily on Haskell for its inspiration. It is, however, not primarily intended as a general purpose language. It is Turing complete, but its purpose is declaring and defining packages, system configurations, development environments, and much more. In general it provides a lot of great tooling involved in software development. I use it for all my projects, as well as for configuring all my machines, which run [NixOS](https://nixos.org/) (a Linux distro based on the Nix package manager that is used with the Nix programming language).

<details>
<summary><strong>🔧 My current Nix deep-dive (click to expand)</strong></summary>

<br>

Recently I've been focusing on the practical use cases of Nix. My [portfolio page](https://jonas.baugerud.no) serves as a real-world test bed for a full Nix-based pipeline:

1. **Build** — The site is written in Rust using [Leptos](https://www.leptos.dev/). Nix builds the binary and all static assets reproducibly. Same inputs, same outputs, every time — like Docker, but more deterministic.
2. **Package** — The build output is wrapped in a **NixOS module** that declares exactly how to run it, with configurable options for tweaking behavior.
3. **Test** — The module runs inside a NixOS VM, letting me validate the full server environment before it ever touches production. This also enables automated integration tests with virtual servers and clients.
4. **Deploy** — [My own deployment tool](https://github.com/MPM-Labs/nixos-deployment-template) handles server bootstrapping, updates, and secrets management via GitHub Actions and environment secrets. Binary caching bridges source and binary deployment, keeping build times low on resource-constrained servers.

As a bonus, Nix gives me deterministic, language-agnostic dev environments that live in the Git repo and work identically for every contributor.

Simply put, **Nix is incredible.**

</details>

---

## Focus — philosophical

Good software accounts for ethical, societal and practical considerations. It's not only functional, but also maintainable and well documented — able to evolve with the client's needs and be passed to other developers with little friction.

I have a great interest in finding *"proper"* solutions to problems. More and more I find myself preferring expert books and official documentation over less formal sources like blogs or guides. That's not to take away from the wonderful part of the software world that is sharing and helping each other. It's just important to verify against official sources — otherwise you hit pitfalls like security holes and solutions that only work _sometimes_.

I care about efficiency. Modern hardware is fast, but energy consumption and scalability still matter, and I find it more satisfying to work in compiled, statically-typed languages where sloppiness has less room to hide. This will likely explain many of the technologies, languages and techniques I prefer using in my work.

---

## Work

> 💼 **I'm actively looking for a job opportunity within software engineering.**

I'm especially interested in roles involving Rust, systems programming, or infrastructure/tooling — but I'm open to anything where correctness and craftsmanship matter.

<p align="center">
  <a href="https://www.linkedin.com/in/jonas-baugerud/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://jonas.baugerud.no">
    <img src="https://img.shields.io/badge/Website-000000?style=for-the-badge&logo=firefox&logoColor=white" alt="Website" />
  </a>
</p>

---

## Technologies I use or have used

### 🟢 Languages I know well

<table>
  <tr>
    <td align="center" width="80"><img src="https://skillicons.dev/icons?i=rust" /><br><sub><b>Rust</b></sub></td>
    <td>My personal go-to. Can be used for almost anything, from low level systems to web servers. I even use it to compile WASM for my portfolio website.</td>
  </tr>
  <tr>
    <td align="center"><img src="https://skillicons.dev/icons?i=nix" /><br><sub><b>Nix</b></sub></td>
    <td>More tooling-oriented. I use it in all my projects. It packages software and guarantees correct deployment.</td>
  </tr>
  <tr>
    <td align="center"><img src="https://skillicons.dev/icons?i=bash" /><br><sub><b>Bash</b></sub></td>
    <td>Always useful.</td>
  </tr>
  <tr>
    <td align="center"><img src="https://skillicons.dev/icons?i=postgres" /><br><sub><b>PostgreSQL</b></sub></td>
    <td>You can do remarkably powerful things with SQL and PL/pgSQL.</td>
  </tr>
  <tr>
    <td align="center"><img src="https://skillicons.dev/icons?i=py" /><br><sub><b>Python</b></sub></td>
    <td>For quick prototyping and university courses.</td>
  </tr>
  <tr>
    <td align="center"><img src="https://skillicons.dev/icons?i=java" /><br><sub><b>Java</b></sub></td>
    <td>The main language taught at university.</td>
  </tr>
  <tr>
    <td align="center"><img src="https://skillicons.dev/icons?i=html" /><br><sub><b>HTML</b></sub></td>
    <td>Always important to keep the basics in mind.</td>
  </tr>
  <tr>
    <td align="center"><img src="https://skillicons.dev/icons?i=css" /><br><sub><b>CSS</b></sub></td>
    <td>I prefer writing my own CSS (SCSS) instead of using tools like Tailwind. That being said, design is not my main focus.</td>
  </tr>
  <tr>
    <td align="center"><img src="https://skillicons.dev/icons?i=js" /><br><sub><b>JavaScript</b></sub></td>
    <td>Unavoidable in web work — though I reach for Rust + WASM when I can.</td>
  </tr>
</table>

### 📚 Languages I'm learning

<table>
  <tr>
    <td align="center" width="80"><img src="https://skillicons.dev/icons?i=rust" /><br><sub><b>Rust</b></sub></td>
    <td>Currently working on async understanding.</td>
  </tr>
  <tr>
    <td align="center"><img src="https://skillicons.dev/icons?i=nix" /><br><sub><b>Nix</b></sub></td>
    <td>Currently working through chapter 5 of <a href="https://edolstra.github.io/pubs/phd-thesis.pdf">the thesis</a>.</td>
  </tr>
  <tr>
    <td align="center"><img src="https://skillicons.dev/icons?i=bash" /><br><sub><b>Bash</b></sub></td>
    <td>I often bump into commands I haven't used before and try to get familiar with as many as possible. (technically I use zsh)</td>
  </tr>
  <tr>
    <td align="center"><img src="https://skillicons.dev/icons?i=haskell" /><br><sub><b>Haskell</b></sub></td>
    <td>Currently reading <a href="https://people.cs.nott.ac.uk/pszgmh/pih.html">Programming in Haskell and [Category theory for programmers by Bartosz Milewski](https://bartoszmilewski.com/2014/10/28/category-theory-for-programmers-the-preface/)</a>.</td>
  </tr>
  <tr>
    <td align="center"><img src="https://skillicons.dev/icons?i=wasm" /><br><sub><b>WASM</b></sub></td>
    <td>I am developing my portfolio site that runs on <a href="https://www.leptos.dev/">Leptos</a>, but would like to learn more about WASM itself.</td>
  </tr>
</table>

### 🛠️ Tooling I use

<table>
  <tr>
    <td align="center" width="80"><img src="https://skillicons.dev/icons?i=docker" /><br><sub><b>Docker</b></sub></td>
    <td>Mostly when collaborating with others. In my personal projects, Nix has replaced Docker.</td>
  </tr>
  <tr>
    <td align="center"><img src="https://skillicons.dev/icons?i=figma" /><br><sub><b>Figma</b></sub></td>
    <td>Prototyping UIs.</td>
  </tr>
  <tr>
    <td align="center"><img src="https://skillicons.dev/icons?i=githubactions" /><br><sub><b>Actions</b></sub></td>
    <td>Love this! Allows a ton of automation and free jobs on public repos.</td>
  </tr>
  <tr>
    <td align="center"><img src="https://skillicons.dev/icons?i=linux" /><br><sub><b>Linux</b></sub></td>
    <td>I run NixOS (btw).</td>
  </tr>
  <tr>
    <td align="center"><img src="https://skillicons.dev/icons?i=maven" /><br><sub><b>Maven</b></sub></td>
    <td>University work.</td>
  </tr>
  <tr>
    <td align="center"><img src="https://skillicons.dev/icons?i=nginx" /><br><sub><b>Nginx</b></sub></td>
    <td>Or Caddy. TLS and reverse proxying between sites.</td>
  </tr>
  <tr>
    <td align="center"><img src="https://skillicons.dev/icons?i=postman" /><br><sub><b>Postman</b></sub></td>
    <td>Manual HTTP testing.</td>
  </tr>
  <tr>
    <td align="center"><img src="https://skillicons.dev/icons?i=redis" /><br><sub><b>Redis</b></sub></td>
    <td>Caching and refresh token storage.</td>
  </tr>
  <tr>
    <td align="center"><img src="https://skillicons.dev/icons?i=spring" /><br><sub><b>Spring</b></sub></td>
    <td>University work.</td>
  </tr>
  <tr>
    <td align="center"><img src="https://skillicons.dev/icons?i=vite" /><br><sub><b>Vite</b></sub></td>
    <td>We use it to build the frontend of the student association's website.</td>
  </tr>
</table>

### 🎯 Tooling I want to learn

<table>
  <tr>
    <td align="center" width="80"><img src="https://skillicons.dev/icons?i=bevy" /><br><sub><b>Bevy</b></sub></td>
    <td>Game development in Rust.</td>
  </tr>
  <tr>
    <td align="center"><img src="https://skillicons.dev/icons?i=neovim" /><br><sub><b>Neovim</b></sub></td>
    <td>Next time I have a couple years to spare.</td>
  </tr>
</table>

### 📦 Technologies I've tried or used in the past

<table>
  <tr>
    <td align="center"><img src="https://skillicons.dev/icons?i=kubernetes" /><br><sub><b>K8s</b></sub></td>
    <td>Ran my own GitHub Actions Runner Controller once (but this is a bit overkill and unnecessary).</td>
  </tr>
  <tr>
    <td align="center"><img src="https://skillicons.dev/icons?i=processing" /><br><sub><b>Processing</b></sub></td>
    <td>This is where I'd say I learned to program.</td>
  </tr>
  <tr>
    <td align="center"><img src="https://skillicons.dev/icons?i=tailwind" /><br><sub><b>Tailwind</b></sub></td>
    <td>Have tried it, prefer SCSS personally.</td>
  </tr>
  <tr>
    <td align="center"><img src="https://skillicons.dev/icons?i=arduino" /><br><sub><b>Arduino</b></sub></td>
    <td>Have had some hobby interest in electronics.</td>
  </tr>
  <tr>
    <td align="center"><img src="https://skillicons.dev/icons?i=sketchup" /><br><sub><b>SketchUp</b></sub></td>
    <td>Useful for simple design, like apartment plans or simple 3D prints.</td>
  </tr>
</table>

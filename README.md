### Dear fellow devs

This is a `Two Minute CV` with an Innopolis University BS'23 Danila Danko.

Today, we are going to look at some of my projects.

## Haskell 🤓

* [script](https://github.com/nix-community/nix-vscode-extensions/blob/master/hs/app/Main.hs) - a crawler for [nix-community/nix-vscode-extensions](https://github.com/nix-community/nix-vscode-extensions). Logging - `co-log-concurrent`, writing to a file - a separate thread that flushes a `TBMQueue`.

* [simplex-cheat](https://github.com/deemp/projects/tree/main/simplex-cheat#readme) - an extremely simplified version of [simplex-chat](https://github.com/simplex-chat/simplex-chat#readme) with a server (`servant`) and clients talking to each other (`servant-client`) and configured via `Nix`. Concurrency - via `stm`, `stm-containers`.

* [lima](https://github.com/deemp/flakes/tree/main/lima#readme) - convert `Haskell` (`.hs`) with `Markdown` comments to `Markdown` (`.md`) and between `Literate Haskell` (`.lhs`) and `Markdown` (`.md`)

* [clerk](https://github.com/deemp/clerk#readme) - declaratively generate spreadsheets ([Hackage](https://hackage.haskell.org/package/clerk))

* [codium-haskell](https://github.com/deemp/flakes/tree/main/templates/codium/haskell#readme) - `Nix` flake template showing 5 ways to run a `Haskell` program + `VSCodium` with `Haskell` extensions

* [try-phi](https://github.com/objectionary/try-phi#readme) - an online interpreter of 𝜑-calculus and [EO](https://github.com/objectionary/eo) language (WIP)

  * [Front end](https://github.com/objectionary/try-phi/tree/main/front#readme)
    * Site - `PureScript` + `Bootstrap 5`
    * Editors - `Codemirror 6` + extensions written in `Typescript`
  * [Back end](https://github.com/objectionary/try-phi/tree/main/back#readme)
    * `Haskell`
    * Parser - `Megaparsec`
      * [EO parser](https://github.com/objectionary/try-phi/blob/main/back/language-utils/eo-utils/src/ParseEO.hs)  - a parser of EO. Provides a convenient annotated IR (with source mapping) closely resembling the grammar of 𝜑-calculus.
    * Server - `Servant`
    * Hosting - a `Docker` container on `Heroku`. The container is built via `Nix`
  * [Nix flake](https://github.com/objectionary/try-phi/blob/main/flake.nix)
    * Dev tools
    * CI

* [manager](https://github.com/deemp/flakes/tree/main/manager#readme) - easily manage Haskell modules and template files in a `stack` project.

* [nginx-clickhouse-hs](https://github.com/deemp/nginx-clickhouse-hs#readme) - parse nginx logs based on log format and prepare them for loading into a database.

* [repohs](https://github.com/deemp/repohs#readme) - a script for concurrent fetching, unpacking and counting lines in multiple repositories.

* [ФП на языке Haskell (часть 2)](https://stepik.org/cert/1492090) - a course on `Haskell` that I almost [finished](https://stepik.org/users/124553190).

* [br4ch1st0chr0n3](https://codeforces.com/submissions/brachistochrone) - several problems solved in `Haskell` on `Codeforces`

## Nix flakes

* [nix-vscode-extensions](https://github.com/deemp/nix-vscode-extensions) - `GitHub Actions` that use `Nix` and `Python` to generate `Nix` expressions for ~40K VS Code extensions. It's `MapReduce`-like - produce separate expressions in multiple jobs and combine them into a single file.

* [terrafix](https://github.com/deemp/flakes/terrafix#readme) - Generate `Terraform` files from DRY `Nix` expressions (`eDSL`)

* [devops-labs](https://github.com/deemp/devops-labs#readme) - `DevOps` course tasks simplified via `Nix`

* [flakes-tools](https://github.com/deemp/flakes/tree/main/flake-tools) - scripts
  * Update `flake.lock`s in selected directories
  * Push them to [cachix](https://www.cachix.org/)

* [codium](https://github.com/deemp/flakes/tree/main/codium#readme) - `VSCodium` with adjustable extensions and runtime dependencies

* [json2md](https://github.com/deemp/flakes/tree/main/json2md#readme) - Convert `Nix` or `JSON` to `Markdown`. Usage: generate docs for `Nix` infra via `Nix` expressions.

* [flakes](https://github.com/deemp/flakes#readme) - flakes for tools that I use

## Front end 🤕

* [final project](https://github.com/deemp/projects/tree/main/blockchain/final-project#readme) for the Blockchain elective course (unfinished)

* [mini-games](https://github.com/deemp/mini-games) - a calculator game written in `Typescript` + `Boostrap 5` for my sisters to practice arithmetical operations.

* [eo-editor](https://github.com/deemp/eo-editor) - An online editor for EO language featuring syntax highlighting, diagnostics, Lezer Tree printing in console, etc. `Codemirror 6` + `Typescript`

* [phi-editor](https://github.com/deemp/phi-editor) - An online editor for 𝜑 language featuring syntax highlighting, diagnostics, Lezer Tree printing in console, etc. `Codemirror 6` + `Typescript`

## Elm

* [elm-graph-editor](https://github.com/deemp/elm-graph-editor) - an interactive graph editor written in `Elm`.

## Logic programming 🤯

* [Intro to AI Assignment](https://github.com/deemp/AI) - Find an optimal path in a grid maze via `SWI-Prolog`.

## OOP and GUI 🥸

* [Ava-Day](https://github.com/RO-DIS/Ava-day) - Combines an image and path data (once generated by a genetic algorithm) to create a pseudo-3D avatar. Written using `PyQT6` and `Vispy`.

* [Computational Practicum](https://github.com/deemp/ComputationalPracticum) - An app (`PyQT5` + `pyqtgraph`) to plot [IVP](https://en.wikipedia.org/wiki/Initial_value_problem) solutions.

## Low-level programming 🤠

* [Sanitator](https://codeforces.com/profile/sanitator) - I solved around 1K problems on Codeforces in `C++`.

* [vforces](https://github.com/deemp/vforces) - Shows the solutions to some Codeforces problems in `V`. Also, includes the setup instructions for a simple project in [V language](https://github.com/vlang/v)

## University courses

<details>
 <summary>Mostly Robotics</summary>

* [Project 32](https://github.com/deemp/Project-32) - A setup for an olympiad during `Differential Equations` F20 course. The rule was to use `Mathematica` for all solutions

* [F21-TM](https://github.com/deemp/F21TM) - `Theoretical mechanics` course. `Python`

* [F21-Meh](https://github.com/deemp/F21Meh) - `Mechatronics` course. `Python`

* [F21-FoR](https://github.com/deemp/F21FoR) - `Fundamentals of Robotics` course. `Python`

* [F21-RoS](https://github.com/deemp/robotic_systems_labs) - `Fundamentals of Robotics` course. `Python`

* [S22-MM](https://github.com/deemp/M-and-Ms) - `Fundamentals of Robotics` course. `Python`

* [S22-MM](https://github.com/deemp/M-and-Ms) - `Mechanics and Machines` course. `Python`

* [S22-ANC](https://github.com/deemp/ANC) - `Applied Nonlinear control` course. `Python`

* [S22-S&S](https://github.com/deemp/S22-sensors-and-sensing) - `Sensors and Sensing` course. `Python`

</details>

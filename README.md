# astro_todo

> This project is a TODO application built with Astro Framework. 
> 
> This application allows users to create, edit, and delete their TODO list items. The design is created using SASS CSS preprocessor.

## Features
* **CRUD**
  * Create TODO List: Users can add a new TODO item to their list
  * Edit TODOs: Users can edit existing TODO items and save the changes
  * Delete TODOs: Users can delete TODO items from the list
  * Save TODOs: User's changes are saved in browser cookies, allowing them to see their todos on subsequent visits

## Install
* [bun](https://bun.sh/docs)  
    `curl -fsSL https://bun.sh/install | bash`
* [asdf (optional)](https://asdf-vm.com/guide/getting-started.html)
  * Can be used to install `bun`
    ```bash
    asdf plugin add bun
    asdf install bun 1.0.4
    ```

## Setup
1. Clone project
    ```bash
    git clone https://github.com/TamperMonkeyUpp/Astro-Todo-App.git
    ```
2. Navigate to the project folder and open a terminal
    ```bash
    cd astro_todo
    ``` 
3. Install the necessary dependencies
    ```bash
    bun install
    ```
4. Start the application
    ```bash
    bun run dev
    ```
5. Open your browser and go to `http://localhost:4321/` to start using the TODO app

## TODO (heh)
* Fix edit function (maybe. see: FastAPI)
  * Update doesn't _actually_ update -- it overwrites original title and description 
* Migrate API to FastAPI
* Gussy up a bit
  * Color scheme
  * Font
  * Size (viewport)
  * Preview description

## Further Reading
[EralKeskinkurt/Astro-Todo-App [inspo! 🙏]](https://github.com/EralKeskinkurt/Astro-Todo-App)

[Bun Docs](https://bun.sh/docs)

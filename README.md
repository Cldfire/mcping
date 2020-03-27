# mcping

Discord bot written in Rust that pings a Minecraft server with the command `~ping` and displays the status information in chat.

## Config

Create a config file called `config.toml` in the root directory of the project with the following:

```
token = "TOKEN"
address = "ADDRESS"
```

Where
- `TOKEN` is the discord bot token
- `ADDRESS` is the Minecraft server address

## Running

In order to run the project you'll need [Rust](https://www.rust-lang.org/) installed. Once you have it installed and have created the config file you can run the project with `cargo run --release`.

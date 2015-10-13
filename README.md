# Oh My ZSH plugin for Elixir, IEX, Mix and Phoenix

Terminal shortcuts for Elixir developers.

## Install and run
```
cd ~/.oh-my-zsh/custom/plugins
git clone https://github.com/gusaiani/elixir-oh-my-zsh.git elixir
```

Enable it by adding _elixir_ to the [_plugins array_](https://github.com/robbyrussell/oh-my-zsh/blob/master/templates/zshrc.zsh-template#L48).

## Aliases

| Alias                    | Command                          |
| :------------------------| :--------------------------------|
| i                        | iex                              |
| ips                      | iex -S mix phoenix.server        |
| ism                      | iex -S mix                       |
| m                        | mix                              |
| mc                       | mix compile                      |
| mdc                      | mix deps.compile                 |
| mdg                      | mix deps.get                     |
| mdgc                     | mix do deps.get, deps.compile    |
| mdu                      | mix deps.update                  |
| mdua                     | mix deps.update --all            |
| mdun                     | mix deps.unlock                  |
| mduu                     | mix deps.unlock --unused         |
| meb                      | mix escript.build                |
| mec                      | mix ecto.create                  |
| mecm                     | mix do ecto.create, ecto.migrate |
| mem                      | mix ecto.migrate                 |
| megm                     | mix ecto.gen.migration           |
| mer                      | mix ecto.rollback                |
| mho                      | mix hex.outdated                 |
| mn                       | mix new                          |
| mns                      | mix new --sup                    |
| mpgc                     | mix phoenix.gen.channel          |
| mpgh                     | mix phoenix.gen.html             |
| mpgj                     | mix phoenix.gen.json             |
| mpgm                     | mix phoenix.gen.model            |
| mpgs                     | mix phoenix.gen.secret           |
| mpn                      | mix phoenix.new                  |
| mpr                      | mix phoenix.routes               |
| mps                      | mix phoenix.server               |
| mr                       | mix run                          |
| mrnh                     | mix run --no-halt                |
| mt                       | mix test                         |
| hrmec                    | heroku run mix ecto.create       |
| hrmem                    | heroku run mix ecto.migrate      |

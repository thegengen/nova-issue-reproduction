# Nova issue reproduction

I am using the Elixir extension: https://github.com/stollcri/elixir.novaextension
I've looked through its source but I can't see how it can affect search results.

If you do a search in this project for `System` you will only get the results in
`config/config.ex` and `config/config.foo`. I do not get the result in 
`config/config.exs`.

There is no `.gitignore` file in this project.
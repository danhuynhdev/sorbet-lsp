# **DEPRECATED in favor of the official extension [here](https://github.com/sorbet/sorbet/tree/master/vscode_extension)**

# Sorbet LSP

Simple LSP extension for sorbet

# How to install

- Set up sorbet in your project follow sorbet's guide: https://sorbet.org/docs/adopting
- Run `bundle install` from your project root inside of VSCode's terminal => This is to ensure VSCode has access to sorbet
- Making sure `bundle exec srb tc` works since this extension rely on that command.
- Enjoy.

# How to use with RVM
![image](https://user-images.githubusercontent.com/17341000/77855156-d796fe80-7218-11ea-959a-3613c02dd4b9.png)

- Set your bundle/srb path in setting to the rvm bin wrapper path. Note: It should be in `~/.rvm/wrappers/ruby-<your-version>@dashboard`

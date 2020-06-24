# perfin-mongodb
Personal Finance app - Database

Install MongoDB on MacOS

```
brew tap mongodb/brew
brew install mongodb-community
git clone https://github.com/JamesKovacs/zsh_completions_mongodb.git ~/.oh-my-zsh/custom/plugins/mongodb
# Add mongodb in .zshrc plugins
```

Create db directory

```
mkdir -p ~/perfin/data/db
```

To start the db server locally

```
mongod --dbpath ~/perfin/data/db
```


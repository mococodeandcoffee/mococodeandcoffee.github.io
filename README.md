### Environment Setup (macos)
Install `chruby`.

```
$ brew install ruby-install chruby
```
Add the following to `~/.zshrc`, making sure to choose the latest version of Ruby in the last line.

```
# enable chruby
source /usr/local/share/chruby/chruby.sh
source /usr/local/share/chruby/auto.sh
chruby ruby-3.3.3
```

Install the latest version of Ruby (at time of writing this is 3.3.3).

```
$ ruby-install ruby 3.3.3
```

Verify this worked by running `ruby -v`.

Install dependencies

```
bundle install
```

Run Jekyll for development using the following command:

```
bundle exec jekyll serve
```

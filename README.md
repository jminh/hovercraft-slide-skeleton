
### Generate your silde from reStructuredText

[hovercraft](https://github.com/regebro/hovercraft)

# ENV

    $ git clone https://github.com/archaicdust/hovercraft-slide-skeleton.git
    $ cd hovercraft-slide-skeleton

    $ pip3 install -r requirements.txt

# Usage

After edit slide.rst

   $ make html

## Tip - [LiveReload](https://github.com/livereload/LiveReload)

    $ bundle exec guard

### prerequisite

+ [Guard](https://github.com/guard/guard)
+ [guard-livereload](https://github.com/guard/guard-livereload)


Setting

    $ rvm use <ruby_version>
    $ rvm gemset create guard-livereload

    $ rvm gemset use guard-livereload
    OR
    $ rvm use <ruby_version>@guard-livereload

    $ gem install guard-livereload

    $ bundle exec guard

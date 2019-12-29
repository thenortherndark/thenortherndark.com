# Develop

## Clone the project
URL: `https://github.com/thenortherndark/thenortherndark.com.git`
Chose either to
1. Clone it with Source Tree 
2. The command line

## Install Jekyll

Jekyll is a [Ruby Gem](https://jekyllrb.com/docs/ruby-101/#gems) that can be installed on most systems.

1. Install a full [Ruby development environment](https://jekyllrb.com/docs/installation/) - tested with `ruby 2.6.5` install with the DevKit ([Windows Installation](https://github.com/oneclick/rubyinstaller2/releases/download/RubyInstaller-2.6.5-1/rubyinstaller-devkit-2.6.5-1-x64.exe)).
2. Install Jekyll and [bundler](https://jekyllrb.com/docs/ruby-101/#bundler) [gems](https://jekyllrb.com/docs/ruby-101/#gems)
```
gem install jekyll bundler
```
3. Change into your new directory (change the path to where you cloned the repository)
```
cd C:/projects/thenortherndark.com
```
4. Install missing gems
```
bundle install
```
5. Build the site and make it available on a local server
```
bundle exec jekyll serve
```

You should see something like:

```
Configuration file: /thenortherndark.com/_config.yml
            Source: /thenortherndark.com
       Destination: thenortherndark.com/docs
 Incremental build: disabled. Enable with --incremental
      Generating...
 Auto-regeneration: enabled for '.'
    Server address: http://127.0.0.1:4000
  Server running... press ctrl-c to stop.
```

# License
All files in an image format (`.png, .jpg, .jpeg`) and portable document format (`.pdf`) is distributed under `CC BY-NC-ND 3.0`.
The source of the website (all except previously mentioned) is distributed under the `MIT` license.

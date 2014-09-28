### Sublime Text 3 Configurations

My configuration files to make ST3 PHP(Symfony 2), JS, CSS(SASS, Compass) IDE with powerful tools. My real aim stay lightweight and stable.

#### Workstation

I tested this confs on following Linux Distros, please let me know any issues on any other distros or unix like distros and help me to improve documentation for other distros and Unix like distros. 

Ubuntu 12.04 LTS with MATE/Gnome 2

XUbuntu 14.04 LTS with Xface

#### Packages

  Beautifiers

  BracketHighlighter(https://github.com/facelessuser/BracketHighlighter/tree/ST3)

  Pretty JSON(https://github.com/dzhibas/SublimePrettyJson)

  Trailing Spaces(https://github.com/SublimeText/TrailingSpaces)

  Theme - Soda(https://github.com/buymeasoda/soda-theme/)

  Gutter Color(https://github.com/ggordan/GutterColor)


  General Enhancements

  PackageControl(https://sublime.wbond.net)

  SideBarEnhancements(https://github.com/titoBouzout/SideBarEnhancements)

  SublimeOpenFromPath(https://github.com/astronaughts/SublimeOpenFromPath)

  CTags(https://github.com/SublimeText/CTags)

  FileDiffs(https://github.com/colinta/SublimeFileDiffs)

  SFTP(http://wbond.net/sublime_packages/sftp)

  WordHighlight(https://github.com/SublimeText/WordHighlight)

  Auto Backups(https://github.com/akalongman/sublimetext-autobackups)

  SublimeLinter(https://github.com/SublimeLinter/SublimeLinter3)

  Git(https://github.com/kemayo/sublime-text-git)

  Git Config(https://github.com/robballou/gitconfig-sublimetext)

  Github(https://github.com/bgreenlee/sublime-github)

  BetterCompletion(https://sublime.wbond.net/packages/Better%20Completion)
  

  PHP Specific
  
  Phpcs

  SublimeLinter-php(https://github.com/SublimeLinter/SublimeLinter-php)

  SublimeLinter-phpcs(http://benmatselby.github.io/sublime-phpcs)

  Symfony2 Snippets(https://github.com/raulfraile/sublime-symfony2)

  SfCommand(https://github.com/jtwebb/sfcommand)

  XDebug(https://github.com/martomo/SublimeTextXdebug)

  JS Specific

  JSLint(https://github.com/darrenderidder/Sublime-JSLint)

  SublimeLinter-jshint(https://github.com/SublimeLinter/SublimeLinter-jshint)


  HTML / CSS Specific

  Emmet(https://github.com/sergeche/emmet-sublime)

  Compass(https://github.com/WhatWeDo/Sublime-Text-2-Compass-Build-System)

  Syntax Highlighting for Sass(https://github.com/P233/Syntax-highlighting-for-Sass)

  HTML-CSS-JS Prettify(https://github.com/victorporof/Sublime-HTMLPrettify)



#### Capabilities

1.Creates file backups on every save, categorized date/time

2.PHP, HTML, Javascript, Symfony2 autocompletes

3.PHP xdebug debugging

4.PHP formatting/indentation PSR1 or PSR2

5.PHP linting

6.git, github, gists operations

7.prettify json, unprettify json

8.Bracket, quotes matching and shows on gutter area

9.ctrl+shift+o open from path

10.ctrl+shift mouse 1 click  goto definition.CTAGS

11.Syfmony2 snippets

12.Symfony2 operations e.g.assetic:dump

13.Twig syntax coloring

14.Twig snippets

15.Twig Linting

16.HTML formatting/indentation

17.Emmet

18.Gutter color

19.JS linting

20.PHP syntax errors

21.JS syntax errors

22.SASS syntax coloring

23.FTP, SFTP operations

24.JSON To XML

25.Sidebar Enhancments

26.File Diffs

27.Trailing spaces, newlines on save

Many extra functionality.
And still lightweight!   Happy Lightweight Editor!

#### Requirements
jq(http://stedolan.github.io/) installation
#### Installation
1. Install Sublime Text 3
2. get sublime configs from this repo.
cd  ~/.config/sublime-text-3/;
rm -r Packages;
rm -r "Installed Packages";
git clone https://github.com/feyyazesat/sublime-text-3.git configs;
mv configs/* configs/.git configs/.gitignore ../;
3. sudo apt-get install exuberant-ctags
5. pecl install PHP_CodeSniffer
4. sudo apt-get install nodejs
6. npm install jshint -g

7. Install jq
download jq from http://stedolan.github.io/
chmod a+x ~/Downloads/jq
sudo mv ~/Downloads/jq /usr/local/bin/
8. Install Compass http://compass-style.org/install/ https://rubygems.org/pages/download
9. sudo apt-get install php5-xdebug
10. 
#### Shortcuts
You can see all shortcuts which I'm using and which ovverriden 
~/.config/sublime-text-3/Packages/User/Default (Linux).sublime-keymap

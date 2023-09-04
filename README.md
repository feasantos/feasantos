
<div style="display: inline_block">
  <a href="https://github.com/feasantos">
    <img height="175em" src="https://github-readme-stats.vercel.app/api?username=feasantos&show_icons=true&theme=github_dark&include_all_commits=true&count_private=true"/>
    <img height="175em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=feasantos&layout=compact&langs_count=16&theme=github_dark&count_private=true"/>
</div>
  
  
##
<div style="display: inline_block"><br>

  <img align="center" alt="Flutter" height="30" width="40" src="https://github.com/devicons/devicon/blob/master/icons/flutter/flutter-original.svg">
   <img align="center" alt="Swift" height="30" width="40" src="https://github.com/devicons/devicon/blob/master/icons/android/android-original-wordmark.svg">
  <img align="center" alt="Swift" height="30" width="40" src="https://github.com/devicons/devicon/blob/master/icons/swift/swift-original.svg">
  <img align="center" alt="Python" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
  <img align="center" alt="Js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
   <img align="center" alt="Git" height="40" width="50" src="https://github.com/devicons/devicon/blob/master/icons/git/git-plain-wordmark.svg">
   <img align="center" alt="Linux" height="30" width="40" src="https://github.com/devicons/devicon/blob/master/icons/linux/linux-original.svg">
  <img align="center" alt="Vscode" height="30" width="40" src="https://github.com/devicons/devicon/blob/master/icons/vscode/vscode-original-wordmark.svg">
 
</div>
  
  ##
 
<div> 
    
- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9

  env:
    # a github token is required to fetch the contribution calendar from github API
    GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
 
</div>

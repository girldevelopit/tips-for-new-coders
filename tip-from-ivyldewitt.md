# General Tips and Resources

Sourcing information that I found helpful when I was first starting out with coding, and things I've picked up along the way.

## Tips for Getting Started with Open Source, Courtesy of Google's Bard AI

Contributing to open source is a great way to learn new skills, give back to the community, and make a difference in the world. Here are a few basics of contributing to open source:

✨ Find a project you're interested in. 
* There are thousands of open source projects out there, so it's important to find one that you're interested in and that you think you can contribute to. If you're not sure where to start, you can browse the Open Source Initiative's directory or search for projects on GitHub.

✨ Read the project's documentation. 
* Once you've found a project you're interested in, take some time to read the project's documentation. This will help you understand the project's goals, how it works, and how you can contribute.
Find a way to contribute. There are many ways to contribute to open source projects. You can write code, fix bugs, improve documentation, or even just test the project. If you're not sure what to do, you can ask the project's maintainers for help.

✨ Submit your contributions. 
* Once you've made a contribution, be sure to submit it to the project so that the maintainers can review it. If your contribution is accepted, it will be merged into the project and everyone will benefit from it!
Contributing to open source is a great way to learn new skills, give back to the community, and make a difference in the world. If you're interested in getting involved, I encourage you to find a project you're interested in and start contributing today!

*Additional Resources*
[The Open Source Guide](https://opensource.guide/how-to-contribute/)

[The Free Code Camp Beginner's Guide](https://www.freecodecamp.org/news/how-to-contribute-to-open-source-projects-beginners-guide/)

[A Beginner's Bumpy Ride in Open Source| Free Code Camp](https://www.freecodecamp.org/news/a-beginners-very-bumpy-journey-through-the-world-of-open-source-4d108d540b39/)

## Tips for Submitting Your First PR

Here are some tips for submitting your first pull request:

✨ Read the project's guidelines for pull requests. 
* Every project has its own guidelines for pull requests, so it's important to read them before you submit your first one. This will help you understand what the project maintainers are looking for and how you can format your pull request.
  
✨ Test your changes. 
* Before you submit your pull request, it's important to test your changes to make sure they work as expected. You can do this by running the project's tests or by running your own tests.
  
✨ Write a good description. 
* When you submit your pull request, be sure to write a good description of what you changed and why. This will help the project maintainers understand your changes and make it easier for them to review your pull request.
  
✨ Be patient. 
* It can take some time for your pull request to be reviewed and merged. Don't be discouraged if your pull request isn't merged right away. Just keep contributing and eventually your pull request will be merged.
Contributing to open source is a great way to learn new things and give back to the community. If you're interested in submitting your first pull request, I encourage you to follow these tips and make a contribution today!

**Additional Resources**

[How to make your first PR | Free Code Camp](https://www.freecodecamp.org/news/how-to-make-your-first-pull-request-on-github-3/)
[Creating a PR](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request) 


## Setting Up Aliases in Bash or ZSH

> Note: This is applicable to Unix/Linux users.

To simply your workflow, you can setup alises for standard command line syntax, i.e. "git commit -m" can be simplified to a singular world. There are a few systems that do this already for you, such as Oh My Zsh with additional extensions, but here's a quick guide to setting up an alias.

1. Open up your bash_profile or zshrc file. Note: This is a hidden file so you'll likely need to run your open file command for your preferred editor or IDE (`nano/vi/code`/etc.) and then `~./{filename}`.
2. In your file, it's recommended to use a header while doing this, i.e. `# ALIASES` 
3. The syntax for creating an alias is `alias {alias}='standard command'`.
4. Once you are done, run `source ~/.bash_profile/zshrc` to update your changes.
5. Congratulations! You can now use your alias when running lines on the command line.

**Example Aliases**

```
alias gad='git add'
alias gcm='git commit -m'
alias python='python3'
```

**Additional Resources**

[Creating Aliases](https://code2care.org/howto/create-alias-in-macos)

[Creating Aliases Pt 2](https://wpbeaches.com/make-an-alias-in-bash-or-zsh-shell-in-macos-with-terminal/)

[Bonus Resource for Windows Users using Doskey](https://winaero.com/how-to-set-aliases-for-the-command-prompt-in-windows/)


## Misc Useful Resources

[Markdown Guide](https://www.markdownguide.org/basic-syntax/#horizontal-rules)

[Merging vs Rebasing](https://www.geeksforgeeks.org/git-difference-between-merging-and-rebasing/)


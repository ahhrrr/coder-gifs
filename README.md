# coder-gifs

Rewarding open source software contributions for a new generation.

### Purpose

At Code for America, we use "Coder Sounds" to [celebrate the open-source contributions of our staff and fellows][celebrate]. And we've already built [two][github_scream] [generations][flying_chicken] of apps to make it work. 

But, it turns out that loud noises, sounding at seemingly-random intervals, are not a boon to productivity. So, in the spirit of Coder Sounds, and in the process of iterative development, a new idea has emerged: Coder GIFs. When code is pushed to GitHub, we'll use the big-screen TVs in our office to display the coder's personal GIF, along with some info about the commits that were pushed.

### Implementation Notes

The app will have the following functionality

- Authenticate as a GH user/organization and register a GitHuba post-commit hook for any/all repositories.
- Recieve post-commit hooks, and when they are received, display gifs, along with information about the commit, on Billboard (probably using a [HTML snippet](https://github.com/dthompson/billboard/issues/19)).
- Optionally: notify Campfire, Twitter, or play coder sounds.
- GIFs/user info will be stored in an appropriate location, TBD



[celebrate]: http://codeforamerica.org/2011/04/26/github-pushes-screaming-hawks-and-a-culture-of-collaboration/
[github_scream]: https://github.com/codeforamerica/github_scream
[flying_chicken]: https://github.com/codeforamerica/flying_chicken


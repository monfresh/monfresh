### Hi there 👋

I'm [Moncef Belyamani](https://www.moncefbelyamani.com/about/). After 9 years in Civic Tech at [Code for America](https://github.com/codeforamerica), [18F](https://github.com/18F) and [Truss](https://github.com/TrussWorks), I quit my job to try to make a living as a full-time creator. Having helped thousands of people set up Ruby on their Mac over the past 10 years, I knew how painful and time-consuming it is. 

To help people save their precious time and avoid frustration, I built [Ruby on Mac](https://www.rubyonmac.dev/?utm_campaign=gh-readme). With a single command, it sets up a complete Ruby development environment for you in 15 minutes or less! It can also fix common issues people run into when setting up a Mac for development, especially on M1 Macs. If you're having trouble installing Rails, Jekyll, Cocoapods, sqlite, ffi, or some other gem, give Ruby on Mac a try.

I'm building Ruby on Mac in public, and sharing my revenue numbers every week on [Twitter](https://twitter.com/monfresh) as I work towards my goal of $24k by the end of 2022.

## Having trouble running legacy Rails or Jekyll projects on M1 Macs? I can help you!
From talking to Ruby on Mac customers and other Ruby developers, a common pain point is not being able to run legacy Rails and Jekyll projects on M1 Macs. This is due to the projects using old versions of Ruby, and old versions of gems that might not be maintained anymore and that aren't supported on the M1 chip. The gem most people complain about is `therubyracer`. They spend days trying to install it, and either end up giving up or using workarounds they're not happy with.

Instead of spending time getting the impossible to work, I recommend replacing `therubyracer` or eliminating it entirely. In many cases, one of these 3 solutions should work:

- Depending on what you're using `therubyracer` for, you might be able to just remove the gem and use Node instead.
- If the dependency on `therubyracer` comes from something related to `Less`, replace it with `Sass`.
- Try replacing `therubyracer` with `mini_racer`.

If you're still stuck getting your old Ruby projects to run, you can hire me and I'd be happy to help you. I'm taking on a limited number of clients at this time. Feel free to email me at my first name @ rubyonmac.dev and we'll go from there.

## Some of my popular blog posts and talks
[The 6 Characters That Could Bring Down Your Rails App](https://www.moncefbelyamani.com/the-6-characters-that-could-bring-down-your-rails-app/) (Euruko 2021)

[Speeding up Tests With Creativity and Behavioral Science](https://www.youtube.com/watch?v=Rs5HBkPkTSA) (ParisRB 2020)

[Techniques For Improving Your Coding Skills](https://www.moncefbelyamani.com/techniques-for-improving-your-coding-skills/)

[How I Reduced the Memory Consumption of a Ruby gem by 92%](https://www.moncefbelyamani.com/a-trip-down-memory-lane-with-derailed-benchmarks/)

[Why You Should Never Use sudo to Install Ruby Gems](https://www.moncefbelyamani.com/why-you-should-never-use-sudo-to-install-ruby-gems/)


<!--
**monfresh/monfresh** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

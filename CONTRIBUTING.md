# How to get involved in the development of pirateparty.org.uk

**Basic anatomy**:

- [Jekyll][] generates static pages
- Template in HTML using [Liquid][]
- The source code itself is HTML5
  - Styles are written in SASS and build on [Foundation][]
  - JS uses Jquery and Foundation
- Source codes are at [Github][Github]
- Tasks we record in [Github issues][] (do not be afraid to seize!)
- There are several websites. All are stored in [github.com/pirati-web][pirati-web]. There is the main website Pirati.cz, regional websites, register of contracts, etc.

All technologies are chosen because of their adherent learning curve. It is not complicated, but it is already a powerful unit.

How to get acquainted with web development. **Learn**:

1. in general HTML 5 (HTML, JS, CSS), JQuery
2. git (protocol) and github
3. the basis of Jekyll

You should now manage common site editing (adding a new page), fixing minor bugs, and so on.

For true understanding, you will still need the basics of the gulp and get to know the structure of the repository. It comes out of jeykyl, but it's a little more complicated than a regular sample blog. E.g. snippets are used, multiple types of templates, template changes slightly according to yaml front matter.

Ideal first engagement:

1. Choose an issue
2. Make a fork
3. Solve the issue within the fork
4. Update fork (if obsolete)
5. Send pull request
6. Senior admins will comment
7. Make corrections as per review comments
8. Senior admins will accept your changes

Once we know your work, we can individually agree on the next step.

**Who will help you**:

- Noah Stride - the main site supervisor

**Other technical department projects**: if you want something more than HTML, we have other projects written in:

- Angular 2
- Nette
- nodejs

For system administrators, our infrastructure could be interesting:

- os
  - debian
  - centOS
- virtualisation
  - kvm
  - docker
- application
  - nginx
  - postfix
  - redmine

[Jekyll]: http://jekyllrb.com/
[Liquid]: https://shopify.github.io/liquid/
[Foundation]: http://foundation.zurb.com/
[Github]: https://github.com/
[Github issues]: https://github.com/pirati-web/pirati.cz/issues
[pirati-web]: https://github.com/pirati-web/

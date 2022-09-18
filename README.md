This repository contains the sources for the website of [IFIP][ifip] [Working
Group 2.13][wg213] on Open Source Software.

It is a [Jekyll][jekyll]-based static website, rebuilt and deployed
automatically upon `git push` to the main copy of [this repository][wg213repo].
The main published instance of this website is available at
<https://www.ifipwg213.org>.

[ifip]: https://www.ifip.org/
[jekyll]: https://jekyllrb.com/
[wg213]: https://www.ifipwg213.org/
[wg213repo]: https://github.com/ifipwg213/ifipwg213.github.io


Development
-----------

To locally test the website you can proceed as follows:

	$ git clone https://github.com/ifipwg213/ifipwg213.github.io.git
	Cloning into 'ifipwg213.github.io'...
	[...]

	$ cd ifipwg213.github.io
	$ bundle config set --local path 'vendor/bundle'
	$ bundle install
	Fetching gem metadata from https://rubygems.org/............
	Resolving dependencies...
	[...]
	$

	$ # modify the content you like via Markdown *.md files

	$ bundle exec jekyll serve
	[...]
	Server address: http://127.0.0.1:4000/
	Server running... press ctrl-c to stop.

Point your Web browser to <http://127.0.0.1:4000/> and check all your
modifications are in place.


License
-------

The content of this repository is distributed under the terms of the [Creative
Commons Attribution 4.0 International License][ccby4], with attribution to
[IFIP WG 2.13][wg213].

[ccby4]: https://creativecommons.org/licenses/by/4.0/

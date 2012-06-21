### Static website generator with Twitter Bootstrap and HAML

Do you like?

+ HAML instead of plain old HTML
+ Twitter Bootstrap instead of templating from scratch
+ A grain of Ruby and Ruby on Rails concept of partials.

and you want to build a static website/template? Look no further.

### Instructions

Install stasis gem

	gem install stasis
		
Clone and cd into directory

	git clone git://github.com/punjab/bootstrap-haml-static.git
	mv 	bootstrap-haml-static my-static-website
	cd my-static-website
	stasis -d

Find generated static website in public subfolder. For other pages create copies of index.html.haml and hack away.
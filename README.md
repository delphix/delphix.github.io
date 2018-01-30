# delphix.github.io
Delphix open source site at delphix.github.io.

## Running Locally

To get started, you will need to follow the instructions for installing
<a href="https://jekyllrb.com/">jekyll</a>. For a vanilla Ubuntu 16.04 ec2 instance,
this will look like the following:

```
	sudo apt-get update
	sudo apt-get install -y ruby ruby-all-dev gcc make g++ zlib1g-dev libcurl3
	sudo gem install jekyll bundle
	git clone <url>
	cd delphix.github.io
```

One you have jekyll installed, you will need to install the bundle from within the
repository, which will include the latest github-pages plugin required to
get the repository data:

```
	bundle install
```

From then on, you can start the webserver with:

```
	bundle exec jekyll serve
```

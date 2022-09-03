Hi, welcome to my website repository. The code here renders the website at [shreyanand.github.io](shreyanand.github.io).

# Website structure
I'm using a simple HTML theme integrated with Jekyll.

The _\_layouts_ directory has the post templates and _\_posts_ has all the posts in markdown files.

## Adding content
To add a post, follow the conventions of existing posts in the _\_posts_ directory. Note the post naming convention and the inline code at the head of each markdown post.

# Development
You'll need to set up Jekyll to build the the website locally.

When running locally for development, change the url to localhost in config.yml

Use `jekyll serve --trace` to build

Note: You don't need docker or anything to build.

all:
	hugo server --themesDir ../../themes

build:
	rm -fr public
	find * -name '.DS_Store' -delete
	find * -name '._*' -delete
	HUGO_ENV="production" hugo --gc --themesDir ../../themes

public-server:
	cd public && python -m SimpleHTTPServer 1314

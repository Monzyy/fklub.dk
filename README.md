# fklub.dk
Implementation of [fklub.dk](http://fklub.dk) written in the [LAML](http://people.cs.aau.dk/~normark/laml/) Scheme web-framework
> Just because it's legacy code, it doesn't mean thats it's old code
> 
> -- <cite>Albert Einstein 1367</cite>

LAML is a framekwork written by [Kurt Nørmark](http://people.cs.aau.dk/~normark) that enables the use of the Scheme 
programming language for writing dynamic web pages using CGI-programming and [HTML mirror functions](http://people.cs.aau.dk/~normark/laml-distributions/laml/lib/xml-in-laml/mirrors/man/xhtml10-transitional-mirror.html#MANUAL-TOP). 

This is a work-in-progress for the new front-page for [fklub.dk](http://fklub.dk) written in this framework.

## Requirements
- Docker

## Running the webserver
1. Clone the repository
```bash
git clone https://github.com/hrjakobsen/fklub.dk
```
2. Run `docker-compose up`
3. Access the page at http://localhost:4000

You may have to figure out some permission for the daemon user to allow it to read/write files in the /data directory.

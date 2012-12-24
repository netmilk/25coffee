# 25coffee.com website

## Bootstrapping

    $ yeoman init
    [?] Would you like to include Twitter Bootstrap for Compass instead of CSS? (Y/n) y
    [?] Would you like to include the Twitter Bootstrap JS plugins? (Y/n) y
    [?] Would you like to include RequireJS (for AMD support)? (Y/n) y 
    [?] Would you like to support writing ECMAScript 6 modules? (Y/n) n

## Deployemnt (naive)

    $ yeoman build
    $ scp -r dist/* com25coffee@server.hosting.tld:~/25coffee.com/


## Links

http://yeoman.io/gettingstarted.html
https://github.com/apenwarr/git-subtree
http://stackoverflow.com/questions/5977234/how-can-i-push-a-part-of-my-git-repo-to-heroku
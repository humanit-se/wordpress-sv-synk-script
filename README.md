# Wordpress Synkroniserings Script
PHP script för att hämta, unzippa och pusha [svenska Wordpress](https://sv.wordpress.org/releases/) till https://github.com/humanit-se/wordpress-sv

## Author

Jamie Telin

## Requires

* [awk](http://www.cs.princeton.edu/~bwk/btl.mirror/)
* [grep](https://www.gnu.org/software/grep/manual/grep.html)
* [git](https://git-scm.com/)


## Setup

Hämta wordpress-sv git-repo:

```
git@github.com:humanit-se/wordpress-sv.git
```

Kopiera över _sync/_ till _wordpress-sv/_:

```
cp wordpress-sv-synk-script/sync wordpress-sv/
```

## Kör synkroniserings

```
php sync
``

## Tack
`

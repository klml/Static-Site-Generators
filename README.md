Static Site Generators
====================

A definitive list of tools for generating static websites.

# properties

What features does static site generator need. Not everybody needs all, but its a mess if you miss something after stating using it.


* what kind of lightweight markup language (e.g. markdown)
* templates (e.g. django, twig)
* config and html-metadaten managed inline source document or extra file  (e.g. YAML)
* edit, create and commit using shell or webinterface or both?
  * changing content only via sshl/ftp/repositories or additional (protectet) onlineditor for normal users
  * building websiet with CLI or with webserver
* tagging
* real static html files are faster and easyer to host or need still need php|ry|rb
* what kind of repository


## Language Agnostic

* [Hammer](http://hammerformac.com/)
* [Ruhoh](http://ruhoh.com/)
* [Mixture](http://mixture.io/)
* [LiveReload](http://livereload.com/)
* [Site builder console](http://sitebuilder.codeplex.com/)
* [StaticMate](https://staticmate.com/)
* [vimwiki](https://github.com/vim-scripts/vimwiki)

## PHP

### Markdown and [twig](https://github.com/fabpot/Twig)

unless otherwise stated

* [Phrozn](http://www.phrozn.info/en/) additional textile and LESS. Parts from PEAR, Zend Framework 2, Symfony 2, Pirum.
* [PieCrust](http://bolt80.com/piecrust/) Mustache, Less, Sass, Compass and YUICompressor
* [Sculpin](http://sculpin.io/) additional textile
* [Site-builder](https://github.com/inanimatt/site-builder) Symfony2 Components: Yaml, Config, DependencyInjection, ClassLoader, Console. But *just a personal project*.
* [Snowshoe](https://github.com/edvanbeinum/snowshoe)
* [Miblo](https://github.com/rafalp/Miblo)
* [Gen](https://github.com/trq/Gen) <!-- reverse indexer? -->
* [Meinhof](https://github.com/miguelibero/meinhof) using symfony components
* [Hydrastic](https://github.com/bpizzi/Hydrastic) still under *heavy development*.
* [cub](https://github.com/patcoll/cub) yaml, but __no markdown__
* [SG](https://github.com/maxailloud/SG) but but __no markdown__, yaml and [phar](http://php.net/manual/en/intro.phar.php)

### Markdown
but no twig

* [Second Crack](https://github.com/marcoarment/secondcrack) smartypants, dropbox sync; but *it's still rough and unfriendly.*
* [Tempo](https://github.com/catnapgames/Tempo) very simple in 501 lines (386 sloc).
* [Phase](https://github.com/AD7six/phase) MVC and Java (optional).
* [Wadoo](https://github.com/alpacaaa/wadoo) doesn't have a CLI, all actions, like compiling, are webserverbased (''index.php?action=com...'') and all is stored in *data.xml*.
* [Fantastic Windmill](https://github.com/sylvainhalle/FantasticWindmill) own templating system
* [SiteMaker](https://github.com/lonescript/php-site-maker) [yaml](https://github.com/mustangostang/spyc/)

### No markdown

* [Drop-a-Site](https://github.com/herschel666/Drop-a-Site) not static
* [Purepress](https://github.com/megakote/purepress) very simple with 200 lines, plain html no markdown, no template.



## Ruby

* [Nanoc](http://nanoc.ws/)
* [Octopress](http://octopress.org/)
* [NestaCMS](http://nestacms.com/)
* [Middleman](http://middlemanapp.com/)
* [Serve](http://get-serve.com/)
* [Webby](http://webby.rubyforge.org/)
* [{ :awestruct }](http://awestruct.org/)
* [Bonsai](http://tinytree.info/)
* [stasis](http://stasis.me/)
* [hobix](http://hobix.github.io/hobix/)
* [Ace](https://github.com/botanicus/ace)
* [Jekyll](https://github.com/mojombo/jekyll)
* [deplot](https://github.com/cdn64/deplot)
* [Fairytale](https://github.com/46Bit/fairytale)
* [Frank](https://github.com/blahed/frank)
* [Hobix](https://github.com/hobix/hobix/)
* [korma](https://github.com/sandal/korma)
* [Machined](https://github.com/petebrowne/machined)
* [Magneto](https://github.com/donmelton/magneto)
* [toto](https://github.com/cloudhead/toto)
* [Massimo](https://github.com/petebrowne/massimo)
* [Pith](https://github.com/mdub/pith)
* [Serif](https://github.com/aprescott/serif)
* [StaticMatic 2](https://github.com/mindeavor/staticmatic2)
* [StaticMatic](http://rubyforge.org/projects/staticmatic/)
* [Rakeweb](http://rubyforge.org/projects/rakeweb/)
* [Rog](http://rog.rubyforge.org/)
* [rote](http://rote.rubyforge.org/)
* [StaticWeb](http://staticweb.rubyforge.org/)
* [webgen](http://webgen.rubyforge.org/)
* [DynamicMatic](https://github.com/nex3/dynamicmatic)
* [Yurt CMS](http://yurtcms.roberthahn.ca/)
* [zenweb](http://www.zenspider.com/projects/zenweb.html)
* [RubyFrontier](http://www.apeth.com/RubyFrontierDocs/default.html)
* [Rassmalog](http://snk.tuxfamily.org/lib/rassmalog/doc/guide.html)
* [gollum-site](https://github.com/dreverri/gollum-site)
* [Shelob](https://github.com/rubyworks/shelob)
* [High Voltage](https://github.com/thoughtbot/high_voltage)
* [Brochure](https://github.com/sstephenson/brochure)
* [Gravity](https://github.com/owainlewis/gravity)
* [Laze](http://avdgaag.github.io/laze/)

## Node

* [yassg](https://npmjs.org/package/yassg)
* [Quill](https://npmjs.org/package/quill)
* [blacksmith](https://github.com/flatiron/blacksmith/)
* [Petrify](https://github.com/caolan/petrify)
* [Punch](https://github.com/laktek/punch)
* [romulus](https://github.com/felixge/node-romulus)
* [Wintersmith](http://jnordberg.github.io/wintersmith/)
* [Hexo](https://github.com/tommy351/hexo)
* [DocPad](https://github.com/bevry/docpad)
* [Scotch](https://github.com/techwraith/scotch)
* [Wheat](https://github.com/creationix/wheat)
* [Nog](https://github.com/c9/nog)
* [Codex](https://github.com/logicalparadox/codex)
* [jen](https://github.com/rfunduk/jen)
* [Gabby](https://github.com/alexmingoia/gabby)
* [node-jekyll](https://github.com/wangbus/node-jekyll)
* [Wanna](https://github.com/shaoshuai0102/wanna)
* [Statix](https://github.com/ff0000/statix)
* [Blode](https://github.com/stackoverflow/blode)
* [Apto](https://github.com/modparadigm/apto)
* [Enfield](https://github.com/fortes/enfield)
* [Kel](https://github.com/koostudios/kel)
* [Jott](https://github.com/jonsherrard/jott)
* [markx](https://github.com/jgallen23/markx)
* [pagen](https://github.com/jawerty/pagen)
* [bread](https://github.com/pvorb/node-bread)
* [node-blog](https://github.com/creationix/node-blog)
* [Pop](https://github.com/alexyoung/pop)
* [Poet](http://jsantell.github.io/poet/)
* [Derby](http://derbyjs.com/)
* [Heckle](http://macwright.org/heckle/)
* [Brunch](http://brunch.io/)
* [Yeoman](http://yeoman.io/)
* [Hoodie](http://hood.ie/)
* [volo](http://volojs.org/)
* [Mimosa](http://mimosajs.com/)
* [Lumbar](https://github.com/walmartlabs/lumbar)
* [Lineman](https://github.com/testdouble/lineman)
* [Grunt](http://gruntjs.com/)
* [GruntStart](http://tsvensen.github.io/GruntStart/)
* [Modjs](http://modulejs.github.io/modjs/)
* [Automaton](http://indigounited.com/automaton/)
* [Woods](https://github.com/studiomoniker/woods)
* [Kerouac](https://github.com/jaredhanson/kerouac)

## Python

* [Acrylamid](https://github.com/posativ/acrylamid)
* [Cactus](https://github.com/koenbok/Cactus)
* [Chisel](https://github.com/dz/chisel)
* [Composer](https://github.com/shazow/composer)
* [Hyde](https://github.com/lakshmivyas/hyde)
* [jinjet](https://github.com/jokull/jinjet)
* [Markbox](https://github.com/myfreeweb/markbox)
* [Speech Hub](https://github.com/alvesjnr/speechhub)
* [staticjinja](https://github.com/Ceasar/staticjinja)
* [tahchee](https://github.com/sebastien/tahchee)
* [Wok](https://github.com/mythmon/wok)
* [Voldemort](https://github.com/semk/voldemort)
* [Pyll](https://github.com/arthurk/pyll)
* [Pelican](https://github.com/getpelican/pelican/)
* [PILCROW](http://inky.github.io/pilcrow/)
* [Fragments](http://glyphobet.github.io/fragments/)
* [Syte](https://github.com/rigoneri/syte)
* [drupan](https://github.com/fallenhitokiri/drupan)
* [Blatter](https://bitbucket.org/jek/blatter/)
* [Poole](https://bitbucket.org/obensonne/poole)
* [Blogofile](http://www.blogofile.com/)
* [cyrax](https://pypi.python.org/pypi/cyrax)
* [Markdoc](http://markdoc.org/)
* [mynt](http://mynt.mirroredwhite.com/)
* [Nikola](http://nikola.ralsina.com.ar/)
* [Socrates](http://honza.ca/socrates/)
* [Jinja](http://jinja.pocoo.org/)
* [Mako](http://www.makotemplates.org/)
* [Sphinx](http://sphinx-doc.org/)
* [Wok](http://wok.mythmon.com/)
* [StrangeCase](https://github.com/colinta/StrangeCase)
* [Igor](https://github.com/aconbere/igor)
* [Elyse](https://github.com/FSX/elyse)
* [growl](https://github.com/xfire/growl/)
* [handcrank](https://pypi.python.org/pypi/handcrank)
* [Nib](https://github.com/jreese/nib)
* [Webber](http://gitorious.org/webber)
* [Lightning](https://github.com/borismus/lightning)
* [Volt](https://github.com/bow/volt/)
* [Glynn](https://github.com/teiko/glynn)
* [Frozen-Flask](http://pythonhosted.org/Frozen-Flask/)
* [PyBlosxom](http://pyblosxom.github.io/)
* [Floyd](https://github.com/nikcub/floyd)
* [Cipherpress](https://github.com/lejonet/Cipherpress)
* [Engineer](https://github.com/tylerbutler/engineer)
* [Firedrop2](http://www.voidspace.org.uk/python/firedrop2/)
* [rstblog](https://github.com/mitsuhiko/rstblog)
* [Obraz](http://obraz.pirx.ru/)
* [django-medusa](https://github.com/mtigas/django-medusa/)
* [fjord](http://dkuntz2.github.io/fjord/)
* [Serious Chicken](http://rtorr.github.io/serious-chicken/)

## Common Lisp

* [coleslaw](http://www.cliki.net/coleslaw)
* [regenerate](https://gist.github.com/TeMPOraL/4190622)

## Java

* [FMPP](http://fmpp.sourceforge.net/)
* [JBake](http://jbake.org/)

## Shell

* [fugitive](https://gitorious.org/fugitive)
* [Vee](http://www.0x743.com/vee/)
* [simple-static](https://github.com/wlangstroth/simple-static)
* [sw](http://nibble.develsec.org/projects/sw.html)
* [werc](http://werc.cat-v.org/)

## Go

* [gostatic](https://github.com/piranha/gostatic)
* [Hastie](https://github.com/mkaz/hastie)
* [jkl](https://github.com/drone/jkl)

## C Sharp

* [Graze](https://github.com/mikoskinen/graze)

## C ++

* [Leo](http://leohtml.sourceforge.net/)

## Haskell

* [Hakyll](http://jaspervdj.be/hakyll/)
* [yst](https://github.com/jgm/yst)

## Bash

* [Pagegen](http://pagegen.phnd.net/)

## Groovy

* [Rizzo](https://github.com/fifthposition/rizzo/)

## Ocaml

* [Ultra Simple Site Maker](http://loup-vaillant.fr/projects/ussm/)

## C and Perl

* [Website Meta Language](http://www.thewml.org/)
* [Templer](https://github.com/skx/templer)
* [blosxom](http://blosxom.sourceforge.net/documentation/users/configure/static.html)

## Clojure

* [Static](http://nakkaya.com/static.html)
* [misaki](https://github.com/liquidz/misaki)

## Scala
* [monkeyman](https://github.com/wspringer/monkeyman)

## Dropbox

* [Scriptogr.am](http://scriptogr.am/)
* [Telegram](https://telegr.am/)
* [Site44](http://www.site44.com/)
* [Pancake.io](https://www.pancake.io/)
* [DropPages](http://droppages.com/)
* [KISSr](http://www.kissr.com/)
* [Chili](http://chilipy.com/)
* [Drapache](https://github.com/louissobel/Drapache)
* [Calepin](http://calepin.co/)

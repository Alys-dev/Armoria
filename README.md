# Armoria is a fork of Wikitten 

_(Wikitten is originally developped by Devaneando)_

Let's start our journey with Armoria.

First, let me explains why I choosed to work on a fork of Wikitten.

I searched for a quick deployment of a Snippets and documents storages.
Because, when I travel accross the web...

I can easily let my concentration be overrided by the ammount of Free top-neat quality PHP (and other programming languages) code snippets !
But not only, sometimes, I'm facing through Articles like those on Medium.com which are so epic.

Then, I discovered Wikitten from a random surf, while searching for a PHP errors handlers (the same that Laravel have: Whoops).
I was clearly captivated by its power..

But, then I looked some other repositories (concentration dismissed.. again..).

Finally, I was teleported (whiiiz,by magic, yeah yeah!) onto a Javascript Template Engine for ... Javascript from Mozilla named: Nunjucks..

What was the relation between Nunjucks and Wikitten? Nothing related between these two basecode !
Haha..
Again, concentration was gone... and... me too with it.. lol.

Well, hours after that, I was imagining in my head a way to store my code snippets, links, and more !
Finally.. I searched onto Github to see what it have to offers me!

And discovered Wikitten.

I searched for a demo on the official site, but it was gone.

Then, looked on Wayback Machine, and I was able to see how it presents, I loved the core of the presentation: Keeping It Simple and Stupid (KISS approach).

But, I also was epicly disappointed: the project was for PHP 5.

I **hated PHP 5 days to days, month to month and years to years past due to my work** (but I love PHP as I love PHP which is clear I think how many amount of love I love PHP, aww.. headache incoming.. Sorry..), at mine own small Web Agency. (I insist onto the word SMALL).
So.. It was impossible for me to resignate to re-install a very dangerous installation of PHP 5 docker stacks.
And, finaly, I was thinking to me:

And.. if i will fork the Wikitten project and code onto that marvelous base my own WIKI and storage documents logic?
And, all for at least PHP 7.4+ (and 8.x branch of course).

I was blank, hypnotized girl with an infinite ideas flowing in my head: YES, then Armoria was take alive!

OF COURSE, I would be able to make one from the scratch, but as I have a f\*ckn... PHP 5.3(yeah... let me cry) customer application to port onto PHP 8,
I just think it will be a great training challenge to port Wikitten to a more recent version of PHP !

***Wikitten was great, but as that project is no more maintained, then I can't hope for a revision in 2023 (and more..)***

# Say hello to Armoria!

Armoria is then a modernized fork foundation-based of old well-known Wikitten.
Armoria have goal to be like Wikitten

 [1] a WIKI written in a custom PHP framework (a more likely customized MVC which I already developped) with no heavy needs for framework, (named as AppRunner)

 [2] fast with a quick deploy (with no need for MySQL, only pure PHP and then a LAP (without MySQL lol) will be needed),

 [3] a great location to stash and stack your documents (which can be possible to get a personal/public link to let other see them),

 [4] where Documents can be everything what you can imagine: notes, programming code snippets, ideas, and more!
 
# What is planned in Armoria (that modernized version of Wikitten) !?

- REMOVING:
> ¤ old code base which is only for PHP 5 and prior to PHP 5 (the main codebase is therefore a very solid good one!).
> 
> ¤ docker support: I do not need for that.

- REPLACING:
> ¤ jQuery 1.11.2 will be replaced by jQuery 3+ (at least from nowadays recent up-to-date versions)
> 
> ¤ Prettifier will be replaced by PrismJS (for handling coloration of syntaxic code)
> 
> ¤ the way the file are stored and readed: 
> 
> **(Wikitten)** _it was just original files which was loaded by direct loading_ 
> 
> **(Armoria)** _always direct loading, but now, the file name would be extracted from a JSON associated file which will contains metadata of the file and pretty URL to it (exit the old formed one ```FILE NAME OF THE DAY.txt``` say hello to ```file-name-o-the-day.php``` it will ensure that our files can have a dissocied name from it's file name url accessed within Armoria.)_
> 
> ¤ files was loaded through fopen() functions, then it will be replaced by file_get_contents(), more easy to maintain.

- ADDING:
> ¤ then adding a SleekDB implementation in order to even more handle the files by a NoSQL database. (a PHP solid one).
> 
> ¤ adding a way to make code-snippets publics by creating such a "shared link", which will be revokable at any time.

- FUTURE ROADMAP?:
> ¤ in brief:
> 
> ~ implement FomanticUI framework, (I love it, aswell uiKit): I hate Bootstrap!

That would be amazing, isn't it ?

Not sure if all it will, but from my viewpoints, it wouldbe amazing

Cheers and have fun with Armoria in next months.

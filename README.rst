Bash_completion scripts for genomics tools.  These scripts are based on the work of Charles Plessy.  Many thanks to Charles for taking the initiative to do this.  I enjoy convenience very much.

It allows you to do things like::

    samto[TAB][TAB] v[TAB][TAB]

and get::

	samtools view

or::

	samtools f[TAB][TAB]
	
and get::

	faidx     fixmate   flagstat

or::

    bedt[TAB][TAB] in[TAB][TAB]

and get::

    bedtools intersect


or::

    bedt[TAB][TAB] g[TAB][TAB]

and get::

	genomecov  getfasta   groupby

Installation
============

1. First you need to install bash_completion.  See this:

https://github.com/bobthecow/git-flow-completion/wiki/Install-Bash-git-completion

2. Second, copy the scripts in this repo to the appropriate (depending on how you installed bash_completion) directory.  For example, with homebrew, it would be::

    /usr/local/etc/bash_completion.d/


3. Source your bash_profile and be on your way.






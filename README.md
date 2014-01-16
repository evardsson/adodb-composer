adodb
=====

ADOdb5 Fork for use with composer

[ADOdb](http://adodb.sourceforge.net/) composer-available copy of the [latest version](https://sourceforge.net/projects/adodb/files/) *as time permits*.

Pay attention to which branch you are including:

 * master - basic ADOdb (no exception or session usage)
 * plus_exceptions - ADOdb with Exceptions included
 * plus_session1 - ADOdb with Sessions (version 1) included
 * plus_session2 - ADOdb with Sessions (version 2) included
 * plus_both1 - ADOdb with Exceptions and Sessions (version 1) included
 * plus_both2 - ADOdb with Exceptions and Sessions (version 2) included
 * plus_sessions_crypt1 - ADOdb with encrypted Sessions (version 1) included
 * plus_sessions_crypt2 - ADOdb with encrypted Sessions (version 2) included
 * plus_both_crypt1 - ADOdb with Exceptions and encrypted Sessions (version 1) included
 * plus_both_crypt2 - ADOdb with Exceptions and encrypted Sessions (version 2) included
 
Note that the only differences in the branches are changes to the composer.json included with each.

todo:
-----

Figure out a way to include the proper items in composer without resorting to a bunch of branches

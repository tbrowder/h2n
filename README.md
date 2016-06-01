# h2n 

This public repository is a place holder for code for the Perl 5 program *h2n* awaiting copyright, licensing, and public use determination from the original publisher, *O'Reilly Media, Inc*.

I sent an e-mail to them per instructions on page xix in the 5th edition of their book, *DNS and BIND*, by Cricket Liu and Paul Albitz.  That book contains references to, discussion of, code from, and a link to the program *h2n*.  The e-mail was addressed to <permissions@oreilly.com> and was sent at 2016-05-31, 0634 CDT.  In it I stated the following:

> Dear Sir or Madam:
>
> I would like to determine if all or any of the following uses of the subject program [*h2n*] are permitted:
>
> 1.  Place copies of the original code obtained from your ftp site into a public repository on <https://github.com>.
>
> 2.  Modify the code to correct errors.
>
> 3.  Modify the code to change formatting.
>
> 4.  Extract subroutines into one or more separate modules.
>
> 5.  Add new features.
>
> 6.  Delete features which are or may become obsolete.
>
> 7.  Translate the code into another language (specifically Perl 6).
>
> 8.  Rename the program.
>
> 9.  Add a GNU Public License to the code as it is initially placed into the repository.
> 
> Note that the code in question is found in several public places in the wild on the Internet but with no license and possibly no attribution, and that has prompted my query.  I believe that I can use the code as is but it would be so much better if it could be treated with specific license terms.
>
> Thank you for your assistance.
>
> Sincerely yours,
>
> -Tom
>
> Thomas M. Browder, Jr.

Update: success!

I got a message from Cricket Liu (on reddit <https://www.reddit.com/r/dns/comments/4lp7v9/cricket_lius_perl_program_h2n/d3rwex6?context=3>) which said the program came from HP (with permission) and included a link to <ftp://ftp.hpl.hp.com/pub/h2n/h2n.tar.gz>.  When going to the ftp site I found file <ftp://ftp.hpl.hp.com/pub/h2n/h2n-2.61rc8> which does contain licensing info which is quoted here:

> \#    Copyright (c) 2010, Andris Kalnozols <andris@hpl.hp.com>
> \#
> \#    Permission to use, copy, modify, and/or distribute this software for any
> \#    purpose with or without fee is hereby granted, provided that the above
> \#    copyright notice and this permission notice appear in all copies.
> \#
> \#    THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES
> \#    WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF
> \#    MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR
> \#    ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES
> \#    WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN
> \#    ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF
> \#    OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
> \#
> \#
> \#    Originally written by Paul Albitz and Ken Stone of Hewlett-Packard
> \#    h2n-hp,v 1.96 1999/12/02 22:05:56 milli (Michael Milligan), Hewlett-Packard
> \#    Extended to v 2.61rc8 2010-08-31 by Andris Kalnozols, HP Labs


I have now incorporated that file into this repo.

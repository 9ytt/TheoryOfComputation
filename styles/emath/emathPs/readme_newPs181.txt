emathPs.sty (v 1.81 2010/05/02) $B$K%m!<%I%*%W%7%g%s(B
    remakefalse
    pdf
    PDF
$B$r?7@_$7$^$7$?!#(B

1) remakefalse
  emathPs.sty $B$O%G%U%)%k%H$G$O(B
  $B!!!!(B[remake] $B%*%W%7%g%s$,$D$$$F$$$k(B
  $B$b$N$H$7$F$"$j$^$9!J(Bv 1.75 2010/03/07$B!!0J9_!K!#(B
  remakefalse $B$O$=$l$rBG$A>C$9$b$N$G!$(Beps $B%U%!%$%k$O99?7$5$l$^$;$s!#(B

$B0J2<$O(B
$B!!!!(Bdvipdfm(x) $B$rMQ$$$k(B
$B$H$$$&$N$,A0Ds$G$9!#(B
$B0J2<$N%=!<%9$r(B 
$B!!!!(Bdviout (or dvips) $B$G8+$l$J$$!$8+$?$i$*$+$7$$(B
$B$J$I$H$$$&%/%l!<%`$O!V>l30!W$G$9!#(B

2) pdf
  2-1) remakefalse $B$HJ;MQ$9$k$N$,86B'$G!J>-Mh$OC1FH;HMQ$b2DG=$H$7$?$$!K!$(B
    $B!!!!(Bpdf $B$,B8:_$7$J$$>l9g(B
    $B$^$?$O(B
    $B!!!!(Bpdf $B$,(B eps $B$h$j8E$$>l9g(B
    $B$K$O!$(Beps $B$r(B pdf $B$KJQ49$7$^$9!#(B
    $B!J$=$N:]!$(Bxbb $B%U%!%$%k$b:n@.(B/$BJQ99$5$l$^$9!#!K(B
  2-2) eps $B$G$O$J$/!$(Bpdf $B$rFI$_9~$_$^$9!#(B

3) PDF
  remakefalse $B$HJ;MQ$9$k!$$H$$$&$N$O(B pdf $B%*%W%7%g%s$HF1MM$G$9!#(B
  pdf $B%*%W%7%g%s$G$O!$I,MW$N$"$k>l9g$O(B eps --> pdf $BJQ49$r$7$^$9$,!$(B
  PDF $B%*%W%7%g%s$O!$(Beps $B$K$OL\$b$/$l$:!$(Bpdf $B$rFI$_$K9T$-$^$9!#(B
  eps $B$H(B pdf $B$NHf3S$J$I$r$7$J$$J,9bB.$K$J$j$^$9$,!$(B
  eps $B$,99?7$5$l$F$$$F$b8E$$(B pdf $B$rFI$s$G$7$^$$$^$9!#(B
  eps $B$r99?7$7$?>l9g$O(B 
  $B!!!!(Bpdf $B%*%W%7%g%s$G(B pdf $B$b99?7(B
  $B$7$?$&$($G(B PDF $B%*%W%7%g%s$rMQ$$$^$9!#(B

$BCm(B1. eps$B"*(Bpdf $BJQ49$O(B
        epstopdf
     $B$r;HMQ$7$F$$$^$9!#(B
     $B$3$l$r5qH]$7$?$$>l9g$O!$JLES2?$i$+$NJ}K!$G(B pdf $B$r:n@.$7$F$*$1$P!$(B
     epstopdf $B$O5/F0$7$^$;$s!#(B

$BCm(B2. $B%U%!%$%k$N%?%$%`%9%?%s%W<hF@$r(B perl $B$N(B stat $B4X?t$G9T$C$F$$$^$9$+$i!$(B
$B!!!!(Bperl $B$H$NO"7H$,I,MW$G$9!#(B

$BCm(B3. EPSfilename=.....
    $B$K$*$1$k%U%!%$%kL>;XDj$r9T$&>l9g$O!$(B
    $B!!!!!!3HD%;R(B eps 
    $B$r86B'$H$7$^$9!J(Bpdf $B$G$O$J$$!K!#(B
    $B%m!<%I%*%W%7%g%s(B pdf(PDF) $B$r$D$1$?>l9g$O!$(B
    $B!!!!!!(B.....eps $B$r(B ..... pdf
    $B$HFI$_BX$($F(B pdf $B$rFI$_$K$$$-$^$9!#(B

$BCm(B4. [remakefalse,pdf] $B%*%W%7%g%s$O!$(B
$B!!!!8D!9$N(B pszahyou(*)$B4D6-$K$D$1$k$3$H$b2DG=$G!$(B
$B!!!!$=$N>l9g$O!$Ev3:(B pszahyou(*)$B4D6-$N$_$KF/$-$^$9!#(B

$BCm(B5. $BJ8=qA4BN$K$O(B
$B!!!!!!!!(B\usepackage[remakefalse,pdf]{emathPs}
$B!!!!$H$7$?>l9g!$(B
$B!!!!FCDj$N(B pszahyou*$B4D6-$K(B [remake,eps] $B%*%W%7%g%s$r$D$1$k$H(B
$B!!!!Ev3:(B pszahyou(*)$B4D6-$K$D$$$F$N$_(B
$B!!!!!!!!(Beps $B%U%!%$%k$O99?7$5$l!$(B
$B!!!!!!!!(Bpdf $B$G$O$J$/(B eps $B$,FI$_9~$^$l$^$9!#(B
$B!!!!$=$N$"$H$G(B remake,eps $B%*%W%7%g%s$r>C5n$7$F%?%$%W%;%C%H$9$l$P!$(B
$B!!!!(Bpdf $B$,:n@.!J99?7!K$5$l!$(Bpdf $B$,FI$_9~$^$l$k$3$H$K$J$j$^$9!#(B
$B!!!!!!8=;~E@$G$O!$(B[remake]$B%*%W%7%g%s$N$_$GF1$8F0:n$r$7$^$9$,!$(B
$B!!!!>-Mh(B pdf $B%*%W%7%g%s$,C1FH$N0UL#$r;}$D$h$&$K$J$l$P!$(B
$B!!!!F0:n$,JQ$o$C$F$/$k2DG=@-$,$"$j$^$9!#(B

$BCm(B5' $BJ8=qA4BN$K$O(B
$B!!!!!!!!(B\usepackage[remakefalse,PDF]{emathPs}
$B!!!!$H$7$?>l9g!$(B
$B!!!!FCDj$N(B pszahyou*$B4D6-$K(B [remake,eps] $B%*%W%7%g%s$r$D$1$k$H(B
$B!!!!Ev3:(B pszahyou(*)$B4D6-$K$D$$$F$N$_(B
$B!!!!!!!!(Beps $B%U%!%$%k$O99?7$5$l!$(B
$B!!!!!!!!(Bpdf $B$G$O$J$/(B eps $B$,FI$_9~$^$l$^$9!#(B
$B!!!!$=$N$"$H$G(B remake,eps $B%*%W%7%g%s$r(B remake,pdf $B%*%W%7%g%s$KJQ99$7$F(B
$B!!!!%?%$%W%;%C%H$9$l$P!$(Bpdf $B$,:n@.!J99?7!K$5$l!$(B
$B!!!!(Bpdf $B$,FI$_9~$^$l$k$3$H$K$J$j$^$9!#(B
$B!!!!!!$5$i$K!$(Bremake,pdf $B%*%W%7%g%s$b>C$;$P!$A4BN$N%*%W%7%g%s(B
$B!!!!!!!!(Bremakefalse,PDF
$B!!!!$,M-8z$H$J$j$^$9!#(B

$BCm(B6. dvipdfmx.def [1999/02/16 v3.0i Driver-dependant file (DPC,SPQR)]
$B!!!!$K$O%P%0$,$"$j!$?^$,H>3Q6uGrJ,$@$11&$K$:$l$^$9!#(B
$B!!!!(Bdvipdfmx.def $B$r(B write18 $B$G8!:w$9$k$H(B
$B!!!!(B    \immediate\write18{extractbb \Gin@base\Gin@ext}
$B!!!!$H$$$&9T$,8+$D$+$j$^$9$,!$$=$N9TKv$K(B % 1$BJ8;z$rIU2C$7(B
$B!!!!(B    \immediate\write18{extractbb \Gin@base\Gin@ext}%
$B!!!!$H=$@5$9$k$3$H$G!$H>3Q6uGr$N:.F~$r2sHr$9$k$3$H$,=PMh$^$9!#(B

$BCm(B7. xbb $B%U%!%$%k$O<+F0E*$K:n@.$5$l$^$9!J(Bdvipdfmx.def $B$N5!G=!K!#(B
$B!!!!!J$"$i$+$8$aMQ0U$9$kI,MW$O$"$j$^$;$s!#!K(B

$BCm(B8. pdf $B%*%W%7%g%s$O!$(Bperl $B$H$NO"7H5!G=$K0MB8$7$^$9$+$i!$(B
$B!!!!(Bplatex $B$KBP$9$k(B -shell-escape $B%*%W%7%g%s$NIU2C$,I,?\$G$9!#(B

$BCm(B9. $B:#2s$N2~D{;EMM$O;CDjE*$J$b$N$G$"$j!$(B
$B!!!!<!$N=$@5%Q%C%/$^$G$K$OBg$-$JJQ99$,$J$5$l$k2DG=@-$,$"$j$^$9$+$i!$(B
$B!!!!$4>5CN$*$-4j$$$^$9!#(B

$B:#2s$N(B emathPs.sty $B$N2~D{$OB>$N%9%?%$%k%U%!%$%k$K$b1F6A$7$^$9$N$G(B
    emath.sty v2.27
    emathPl.sty v0.23
    emathPp.sty v0.87
    emathPh.sty v3.84
    emathPk.sty v1.20
$B$bF1:-$7$F$"$j$^$9!#(B
$B$^$?!$%5%s%W%k%j%9%H(B
    newPs181.tex
$B$bF1:-$7$^$9!#(B

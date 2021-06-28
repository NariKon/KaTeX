# $\KaTeX$
\cancel{5}	​	
\overbrace{a+b+c}^{\text{note}}
\bcancel{5}	
\underbrace{a+b+c}_{\text{note}}
\xcancel{ABC}	
\sout{abc}	
\boxed{\pi=\frac c d}
  $a_{\angl n}	
  a_\angln
\phase{-78^\circ}
\tag{hi} x+y^{2x}
\tag*{hi} x+y^{2x}
Vertical Layout

\stackrel{!}{=}	
\atop b
\overset{!}{=}	
a\raisebox{0.25em}{$b$}c
\underset{!}{=}	
a+\left(\vcenter{\hbox{$\frac{\frac a b}c$}}\right)
\sum_{\substack{0<i<m\\0<j<n}}

Overlap and Spacing

 {=}\mathllap{/\,}	
 \left(x^{\smash{2}}\right)
\mathrlap{\,/}{=}	
\sqrt{\smash[b]{y}}
\sum_{\mathclap{1\le i\le j\le n}} x_{ij}

Spacing

Function	Produces	Function	Produces
\,	³∕₁₈ em space	\kern{distance}	space, width = distance
\thinspace	³∕₁₈ em space	\mkern{distance}	space, width = distance
\>	⁴∕₁₈ em space	\mskip{distance}	space, width = distance
\:	⁴∕₁₈ em space	\hskip{distance}	space, width = distance
\medspace	⁴∕₁₈ em space	\hspace{distance}	space, width = distance
\;	⁵∕₁₈ em space	\hspace*{distance}	space, width = distance
\thickspace	⁵∕₁₈ em space	\phantom{content}	space the width and height of content
\enspace	½ em space	\hphantom{content}	space the width of content
\quad	1 em space	\vphantom{content}	a strut the height of content
\qquad	2 em space	\!	– ³∕₁₈ em space
~	non-breaking space	\negthinspace	– ³∕₁₈ em space
\<space>	space	\negmedspace	– ⁴∕₁₈ em space
\nobreakspace	non-breaking space	\negthickspace	– ⁵∕₁₈ em space
\space	space	\mathstrut	\vphantom{(}
Notes:

distance will accept any of the KaTeX units.

\kern, \mkern, \mskip, and \hspace accept unbraced distances, as in: \kern1em.

\mkern and \mskip will not work in text mode and both will write a console warning for any unit except mu.

 	\def\foo{x^2} \foo + \foo
 	\gdef\bar#1{#1^2} \bar{y} + \bar{y}
\xdef\macroname#1#2…{definition to be expanded}
\futurelet\foo\bar x
\newcommand\macroname[numargs]{defiition}

\char \mathchoice \TextOrMath \@ifstar \@ifnextchar \@firstoftwo \@secondoftwo \relax \expandafter \noexpand

@ is a valid character for commands, as if \makeatletter were in effect.

Operators


Fractions and Binomials

​	
\frac{a}{b}	
​	
\tfrac{a}{b}	
a+1
​	
 \genfrac ( ] {2pt}{1}a{a+1}
​	
  {a \over b}	
​	
  \dfrac{a}{b}	
b+1
​	
  {a \above{2pt} b+1}
a/b a/b		
1+ 
​	
​	
  \cfrac{a}{1 + \cfrac{1}{b}}
​	
 \binom{n}{k}	
​	
 \dbinom{n}{k}	
​	
 } {n\brace k}
​	
 ) {n \choose k}	
​	
 \tbinom{n}{k}	
​	
 ] {n\brack k}
Math Operators

arcsin
arcsin \arcsin	
cosec
cosec \cosec	
deg
deg \deg	
sec
sec \sec
arccos
arccos \arccos	
cosh
cosh \cosh	
dim
dim \dim	
sin
sin \sin
arctan
arctan \arctan	
cot
cot \cot	
exp
exp \exp	
sinh
sinh \sinh
arctg
arctg \arctg	
cotg
cotg \cotg	
hom
hom \hom	
sh
sh \sh
arcctg
arcctg \arcctg	
coth
coth \coth	
ker
ker \ker	
tan
tan \tan
arg
arg \arg	
csc
csc \csc	
lg
lg \lg	
tanh
tanh \tanh
ch
ch \ch	
ctg
ctg \ctg	
ln
ln \ln	
tg
tg \tg
cos
cos \cos	
cth
cth \cth	
log
log \log	
th
th \th
f \operatorname{f}			
arg max
argmax \argmax	
inj lim
injlim \injlim	
min
min \min	
lim
​	
  \varinjlim
arg min
argmin \argmin	
lim
lim \lim	
plim \plim	
lim
​	
  \varliminf
det
det \det	
lim inf
liminf \liminf	
Pr
Pr \Pr	
lim
  \varlimsup
gcd
gcd \gcd	
lim sup
limsup \limsup	
proj lim
projlim \projlim	
lim
​	
  \varprojlim
inf
inf \inf	
max
max \max	
sup
sup \sup	
f \operatorname*{f}	
f \operatornamewithlimits{f}		
Functions in the bottom six rows of this table can take \limits.

\sqrt

​	
  \sqrt{x}
​	
  \sqrt[3]{x}

Relations

  \stackrel{!}{=}

= =	
≑ \doteqdot	
⪅ \lessapprox	
⌣ \smile
< <	
≖ \eqcirc	
⋚ \lesseqgtr	
⊏ \sqsubset
> >	
−: \eqcolon or
\minuscolon	
⪋ \lesseqqgtr	
⊑ \sqsubseteq
: :	
−:: \Eqcolon or
\minuscoloncolon	
≶ \lessgtr	
⊐ \sqsupset
≈ \approx	
=: \eqqcolon or
\equalscolon	
≲ \lesssim	
⊒ \sqsupseteq
≈: \approxcolon	
=:: \Eqqcolon or
\equalscoloncolon	
≪ \ll	
⋐ \Subset
≈:: \approxcoloncolon	
≂ \eqsim	
⋘ \lll	
⊂ \subset or \sub
≊ \approxeq	
⪖ \eqslantgtr	
⋘ \llless	
⊆ \subseteq or \sube
≍ \asymp	
⪕ \eqslantless	
< \lt	
⫅ \subseteqq
∍ \backepsilon	
≡ \equiv	
∣ \mid	
≻ \succ
∽ \backsim	
≒ \fallingdotseq	
⊨ \models	
⪸ \succapprox
⋍ \backsimeq	
⌢ \frown	
⊸ \multimap	
≽ \succcurlyeq
≬ \between	
≥ \ge	
⊶ \origof	
⪰ \succeq
⋈ \bowtie	
≥ \geq	
∋ \owns	
≿ \succsim
≏ \bumpeq	
≧ \geqq	
∥ \parallel	
⋑ \Supset
≎ \Bumpeq	
⩾ \geqslant	
⊥ \perp	
⊃ \supset
≗ \circeq	
≫ \gg	
⋔ \pitchfork	
⊇ \supseteq or \supe
:≈ \colonapprox	
⋙ \ggg	
≺ \prec	
⫆ \supseteqq
::≈ \Colonapprox or
\coloncolonapprox	
⋙ \gggtr	
⪷ \precapprox	
≈ \thickapprox
:− \coloneq or
\colonminus	
> \gt	
≼ \preccurlyeq	
∼ \thicksim
::− \Coloneq or
\coloncolonminus	
⪆ \gtrapprox	
⪯ \preceq	
⊴ \trianglelefteq
:= \coloneqq or
\colonequals	
⋛ \gtreqless	
≾ \precsim	
≜ \triangleq
::= \Coloneqq or
\coloncolonequals	
⪌ \gtreqqless	
∝ \propto	
⊵ \trianglerighteq
:∼ \colonsim	
≷ \gtrless	
≓ \risingdotseq	
∝ \varpropto
::∼ \Colonsim or
\coloncolonsim	
≳ \gtrsim	
∣ \shortmid	
△ \vartriangle
≅ \cong	
⊷ \imageof	
∥ \shortparallel	
⊲ \vartriangleleft
⋞ \curlyeqprec	
∈ \in or \isin	
∼ \sim	
⊳ \vartriangleright
⋟ \curlyeqsucc	
⋈ \Join	
∼: \simcolon	
: \vcentcolon or
\ratio
⊣ \dashv	
≤ \le	
∼:: \simcoloncolon	
⊢ \vdash
:: \dblcolon or
\coloncolon	
≤ \leq	
≃ \simeq	
⊨ \vDash
≐ \doteq	
≦ \leqq	
⌢ \smallfrown	
⊩ \Vdash
≑ \Doteq	
⩽ \leqslant	
⌣ \smallsmile	
⊪ \Vvdash

Negated Relations

≠
= \not =

⪊ \gnapprox	
 \ngeqslant	
⊈ \nsubseteq	
⪵ \precneqq
⪈ \gneq	
≯ \ngtr	
 \nsubseteqq	
⋨ \precnsim
≩ \gneqq	
≰ \nleq	
⊁ \nsucc	
⊊ \subsetneq
⋧ \gnsim	
 \nleqq	
⋡ \nsucceq	
⫋ \subsetneqq
 \gvertneqq	
 \nleqslant	
⊉ \nsupseteq	
⪺ \succnapprox
⪉ \lnapprox	
≮ \nless	
 \nsupseteqq	
⪶ \succneqq
⪇ \lneq	
∤ \nmid	
⋪ \ntriangleleft	
⋩ \succnsim
≨ \lneqq	
 \notin	
⋬ \ntrianglelefteq	
⊋ \supsetneq
⋦ \lnsim	
∋ \notni	
⋫ \ntriangleright	
⫌ \supsetneqq
 \lvertneqq	
∦ \nparallel	
⋭ \ntrianglerighteq	
 \varsubsetneq
≆ \ncong	
⊀ \nprec	
⊬ \nvdash	
 \varsubsetneqq
= \ne	
⋠ \npreceq	
⊭ \nvDash	
 \varsupsetneq
= \neq	
 \nshortmid	
⊯ \nVDash	
 \varsupsetneqq
≱ \ngeq	
 \nshortparallel	
⊮ \nVdash
 \ngeqq	
≁ \nsim	
⪹ \precnapprox

Arrows

↺ \circlearrowleft	
↼ \leftharpoonup	
⇒ \rArr
↻ \circlearrowright	
⇇ \leftleftarrows	
→ \rarr
↶ \curvearrowleft	
↔ \leftrightarrow	
↾ \restriction
↷ \curvearrowright	
⇔ \Leftrightarrow	
→ \rightarrow
⇓ \Darr	
⇆ \leftrightarrows	
⇒ \Rightarrow
⇓ \dArr	
⇋ \leftrightharpoons	
↣ \rightarrowtail
↓ \darr	
↭ \leftrightsquigarrow	
⇁ \rightharpoondown
⇠ \dashleftarrow	
⇚ \Lleftarrow	
⇀ \rightharpoonup
⇢ \dashrightarrow	
⟵ \longleftarrow	
⇄ \rightleftarrows
↓ \downarrow	
⟸ \Longleftarrow	
⇌ \rightleftharpoons
⇓ \Downarrow	
⟷ \longleftrightarrow	
⇉ \rightrightarrows
⇊ \downdownarrows	
⟺ \Longleftrightarrow	
⇝ \rightsquigarrow
⇃ \downharpoonleft	
⟼ \longmapsto	
⇛ \Rrightarrow
⇂ \downharpoonright	
⟶ \longrightarrow	
↱ \Rsh
← \gets	
⟹ \Longrightarrow	
↘ \searrow
⇔ \Harr	
↫ \looparrowleft	
↙ \swarrow
⇔ \hArr	
↬ \looparrowright	
→ \to
↔ \harr	
⇔ \Lrarr	
↞ \twoheadleftarrow
↩ \hookleftarrow	
⇔ \lrArr	
↠ \twoheadrightarrow
↪ \hookrightarrow	
↔ \lrarr	
⇑ \Uarr
  
  
⟺ \iff	
↰ \Lsh	
⇑ \uArr
  
  
⟸ \impliedby	
↦ \mapsto	
↑ \uarr
  
  
⟹ \implies	
↗ \nearrow	
↑ \uparrow
⇐ \Larr	
↚ \nleftarrow	
⇑ \Uparrow
⇐ \lArr	
⇍ \nLeftarrow	
↕ \updownarrow
← \larr	
↮ \nleftrightarrow	
⇕ \Updownarrow
⇝ \leadsto	
⇎ \nLeftrightarrow	
↿ \upharpoonleft
← \leftarrow	
↛ \nrightarrow	
↾ \upharpoonright
⇐ \Leftarrow	
⇏ \nRightarrow	
⇈ \upuparrows
↢ \leftarrowtail	
↖ \nwarrow
↽ \leftharpoondown	
⇒ \Rarr


Extensible Arrows

abc
​	
  \xleftarrow{abc}	
over
under
​	
  \xrightarrow[under]{over}
abc
​	
  \xLeftarrow{abc}	
abc
​	
  \xRightarrow{abc}
abc
​	
  \xleftrightarrow{abc}	
abc
​	
  \xLeftrightarrow{abc}
abc
​	
  \xhookleftarrow{abc}	
abc
​	
  \xhookrightarrow{abc}
abc
  \xtwoheadleftarrow{abc}	
abc
  \xtwoheadrightarrow{abc}
abc
​	
  \xleftharpoonup{abc}	
abc
​	
  \xrightharpoonup{abc}
abc
​	
  \xleftharpoondown{abc}	
abc
​	
  \xrightharpoondown{abc}
abc
​	
  \xleftrightharpoons{abc}	
abc
​	
  \xrightleftharpoons{abc}
abc
​	
  \xtofrom{abc}	
abc
​	
  \xmapsto{abc}
abc
  \xlongequal{abc}
Extensible arrows all can take an optional argument in the same manner
as \xrightarrow[under]{over}.

Special Notation

Bra-ket Notation

⟨ϕ∣ \bra{\phi}	
∣ψ⟩ \ket{\psi}	
⟨ϕ∣ψ⟩ \braket{\phi\vert\psi}
⟨ϕ∣ \Bra{\phi}	
∣ψ⟩ \Ket{\psi}	
Style, Color, Size, and Font

Class Assignment

\mathbin \mathclose \mathinner \mathop
\mathopen \mathord \mathpunct \mathrel

Color

F=ma \color{blue} F=ma

Note that \color acts like a switch. Other color functions expect the content to be a function argument:

F=ma \textcolor{blue}{F=ma}
F=ma \textcolor{#228B22}{F=ma}
F=ma
​	
  \colorbox{aqua}{$F=ma$}
F=ma
​	
  \fcolorbox{red}{aqua}{$F=ma$}

Note that, as in LaTeX, \colorbox & \fcolorbox renders its third argument as text, so you may want to switch back to math mode with $ as in the examples above.

For color definition, KaTeX color functions will accept the standard HTML predefined color names. They will also accept an RGB argument in CSS hexa­decimal style. The "#" is optional before a six-digit specification.

Font

Ab0 \mathrm{Ab0}	
Ab0 \mathbf{Ab0}	
Ab0 \mathit{Ab0}
Ab0 \mathnormal{Ab0}	
Ab0
Ab0 \textbf{Ab0}	
Ab0
Ab0 \textit{Ab0}
Ab0
Ab0 \textrm{Ab0}	
Ab0 \bf Ab0	
Ab0 \it Ab0
Ab0 \rm Ab0	
Ab0 \bold{Ab0}	
Ab0
Ab0 \textup{Ab0}
Ab0
Ab0 \textnormal{Ab0}	
Ab0 \boldsymbol{Ab}	
AB \Bbb{AB}
Ab0
Ab0 \text{Ab0}	
Ab0 \bm{Ab0}	
AB \mathbb{AB}
Ab0 \mathsf{Ab0}	
Ab0
Ab0 \textmd{Ab0}	
Ab0 \frak{Ab0}
Ab0
Ab0 \textsf{Ab0}	
Ab0 \mathtt{Ab0}	
Ab0 \mathfrak{Ab0}
Ab0 \sf Ab0	
Ab0
Ab0 \texttt{Ab0}	
AB0 \mathcal{AB0}
Ab0 \tt Ab0	
AB0 \cal AB0
AB \mathscr{AB}
One can stack font family, font weight, and font shape by using the \textXX versions of the font functions. So \textsf{\textbf{H}} will produce 
H. The other versions do not stack, e.g., \mathsf{\mathbf{H}} will produce 
H.

In cases where KaTeX fonts do not have a bold glyph, \pmb can simulate one. For example, \pmb{\mu} renders as : 

Size

AB \Huge AB	
AB \normalsize AB
AB \huge AB	
AB \small AB
AB \LARGE AB	
AB \footnotesize AB
AB \Large AB	
AB \scriptsize AB
AB \large AB	
AB \tiny AB
Style

i=1
​	
  \displaystyle\sum_{i=1}^n
i=1
​	
  \textstyle\sum_{i=1}^n
x \scriptstyle x         (The size of a first sub/superscript)
x \scriptscriptstyle x (The size of subsequent sub/superscripts)
lim
lim
​	
  \lim\limits_x
lim
lim 
​	
  \lim\nolimits_x
x^2
x^2 \verb!x^2!
\text{…} will accept nested $…$ fragments and render them in math mode.

Symbols and Punctuation

% comment	
… \dots	
KaTeX
 T 
​	
 X \KaTeX
% \%	
⋯ \cdots	
LaTeX
 T 
​	
 X \LaTeX
# \#	
⋱ \ddots	
TeX
​	
 X \TeX
& \&	
… \ldots	
∇ \nabla
_ \_	
⋮ \vdots	
∞ \infty
_ \text{\textunderscore}	
⋯ \dotsb	
∞ \infin
– \text{--}	
… \dotsc	
✓ \checkmark
– \text{\textendash}	
 ⁣
⋯ \dotsi	
† \dag
— \text{---}	
⋯ \dotsm	
† \dagger
— \text{\textemdash}	
… \dotso	
† \text{\textdagger}
~ \text{\textasciitilde}	
⋅ \sdot	
‡ \ddag
^ \text{\textasciicircum}	
… \mathellipsis	
‡ \ddagger
‘ `	
… \text{\textellipsis}	
‡ \text{\textdaggerdbl}
‘ text{\textquoteleft}	
□ \Box	
‡ \Dagger
‘ \lq	
□ \square	
∠ \angle
’ \text{\textquoteright}	
■ \blacksquare	
∡ \measuredangle
  \rq	
△ \triangle	
∢ \sphericalangle
“ \text{\textquotedblleft}	
▽ \triangledown	
⊤ \top
" "	
◃ \triangleleft	
⊥ \bot
” \text{\textquotedblright}	
▹ \triangleright	
$ \$
 ⁣
: \colon	
▽ \bigtriangledown	
$ \text{\textdollar}
‵ \backprime	
△ \bigtriangleup	
£ \pounds
′ \prime	
▲ \blacktriangle	
£ \mathsterling
< \text{\textless}	
▼ \blacktriangledown	
£ \text{\textsterling}
> \text{\textgreater}	
◀ \blacktriangleleft	
¥ \yen
| \text{\textbar}	
▶ \blacktriangleright	
√ \surd
∥ \text{\textbardbl}	
⋄ \diamond	
° \degree
{ \text{\textbraceleft}	
◊ \Diamond	
° \text{\textdegree}
} \text{\textbraceright}	
◊ \lozenge	
℧ \mho
\ \text{\textbackslash}	
⧫ \blacklozenge	
╲ \diagdown
¶ \text{\P} or \P	
⋆ \star	
╱ \diagup
§ \text{\S} or \S	
★ \bigstar	
♭ \flat
§ \text{\sect}	
♣ \clubsuit	
♮ \natural
  \copyright	
♣ \clubs	
♯ \sharp
® \circledR	
♢ \diamondsuit	
♡ \heartsuit
  \text{\textregistered}	
♢ \diamonds	
♡ \hearts
Ⓢ \circledS	
♠ \spadesuit	
♠ \spades
  \text{\textcircled a}	
✠ \maltese	
− \minuso
# cs39003-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [CS39003 Assignment 3 Solved](https://www.ankitcodinghub.com/product/compilers-laboratory-cs39003-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;113930&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS39003 Assignment 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
1 Preamble – tinyC

This assignment follows the lexical specification of C language from the International Standard ISO/IEC 9899:1999 (E). To keep the assignment within our required scope, we have chosen a subset of the specification as given below. We shall refer to this language as tinyC and subsequently (in a later assignment) specify its grammar from the Phase Structure Grammar given in the C Standard.

The lexical specification quoted here is written using a precise yet compact notation typically used for writing language specifications. We first outline the notation and then present the Lexical Grammar that we shall work with.

2 Notation

In the syntax notation used here, syntactic categories (non-terminals) are indicated by italic type, and literal words and character set members (terminals) by bold type. A colon (:) following a non-terminal introduces its definition. Alternative definitions are listed on separate lines, except when prefaced by the words ”one of”. An optional symbol is indicated by the subscript ”opt”, so that the following indicates an optional expression enclosed in braces.

{ expressionopt }

3 Lexical Grammar of tinyC

1. Lexical Elements token: keyword

identifier constant string-literal punctuator

2. Keywords keyword: one of

auto enum restrict unsigned

break extern return void

case float short volatile

char for signed while

const goto sizeof Bool

continue if static Complex

default inline struct Imaginary

do int switch

double long typedef

else register union

3. Identifiers identifier:

identifier-nondigit identifier identifier-nondigit identifier digit identifier-nondigit: one of

a b c d e f g h i j k l m

n o p q r s t u v w x y z

A B C D E F G H I J K L M

N O P Q R digit: one of S T U V W X Y Z

0 1 2 3 4 5

4. Constants constant: integer-constant floating-constant enumeration-constant character-constant integer-constant: nonzero-digit integer-constant digit nonzero-digit: one of 6 7 8 9

1 2 3 4 5 6 floating-constant: 7 8 9

fractional-constant exponent-partopt digit-sequence exponent-part fractional-constant:

digit-sequenceopt . digit-sequence digit-sequence . exponent-part:

e signopt digit-sequence

E signopt digit-sequence sign: one of

+ –

digit-sequence:

digit digit-sequence digit enumeration-constant: identifier character-constant:

‘ c-char-sequence ‘ c-char-sequence:

c-char c-char-sequence c-char c-char:

any member of the source character set except

the single-quote ‘, backslash , or new-line character escape-sequence

escape-sequence: one of

‘ ” ? \

a

5. String literals string-literal:

” s-char-sequenceopt ” s-char-sequence:

s-char s-char-sequence s-char

s-char:

any member of the source character set except the double-quote ”, backslash , or new-line character

escape-sequence

6. Punctuators punctuator: one of

[ ] ( ) { } . -&gt;

++ — &amp; * + – ~ ! / % &lt;&lt; &gt;&gt; &lt; &gt; &lt;= &gt;= == != ^ | &amp;&amp; || ? : ; …

= *= /= %= += -= &lt;&lt;= &gt;&gt;= &amp;= ^= |=

, #

7. Comments

(a) Multi-line Comment

Except within a character constant, a string literal, or a comment, the characters /* introduce a comment. The contents of such a comment are examined only to identify multibyte characters and to find the characters */ that terminate it. Thus, /* … */ comments do not nest.

(b) Single-line Comment

Except within a character constant, a string literal, or a comment, the characters // introduce a comment that includes all multibyte characters up to, but not including, the next new-line character. The contents of such a comment are examined only to identify multibyte characters and to find the terminating new-line character.

4 The Assignment

1. Write a flex specification for the language of tinyC using the above lexical grammar. Name of your file should be ass3 roll.l. The ass3 roll.l should not contain the function main().

2. Write your main() (in a separate file ass3 roll.c) to test your lexer.

3. Prepare a Makefile to compile the specifications and generate the lexer.

4. Prepare a test input file ass3 roll test.c that will test all the lexical rules that you have coded.

5. Prepare a tar-archive with the name ass3 roll.tar containing all the above files and upload to Moodle.

5 Credits

1. Flex Specifications: 60

2. Main function and Makefile: 20 [15+5]

3. Test file: 20

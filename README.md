A REPORT FOR WEB (TERM 1)

KRITAGYA JUNG ADHIKARI
(16418536)




















CONTENTS
1)	WIREFRAMINGS
2)	WORK DESCRIPTIONS
I) INDEX.HTML AND INDEX.CSS
II) PORTFOLIO.HTML AND STYLEB.CSS
III) CV.HTML AND STYLEA.CSS
IV) BIO.HTML AND BIO.CSS
V) CONTACT.HTML AND CONTACT.CSS
     3) CODES
     4) TIME DETAILS AND OBSTACLES
     5) Limitations
     6) CONCLUSION


















WIREFRAMINGS


 

FIG 1.1 WIREFRAME FOR CV



 

FIG 1.2 WIREFRAME FOR HOME PAGE




 


FIG 1.3 WIREFRAME FOR PORTFOLIO




 


FIG 1.4 WIREFRAME FOR CONTACT PAGE



 

FIG 1.5 WIREFRAME FOR BIO PAGE





WORK-DESCRIPTION

CODING WITH CSS AND HTML WAS FUN AND CHALLENGING AT A SAME TIME BUT I MANAGED MY WAY WITH A HELP OF SOME WEB TUTORIAL ONLINE, NILE AND WORKSHOPS ATTENDED.
AT FIRST, I STARTED CODING WITH PORTFOLIO PAGE WHICH I THOUGHT TO BE A HOME PAGE THAT LINKS TO EVERY OTHER PAGES. I WAS UNAWARE THAT INDEX PAGE WAS TO BE DIFFERENTLY BUILT AND THIS PAGE WAS PRIMARY OF ALL. LATER, I FOUND THAT INDEX AND PORTFOLIO PAGE WERE DIFFERENT AND I CHANGED THE NAME OF INDEX.HTML TO PORTFOLIO.HTML. REMAINING THREE PAGES TOOK ME SOME TIME TO LEARN AND CODE AS THEY WERE NEW TO ME.

NOW, LET US BEGIN WITH A DESCRIPTION OF EACH INDIVIDUAL PAGES RELATIVE TO CONTENTS.













INDEX.HTML AND INDEX.CSS

AT FIRST, I CREATED A CONSOLE FOR INDEX.HTML PAGE WITH ATOM TEXT EDITOR AND USED INTERNET EXPLORER TO CHECK MY PROGRESS. INDEX.CSS WAS LINKED WITH LINK HREF. FOR THIS PAGE, I THOUGHT IT SHOULD BE SIMPLE AND FUNCTIONAL AT A SAME TIME. THANKS TO GOOGLE API FONTS WHICH ALLOWED USER TO COPY SOME LINK DESIGN THE FONTS IN DIFFERENT STYLES. FOR THIS PAGE I USED CABIN SKETCH AND LOBSTER FONTS FOR HEADING AND CONTENTS CLASS RESPECTIVELY. 
I USED ONE OF MY IMAGE AS A DISPLAY PHOTO FOR THIS PAGE. SOME FEATURES LIKE HEIGHT AND WIDTH WAS NOT SUPPORTED IN CSS AND I HAD TO DEFINE IT IN HTML. LINKS FOR CERTAIN PAGES WERE PROVIDED IN THIS CONSOLE.
FOR BODY BACKGROUND I REFERENCED A COLOR FOR COLOR-HEX.COM. CERTAIN MARGIN AND PADDING PROPERTIES WERE FEEBLE IN A PAGE AND FIXED POSITION WAS TO BE DEFINED TO TARGET IT�S PLACE AT A FIX POINT. IN THIS PAGE, I USED SOME ANIMATION PROPERTIES SUCH AS ROTATE AND HOVER. ROTATE PROPERTY MOTIONS A TEXT TO CERTAIN DEGREE AS SPECIFIED BY USER AND HOVER PROPERTY ALLOWS TO TARGET SOME ELEMENT. AS A TARGET, I USED SCALING SUB-PROPERTY WHICH ALLOWS TEXT TO ZOOM IN AND ZOOM OUT. 
ALTHOUGH FLOAT PROPERTY IS CONSIDERED TO BE OLD, I DEFINED THIS PROPERTY IN A PAGE AS IT IS MUCH MORE CONVENIENT AS FLEX. 









PORTFOLIO.HTML AND STYLEB.CSS
AT FIRST, I CREATED A CONSOLE FOR PORTFOLIO.HTML PAGE WITH ATOM TEXT EDITOR AND USED INTERNET EXPLORER TO CHECK MY PROGRESS. STYLEB.CSS WAS LINKED WITH LINK HREF.

FOR THIS PAGE, I USED SOME PROPERTIES LIKE DIV AND A HREF TAGS TO DEFINE A PARAGRAPH AND LINK PAGE RESPECTIVELY. HEADER CLASS WAS DEFINED AND SOME TEXTS WERE CAGED IN IT. FOR NAVIGATION MENU, I USED HOVER AND MARKED DELAY FOR IT. WHEN A USER MOVES CURSOR TO A CONTENTS IN NAVIGATION, A TEXT IS HIGHLIGHTED WITH A BACKGROUND COLOR AFTER DEFINED TIME. USING CSS, I DEFINED A COLOR FOR HEADER TEXTS AND ALIGNED TEXT TO A CENTRE. IN THE CONTAINER PART OF A BODY, I USED ONE OF MY PHOTO AS A DISPLAY AND KEPT A PHOTO OF MINE. SOME TEXTS WERE KEPT ABOVE THE IMAGE USING ABSOLUTE VALUE FOR POSITION ATTRIBUTE. THIS VALUE ALLOWS TEXTS TO RUN OVER IMAGE. SOME TEXTS SUCH AS �DESIGNER� AND �CREATION� WERE GIVEN FIXED VALUES SUCH THAT IT CAN SCROLL AS THE USER MOVES DOWN THE PAGE.

AT A FOOTER PART, I USED SOME OF MY SNAPS AND DEFINED ITS SIZE IN HTML AS IT WAS NOT SUPPORTED BY CSS. FOR THE IMAGE I USED LINK TAGS AND HOVER PROPERTY WITH CERTAIN SCALING. WHEN WE CLICK THE IMAGE, IT OPENS AND I DEFINED THE TEXTS TO GO BACK TO A PORTFOLIO PAGE AGAIN. ABOVE IMAGE I CAGED SOME TEXTS USING ABSOLUTE PROPERTY AND DEFINED AN OPACITY FOR TEXT BACKGROUND. OPACITY PROPERTY ALLOWS TO VISUALIZE THE ELEMENTS IN CERTAIN CONTRASTS.








CV.HTML AND STYLEA.CSS

AT FIRST, I CREATED A CONSOLE FOR CV.HTML PAGE WITH ATOM TEXT EDITOR AND USED INTERNET EXPLORER TO CHECK MY PROGRESS. STYLES.CSS WAS LINKED WITH LINK HREF.

IN THIS PAGE, GOOGLE API FONT (LOBSTER) WAS USED TO DECORATE SOME TEXTS. TO CREATE A TABLE LIKE STRUCTURE, BORDER WAS DEFINED AND TEXTS WERE ENCLOSED IN IT. FOR SOME AREA SUCH AS GMAIL, BLACK BACKGROUND COLOR WAS USED AND PADDING CUM MARGIN PROPERTY WERE DEFINED TO FIX IT�S SIZE. IN THE NAVIGATION PANAL, HOVER WAS USED WITH CERTAIN DELAY AND BACKGROUND COLOR SUCH THAT TEXTS WOULD ZOOM AND HIGHLIGHT THEMSELVES WITH MAROON BACKGROUND IN 0.5S.















BIO.HTML AND BIO.CSS

BIO.HTML PAGE WAS CREATED WITH ATOM TEXT EDITOR AND LINKED WITH BIO.CSS USING LINK HREF. IN THIS PAGE, PARAGRAPH ABD BREAK TAG WERE USED. PARAGRAPH TAG DEFINES A PARAGRAPH FOR TEXTS ENCLOSED IN IT AND BR TAG BREAKS A LINE. GOOGLE API FONTS SUCH AS LOBSTER AND GREAT VIBES WERE USED. 
FOR CREATING NAVIGATION PANAL, FLEX PROPERTY WAS USED. FLEX PROPERTY DEFINES AN ELEMENT TO FIX IN DIFFERENT SCREEN SIZES. ROW-REVERSE ATTRIBUTE WAS DEFINED; THIS ATTRIBUTE REVERSES THE TEXTS IN A ROW FROM RIGHT TO LEFT.


CERTAIN ANIMATION PROPERTY SUCH AS WEBKIT TRANSFORM WAS USED IN RELATION WITH ROTATION. THIS PROPERTY ROTATES TEXT TO CERTAIN DEGREE AS DEFINED.













CONTACT.HTML AND CONTACT.CSS

IN THIS PAGE, FORM PROPERTY WAS USED TO CREATE A FORM. AND CERTAIN SUB-ATTRIBUTE SUCH AS BUTTON WERE USED TO CREATE A SUBMIT BUTTON. SOME HELP WAS TAKEN FROM W3SCHOOLS TO CREATE A FORM. 

FLEX PROPERTY WAS DEFINED TO CREATE A NAVIGATION PANAL. SOME SCALING WAS DEFINED FOR HOVER SUCH THAT TEXTS WOULD POP OUT FROM ITS ACTUAL POSITION. GOOGLE API FONT �CABIN SKETCH� WAS USED TO DECORATE SOME TEXTS.

IN THE FOOTER PART, PADDING AND MARGIN PROPERTIES WERE DEFINED. PADDING PROPERTY DEFINES A DISTANCE OF TEXT FROM BORDER AND MARGIN PROPERTY DEFINES A SCALING FROM NEAREST ELEMENTS.

CODES
CODES FOR INDEX PAGE
<!--KRITAGYA JUNG ADHIKARI, 16418536-->
INDEX.HTML

<!DOCTYPE HTML>
<HTML>
  <HEAD>
    <META CHARSET="UTF-8"> <!--DEFINES ENCODING VALUES FOR A PARTICULAR PAGE-->
    <LINK HREF="INDEX.CSS" REL="STYLESHEET" TYPE="TEXT/CSS"> <!--PROVIDES A LINK TO A CSS DEFINED CONSOLE-->
    <TITLE>FRONT</TITLE>
  </HEAD>
  <BODY>
    <DIV CLASS="MYPHOTO"><IMG SRC="COUNT.JPEG" HEIGHT="128" WIDTH="176"></DIV>
    <DIV CLASS="MYNAME"><LINK HREF="HTTPS://FONTS.GOOGLEAPIS.COM/CSS?FAMILY=CABIN+SKETCH" REL="STYLESHEET"> ALPHAKRITAGYA </DIV> <!--FONT REFERENCED FROM GOOGLE API-->
    <DIV CLASS="START"> <LINK HREF="HTTPS://FONTS.GOOGLEAPIS.COM/CSS?FAMILY=CABIN+SKETCH" REL="STYLESHEET"> GET STARTED!! </DIV> <!--FONT REFERENCED FROM GOOGLE API-->
    <DIV CLASS="HEADER4"><LINK HREF="HTTPS://FONTS.GOOGLEAPIS.COM/CSS?FAMILY=LOBSTER" REL="STYLESHEET"> <!--CLASS AND LINE BREAK IS DEFINED AT A SAME TIME, FONT REFERENCED FROM GOOGLE API-->
      <LI><A HREF="PORTFOLIO.HTML"><DIV CLASS="BACK"> PORTFOLIO </DIV></A></LI> <!--LINKS A CURRENT PAGE TO THE SPECIFIED PAGE WITHIN TAGS-->
      <LI><A HREF="CV.HTML"><DIV CLASS="EXTRA"> CV </DIV></LI>
      <LI><A HREF="CONTACT.HTML"><DIV CLASS="CONTACT"> CONTACT </DIV></A></LI>
      <LI><A HREF="BIO.HTML"><DIV CLASS="MORE"> BIO </DIV></A></LI>
    </DIV>
  </BODY>
</HTML>

INDEX.CSS

BODY{
  BACKGROUND-COLOR: #002633; /* REFERENCED FROM COLOR-HEX */
}
.MYPHOTO{
  FONT-FAMILY: 'CABIN SKETCH', CURSIVE; /* GOOGLE API FONT */
  MARGIN-LEFT: 1290PX;
}
.MYNAME{
  FONT-FAMILY: 'CABIN SKETCH', CURSIVE; /* GOOGLE API FONT */
  FONT-SIZE: 28PX;
  COLOR:SEASHELL;
  FONT-WEIGHT: BOLD;
  MARGIN-TOP: -26PX;
  MARGIN-LEFT: 1100PX;
  TEXT-SHADOW: 8PX 8PX BLACK; /* DEFINES SHADOW OF A TEXT WITH A SPECIFIED HEIGHT AND WIDTH */
}
.START{
  FONT-SIZE: 52PX;
  COLOR: SEASHELL;
  FONT-FAMILY: 'CABIN SKETCH', CURSIVE; /* GOOGLE API FONT */
  POSITION: FIXED; /* DEFINES A TEXT IS EXACTLY FITTED AT A SAME POSITION WHATEVER THE ACTION IS TAKEN */
  MARGIN-LEFT: 522PX;
  MARGIN-TOP: 118PX;
 -WEBKIT-TRANSFORM: ROTATE(-12DEG); /* CSS ANIMATION PROPERTY, ROTATES A TEXT TO A CERTAIN DEGREE */
}
.HEADER4{
  FONT-FAMILY: LOBSTER , CURSIVE; /* GOOGLE API FONT */
  FONT-SIZE: 32PX;
  LIST-STYLE-TYPE: NONE;
}
.BACK{
  COLOR: #E1D4F6; /* DEFINES A COLOR TO A PARTICULAR TEXT, REFERENCED FROM COLOR-HEX.COM */
  FLOAT: LEFT;
  POSITION: FIXED;
  MARGIN-LEFT: 698PX;
  MARGIN-TOP: 236PX;
}
.BACK:HOVER{ /* IDENTIFY SOME ELEMENT WITH A SHORT INDICATION WHEN WE MOVE CURSOR TOWARDS IT */
  BACKGROUND-COLOR: BLACK;
  -WEBKIT-TRANSFORM: SCALE(1.4); /* ZOOM TEXT WITH A CERTAIN SCALES, CSS ANIMATION PROPERTY */
}
.EXTRA{
  COLOR: #7CFC00; /* DEFINES A COLOR TO A PARTICULAR TEXT I.E. LAWNGREEN, REFERENCED FROM COLOR-HEX.COM */
  FLOAT: LEFT;
  POSITION: FIXED;
  MARGIN-LEFT: 726PX;
  MARGIN-TOP: 318PX;
}
.EXTRA:HOVER{
  BACKGROUND-COLOR: BLACK;
  -WEBKIT-TRANSFORM: SCALE(1.4);
}
.CONTACT{
  COLOR: 	#B22222; /*DEFINES A FIREBRICK COLOR TO A TEXT, TAKEN FROM COLOR-HEX.COM */
  FLOAT: LEFT;
  POSITION: FIXED;
  MARGIN-LEFT: 702PX;
  MARGIN-TOP: 400PX;
}
.CONTACT:HOVER{
  BACKGROUND-COLOR: BLACK;
  -WEBKIT-TRANSFORM: SCALE(1.4);
}
.MORE{
  COLOR: #EE7600; /* A DARK ORANGE, REFERENCED FROM COLOR-HEX.CON */
  FLOAT: LEFT;
  MARGIN-LEFT: 730PX;
  MARGIN-TOP: 482PX;
  POSITION: FIXED;
}
.MORE:HOVER{
  BACKGROUND-COLOR: BLACK;
  -WEBKIT-TRANSFORM: SCALE(1.4);
}





CODES FOR PORTFOLIO.HTML
<!--KRITAGYA JUNG ADHIKARI, 16418536-->

<!DOCTYPE HTML>
<HTML>
  <HEAD>
    <META CHARSET="UTF-8"> <!--DEFINES ENCODING VALUES FOR A PARTICULAR PAGE-->
    <LINK HREF="STYLEB.CSS" REL="STYLESHEET" TYPE="TEXT/CSS"> <!--PROVIDES A LINK TO A CSS DEFINED CONSOLE-->
    <TITLE>FRONT</TITLE>
  </HEAD>
  <BODY>
    <DIV CLASS="HEADER"> <!--CLASS AND LINE BREAK IS DEFINED AT A SAME TIME-->
      <DIV CLASS="D"> ALPHA KRITAGYA </DIV>
      <DIV CLASS="B"> SURFIN' </DIV>
      <DIV CLASS="C"> BLACK </DIV>
    </DIV>
    <UL CLASS="I"> <!--DEFINES A CLASS AND A LIST AT A SAME TIME-->
      <DIV CLASS="J">
      <LI><A HREF="INDEX.HTML"><DIV CLASS="FRONT"> HOME </DIV></A></LI> <!--LINKS A CURRENT PAGE TO THE SPECIFIED PAGE WITHIN TAGS-->
      <LI><A HREF="CV.HTML"><DIV CLASS="EXTRA"> CV </DIV></LI>
      <LI><A HREF="CONTACT.HTML"><DIV CLASS="CONTACT"> CONTACT </DIV></A></LI>
      <LI><A HREF="BIO.HTML"><DIV CLASS="MORE"> BIO </DIV></A></LI>
      </DIV>
    </UL>
    <DIV CLASS="COUNT"><IMG SRC="COUNT.JPEG" HEIGHT="130" WIDTH="186"></DIV> <!--TO INSERT AN IMAGE COUNT CLASS IS DEFINED-->
    <DIV CLASS="TEXT"> MAKE TO CREATE </DIV>
    <DIV CLASS="TEXT1"> AM A <DIV CLASS="WEB">WEB</DIV><DIV CLASS="DESIGNER">DESIGNER</DIV><DIV CLASS="AND">AND THIS IS</DIV><DIV CLASS="MY">MY</DIV><DIV CLASS="CREATION">CREATION</DIV></DIV>
    <DIV CLASS="PORT IMAGE"><IMG SRC="D.JPG" HEIGHT="700" WIDTH="1510"></DIV> <!--TO DEFINE AN IMAGE D.JPG CLASS PORT IMAGE IS DEFINED-->
    <DIV CLASS="FOOTER">
      <DIV CLASS="SNAPS"> SNAPS </DIV>
      <DIV CLASS="CATCH"> CATCH ME </DIV>
      <DIV CLASS="IMAGE1"><A HREF="IMAGE1.HTML"><IMG SRC="IMAGE1.JPG" HEIGHT="182" WIDTH="302"></A></DIV> <!--CSS COULDN'T FETCH HEIGHT AND WIDTH PROPERTY, SO IT'S DEFINED WITHIN HTML-->
      <DIV CLASS="THUNDERS"> THUNDERS </DIV>
      <DIV CLASS="IMAGE2"><A HREF="IMAGE2.HTML"><IMG SRC="IMAGE2.JPG" HEIGHT="182" WIDTH="302"></A></DIV> <!--CSS COULDN'T FETCH HEIGHT AND WIDTH PROPERTY, SO IT'S DEFINED WITHIN HTML-->
      <DIV CLASS="DAY"> A NEW DAY </DIV>
      <DIV CLASS="IMAGE3"><A HREF="IMAGE3.HTML"><IMG SRC="IMAGE3.JPG" HEIGHT="182" WIDTH="302"></A></DIV> <!--CSS COULDN'T FETCH HEIGHT AND WIDTH PROPERTY, SO IT'S DEFINED WITHIN HTML-->
    </DIV>
  </BODY>
</HTML>

STYLEB.CSS (PORTFOLIO CSS)

@MEDIA ONLY SCREEN AND (MAX-WIDTH: 502PX) { /* DEFINES A RESPONSIVENESS OF A BODY */
BODY{
  BACKGROUND-COLOR: WHITE;
}
}
.HEADER{
 BACKGROUND-COLOR:  #000F19; /* DEFINES A BACKGROUND COLOR TO A PARTICULAR HEADER, REFERENCED FROM COLOR-HEX.COM */
 MARGIN-TOP: -8PX; /* DEFINES A TOP MARGIN OF A HEADER AND "-" INDICATES MORE CLOSEST TO A TOP AND VICE-VERSA */
 MARGIN-RIGHT: -8PX;
 MARGIN-LEFT: -8PX;
 TEXT-ALIGN: CENTER; /* POSITIONS A TEXT TO A CENTRE OF A HEADER */
 COLOR: #E1D4F6; /* DEFINES A COLOR OF A TEXT IN A PAGE, REFERENCED FROM COLOR-HEX.COM */
}
.D{
  FONT-SIZE: 46PX;
  FONT-FAMILY: ALGERIAN; /* DEFINES A FONT-TYPE OF A TEXT */
  FONT-WEIGHT: BOLD; /* BOLDENS A TEXT */
  PADDING-TOP: 46PX; /* DEFINES A DISTANCE BETWEEN TEXT AND A TOP ELEMENT */
}
.B{
  FONT-SIZE: 32PX; /* DEFINES A SIZE OF A TEXT */
  FONT-FAMILY: ALGERIAN;
  PADDING-TOP: 16PX;
  TEXT-DECORATION: UNDERLINE; /* UNDERLINES A TEXT */
}
.C{
  FONT-SIZE: 26PX;
  FONT-FAMILY: GEORGIA;
  PADDING-TOP: 2PX;
  PADDING-BOTTOM: 22PX;
}
.I{
  OVERFLOW: HIDDEN; /* HIDES A EXTRA BOUNDARIES FROM AN ELEMENT */
  LIST-STYLE-TYPE: NONE; /* DISCARDS BULLETS AND LISTS INDICATIVES */
  PADDING: 0;
  MARGIN: 0;
}
.J{
FONT-FAMILY: GEORGIA;
FONT-WEIGHT: BOLD;
FONT-SIZE: 18PX;
}
.FRONT{
  PADDING-BOTTOM: 10PX;
  PADDING-TOP: 10PX;
  COLOR: BLACK; /* CHANGE A COLOR OF A TEXT TO BLACK */
  FLOAT:LEFT; /* USED TO DEFINE A LINE IN A HORIZONTAL MANNER FOR LISTS AND NAVIGATIONS, ALSO TO CREATE A BOX */
  TEXT-DECORATION: NONE;
}
.FRONT:HOVER{ /* IDENTIFY SOME ELEMENT WITH A SHORT INDICATION WHEN WE MOVE CURSOR TOWARDS IT */
  BACKGROUND-COLOR: ORANGE;  /* DEFINE THE COLOR OF AN INDICATION WITH ORANGE BACKGROUND */
  TRANSITION-DELAY: 0.5S; /* CREATE A TIME INTERVAL FOR INDICATION WHEN A CURSOR IS MOVED TOWARDS TEXT */
}
.EXTRA{
  PADDING-LEFT: 16PX;
  PADDING-BOTTOM: 10PX;
  PADDING-TOP: 10PX;
  COLOR: BLACK;
  FLOAT:LEFT;
  TEXT-DECORATION: NONE;
}
.EXTRA:HOVER{
  BACKGROUND-COLOR: ORANGE;
  TRANSITION-DELAY: 0.5S;
  MARGIN-LEFT: 10PX; /* DEFINES A BOUNDARY OF A HOVER PROPERTY IN LEFT HAND SIDE */
  MARGIN-RIGHT: 2PX;
  PADDING-RIGHT: 16PX; /* DEFINES A DISTANCE BETWEEN A TEXT AND HOVER CREATED */
}
.CONTACT{
  PADDING-LEFT: 16PX;
  PADDING-BOTTOM: 10PX;
  PADDING-TOP: 10PX;
  COLOR: BLACK;
  FLOAT: LEFT;
  TEXT-DECORATION: NONE;
}
.CONTACT:HOVER{
  BACKGROUND-COLOR: ORANGE;
  TRANSITION-DELAY: 0.5S;
  MARGIN-LEFT: 14PX;
  MARGIN-RIGHT: 4PX;
  PADDING-RIGHT: 16PX;
}
.MORE{
  PADDING-LEFT: 16PX;
  PADDING-BOTTOM: 10PX;
  PADDING-TOP: 10PX;
  COLOR: BLACK;
  FLOAT: LEFT;
  TEXT-DECORATION: NONE;
}
.MORE:HOVER{
  BACKGROUND-COLOR: ORANGE;
  TRANSITION-DELAY: 0.5S;
  MARGIN-LEFT: 10PX;
  MARGIN-RIGHT: 2PX;
  PADDING-RIGHT: 14PX;
}
.PORT IMAGE{
  MIN-WIDTH: 100.5%; /* DEFINES A BOUNDARY WIDTH FOR AN IMAGE TO FIT IN A SCREEN */
  MIN-HEIGHT: 100%;  /* DEFINES A BOUNDARY HEIGHT FOR AN IMAGE TO FIT IN A SCREEN */
  DISPLAY: BLOCK; /*DEFINES A BOX PROPERTY*/
  MARGIN: AUTO;
  PADDING: 0;
}
.TEXT{
  POSITION: ABSOLUTE; /* POSITIONED RELATIVE TO BACKGROUND IMAGE, CAN RUN OVER IMAGE */
  TOP: 1;
  PADDING-TOP: 300PX;
  PADDING-LEFT: 600PX;
  FONT-SIZE: 38PX;
  FONT-FAMILY: ALGERIAN;
  FONT-WEIGHT: BOLD;
}
.COUNT{
  OVERFLOW: HIDDEN;
  BORDER-RADIUS: 8%;
  MARGIN-LEFT: -20PX;
  POSITION: ABSOLUTE;
  PADDING-LEFT: 684PX;
  PADDING-TOP: 150PX;
}
.TEXT1{
  PADDING-TOP: 400PX;
  PADDING-LEFT: 380PX;
  TOP:1;
  FONT-SIZE: 38PX;
  POSITION: ABSOLUTE;
  COLOR: #E1D4F6;
  FONT-FAMILY: GEORGIA;
  FONT-WEIGHT: BOLD;
}
.WEB{
  COLOR: BLACK;
  POSITION: STATIC; /* POSITION IS DEFAULT */
  TEXT-ALIGN: CENTER;
  MARGIN-TOP: -40PX;
  MARGIN-LEFT: -380PX;
}
.DESIGNER{
  COLOR: #E1D4F6;
  MARGIN-TOP: -44PX;
  PADDING-LEFT: 220PX;
  POSITION: FIXED; /* DEFINES A TEXT IS EXACTLY FITTED AT A SAME POSITION WHATEVER THE ACTION IS TAKEN */
}
.AND{
  MARGIN-LEFT: 420PX;
  MARGIN-TOP: 10PX;
  COLOR: BLACK;
}
.MY{
  MARGIN-LEFT: 630PX;
  MARGIN-TOP: -104PX;
  COLOR: #E1D4F6;
}
.CREATION{
  COLOR: #E1D4F6;
  MARGIN-LEFT: 740PX;
  POSITION: FIXED;
}
.SNAPS{
  TEXT-ALIGN: CENTER;
  COLOR: BLACK;
  FONT-FAMILY: GEORGIA;
  FONT-WEIGHT: BOLD;
  FONT-SIZE: 38PX;
  PADDING-BOTTOM:82PX;

}
.IMAGE1{
  PADDING-LEFT: 500PX;
  MARGIN-LEFT: 120PX;
  MARGIN-BOTTOM: -216PX;
}
.IMAGE1:HOVER{
  -WEBKIT-TRANSFORM: SCALE(1.4); /* ZOOM IMAGE WITH A CERTAIN SCALES, ANIMATION PROPERTY */
}
.IMAGE2{
  PADDING-LEFT: 1020PX;
  PADDING-TOP: 12PX;
  MARGIN-TOP: 24PX;
  MARGIN-BOTTOM: -226PX;
  MARGIN-LEFT: 184PX;
}
.IMAGE2:HOVER{
  -WEBKIT-TRANSFORM: SCALE(0.9); /* ZOOM IMAGE WITH CERTAIN SCALES, ANIMATION PROPERTY */
}
.IMAGE3{
  PADDING-TOP: 32PX;
  MARGIN-TOP: 4PX;
  MARGIN-LEFT: 2PX;
}
.IMAGE3:HOVER{
  -WEBKIT-TRANSFORM: SCALE(0.7); /* ZOOM IMAGE WITH A CERTAIN SCALES, ANIMATION PROPERTY */
}
.FOOTER{
  BACKGROUND-COLOR: SEASHELL; /* DEFINES A BACKGROUND COLOR OF A FOOTER */
  PADDING-TOP: 180PX;
}
.CATCH{
  POSITION: ABSOLUTE;
  FONT-FAMILY: GEORGIA;
  FONT-WEIGHT: BOLD;
  FONT-SIZE: 22PX;
  MARGIN-TOP: 102PX;
  PADDING-LEFT: 12PX;
  BACKGROUND-COLOR: BLACK; /* DEFINES A BACKGROUND COLOR OF A PARTICULAR TEXT */
  HEIGHT: 36PX;
  WIDTH:120PX;
  OPACITY: 0.6; /*DECREASES THE CLARITY OF A BACKGROUND COLOR OF A TEXT AND MAKES THE SECOND BACKGROUND VISIBLE THROUGH IT */
  MARGIN-LEFT: 20PX;
  COLOR: #E1D4F6; /*DEFINES A COLOR OF A TEXT I.E. BLUE MAGENTA GROUP .. REFERENCED FROM COLOR-HEX.COM */
}
.THUNDERS{
  POSITION:ABSOLUTE;
  FONT-FAMILY: GEORGIA;
  FONT-WEIGHT: BOLD;
  FONT-SIZE: 22PX;
  PADDING-LEFT: 4PX;
  PADDING-RIGHT: 2PX;
  PADDING-TOP: 2PX;
  MARGIN-TOP: 102PX;
  BACKGROUND-COLOR: BLACK;
  HEIGHT:36PX;
  WIDTH:-1200PX;
  MARGIN-LEFT: 700PX;
  OPACITY: 0.6;
  COLOR: #E1D4F6; /*DEFINES A COLOR OF A TEXT I.E. BLUE MAGENTA GROUP .. REFERENCED FROM COLOR-HEX.COM */
}
.DAY{
  POSITION: ABSOLUTE;
  FONT-SIZE: GEORGIA;
  FONT-WEIGHT: BOLD;
  FONT-SIZE: 22PX;
  MARGIN-LEFT: 1300PX;
  MARGIN-TOP: 102PX;
  BACKGROUND-COLOR: BLACK;
  OPACITY: 0.6;
  COLOR: #E1D4F6; /*DEFINES A COLOR OF A TEXT I.E. BLUE MAGENTA GROUP .. REFERENCED FROM COLOR-HEX.COM */
  PADDING: 4PX;
}

IMAGE1.HTML UNDER PORTFOLIO.HTML
<!--KRITAGYA JUNG ADHIKARI, 16418536-->

<!DOCTYPE HTML>
<HTML>
  <HEAD>
    <META CHARSET="UTF-8"> <!--DEFINES ENCODING VALUES FOR A PARTICULAR PAGE-->
    <LINK HREF="IMAGE1.CSS" REL="STYLESHEET" TYPE="TEXT/CSS"> <!--PROVIDES A LINK TO A CSS DEFINED CONSOLE-->
    <TITLE>FRONT</TITLE>
  </HEAD>
  <BODY>
    <DIV CLASS="HEADER">
      <A HREF="PORTFOLIO.HTML">CLICK HERE TO GO BACK</A>
    </DIV>
    <DIV CLASS="IMAGE11">
    <IMG SRC="IMAGE1.JPG">
    </DIV>
  </BODY>
  </HTML>

IMAGE1.CSS

BODY{
  BACKGROUND-COLOR: BLACK;
}
.HEADER{
  FONT-WEIGHT: BOLD;
  FONT-SIZE: 18PX;
  FONT-FAMILY: GEORGIA;
  COLOR: MAROON;
  PADDING-TOP: 12PX;
}
.IMAGE11{
  HEIGHT:200PX;
  WIDTH:320PX;
  MIN-WIDTH: 100%;
  MIN-HEIGHT: 100%;
  PADDING-TOP: 28PX;
}

IMAGE2.HTML UNDER PORTFOLIO.HTML
<!--KRITAGYA JUNG ADHIKARI, 16418536-->

<!DOCTYPE HTML>
<HTML>
  <HEAD>
    <META CHARSET="UTF-8"> <!--DEFINES ENCODING VALUES FOR A PARTICULAR PAGE-->
    <LINK HREF="IMAGE2.CSS" REL="STYLESHEET" TYPE="TEXT/CSS"> <!--PROVIDES A LINK TO A CSS DEFINED CONSOLE-->
    <TITLE>FRONT</TITLE>
  </HEAD>
  <BODY>
    <DIV CLASS="R">
      <A HREF="PORTFOLIO.HTML">CLICK HERE TO GO BACK</A>
    </DIV>
    <DIV CLASS="IMAGE22">
    <IMG SRC="IMAGE2.JPG">
    </DIV>
  </BODY>
  </HTML>

IMAGE2.CSS

BODY{
  BACKGROUND-COLOR: BLACK;
}
.R{
  FONT-WEIGHT: BOLD;
  FONT-SIZE: 18PX;
  FONT-FAMILY: ALGERIAN;
  COLOR: MAROON;
  PADDING-TOP: 12PX;
}
.IMAGE22{
  HEIGHT:200PX;
  WIDTH:320PX;
  MIN-WIDTH: 100%;
  MIN-HEIGHT: 100%;
  PADDING-TOP: 28PX;
}

IMAGE3.HTML UNDER PORTFOLIO.HTML
<!--KRITAGYA JUNG ADHIKARI, 16418536-->

<!DOCTYPE HTML>
<HTML>
  <HEAD>
    <META CHARSET="UTF-8"> <!--DEFINES ENCODING VALUES FOR A PARTICULAR PAGE-->
    <LINK HREF="IMAGE3.CSS" REL="STYLESHEET" TYPE="TEXT/CSS"> <!--PROVIDES A LINK TO A CSS DEFINED CONSOLE-->
    <TITLE>FRONT</TITLE>
  </HEAD>
  <BODY>
    <DIV CLASS="W">
      <A HREF="PORTFOLIO.HTML">CLICK HERE TO GO BACK</A>
    </DIV>
    <DIV CLASS="IMAGE33">
    <IMG SRC="IMAGE3.JPG">
    </DIV>
  </BODY>
  </HTML>

IMAGE3.CSS

BODY{
  BACKGROUND-COLOR: BLACK;
}
.W{
  FONT-WEIGHT: BOLD;
  FONT-SIZE: 18PX;
  FONT-FAMILY: ALGERIAN;
  COLOR: ORANGE;
  PADDING-TOP: 12PX;
}
.IMAGE33{
  HEIGHT:200PX;
  WIDTH:320PX;
  MIN-WIDTH: 100%;
  MIN-HEIGHT: 100%;
  PADDING-TOP: 28PX;
}

BIO.HTML
<!--KRITAGYA JUNG ADHIKARI, 16418536-->

<!DOCTYPE HTML>
<HTML>
  <HEAD>
    <LINK HREF="BIO.CSS" REL="STYLESHEET" TYPE="TEXT/CSS"> <!--PROVIDES LINK TO CSS DEFINED CONSOLE I.E. BIO.CSS-->
    <TITLE> BIO </TITLE>
  </HEAD>
  <BODY>
    <DIV CLASS="CONTAINER"> <!-- A CONTAINER CLASS SPECIFIED FOR FLEX-->
      <A HREF="INDEX.HTML"><DIV CLASS="FLEXX"> HOME </DIV>
      <A HREF="CV.HTML"><DIV CLASS="FLEXY"> CV </DIV></A>
      <A HREF="CONTACT.HTML"><DIV CLASS="FLEXZ"> CONTACT </DIV></A>
    </DIV>
    <DIV CLASS="TOP1"> <LINK HREF="HTTPS://FONTS.GOOGLEAPIS.COM/CSS?FAMILY=LOBSTER" REL="STYLESHEET"> A SHORT BIO </DIV> <!--FONT REFERENCED FROM GOOGLE API-->
    <DIV CLASS="TOP2"> <LINK HREF="HTTPS://FONTS.GOOGLEAPIS.COM/CSS?FAMILY=GREAT+VIBES|TANGERINE" REL="STYLESHEET"> <!--FONT REFERENCED FROM GOOGLE API-->
      <P>THIS IS KRITAGYA JUNG ADHIKARI WORKING WITH A PROJECT HIGHLIGHTING THE BASICS OF HTML AND CSS WORLD. AT FIRST, LET ME START WITH MY GEOGRAPHICAL DETAILS.
         I WAS BORN ON 17TH OF JULY, 1998 IN A COUNTRY WHERE CITIZENS ARE CALLED NEPALESE. GETTING MORE INTO IT, A BEAUTIFUL TOWN DHARAN WAS MY REGION OF BIRTH.
         FROM A VERY TENDER AGE, I HAD A SORT OF INTEREST IN A STUFFS THAT WERE IMAGINATIVE AND SURREAL. MUSIC WAS A KIND OF TASTE I REALLY HAD MUCH PREFERENCES TO.
         I USED TO LOATHE SCHOOLING MORE THAN MUCH. I NEVER HAD MUCH INTEREST IN ACADEMIC STUDIES BUT I MADE MY WAY TO HIGH SCHOOL AND THAT'S A REMARKABLE STEP IN MY
         LIFE. SCIENCE WAS A THING I REALLY LOVED SINCE CHILDHOOD. RESEARCH RELATED TO SCIENCE THING WERE ALWAYS ON MY MIND.</P> <!--DEFINES A PARAGRAPH-->
      <P> TALKING ABOUT HOBBIES, I AM REALLY FOND OF STRIKING THE BALL WITH A BAT AND VICE VERSA, SOCCERS WERE A KIND OF DREAM DURING A GROWING AGE.
         PERHAPS, MOST OF THE TIME IN MY LIFE IS WELL-UTILIZED IN MUSICAL WAY. </P>
      <BR> GUESS IT'S AN END TO A SHORT BIO. THE PROJECT IS REALLY SKILL-BUILDER AND MAKES SCHOLARS UTILIZE MIND JOBS WITH A SHARP EDGE. <!--BREAKS LINE-->
      <DIV CLASS="QUOTE"> " IMAGINE SURREAL AND KEEP MOVING FORWARD " </DIV>
    </BODY>
    </HTML>

BIO.CSS

@MEDIA ONLY SCREEN AND (MAX-WIDTH: 502PX){ /* DEFINES A RESPONSIVENESS OF A SPECIFIED CONTENT */
  BODY{
    BACKGROUND-COLOR: WHITE;
  }
}
.CONTAINER{
  DISPLAY: FLEX; /* DEFINES AN ELEMENT TO FIT IN DIFFERENT SCREEN SIZES */
  WIDTH: 220PX;
  HEIGHT: 32PX;
  BACKGROUND-COLOR: BLACK;
  BORDER-STYLE: SOLID; /* TYPE OF A BORDER SPECIFIED FPOR FLEX PROPERTY */
  BORDER-COLOR: ORANGE; /* A COLOR SPECIFIED FOR FLEX BORDER */
}
.FLEXX{
  FONT-FAMILY: GEORGIA;
  FONT-WEIGHT: BOLD;
  FONT-SIZE: 22PX;
  FLOAT: LEFT;
  COLOR:ORANGE;
  PADDING-TOP: 2PX;
  -WEBKIT-TRANSFORM: ROTATE(12DEG); /* ROTATES A TEXT TO SPECIFIED DEGREE, CSS ANIMATION PROPERTY */
}
.FLEXX:HOVER{ /* IDENTIFY SOME ELEMENT WITH A SHORT INDICATION WHEN WE MOVE CURSOR TOWARDS IT */
  BACKGROUND-COLOR: WHITE; /* DEFINE THE COLOR OF AN INDICATION WITH ORANGE BACKGROUND */
  TRANSITION-DELAY: 0.5S; /* CREATE A TIME INTERVAL FOR INDICATION WHEN A CURSOR IS MOVED TOWARDS TEXT */
}
.FLEXY{
  FONT-FAMILY: GEORGIA;
  FONT-WEIGHT: BOLD;
  FONT-SIZE: 22PX;
  FLOAT: LEFT;
  COLOR: ORANGE;
  PADDING-LEFT: 10PX;
  PADDING-TOP: 2PX;
}
.FLEXY:HOVER{
  BACKGROUND-COLOR: SEASHELL;
  TRANSITION-DELAY: 0.5S;
  PADDING-LEFT: 4PX;
}
.FLEXZ{
  FONT-FAMILY: GEORGIA;
  FONT-WEIGHT: BOLD;
  FONT-SIZE: 22PX;
  FLOAT: LEFT;
  COLOR: ORANGE;
  PADDING-LEFT: 10PX;
  PADDING-TOP: 2PX;
  -WEBKIT-TRANSFORM: ROTATE(-12DEG); /* ROTATES A TEXT TO SPECIFIED DEGREE, CSS ANIMATION PROPERTY */
}
.FLEXZ:HOVER{
  BACKGROUND-COLOR: WHITE;
  TRANSITION-DELAY: 0.5S;
  PADDING-LEFT: 2PX;
}
.TOP1{
  FONT-FAMILY: LOBSTER , CURSIVE; /* GOOGLE API FONT */
  FONT-SIZE: 52PX;
  TEXT-ALIGN: CENTER;
  PADDING-TOP: 42PX;
}
.TOP2{
  PADDING-TOP: 18PX;
  FONT-SIZE: 34PX;
  FONT-FAMILY: 'TANGERINE', CURSIVE; /* GOOGLE API FONT */
  FONT-WEIGHT: BOLD; /* DEFINES THE QUALITY OR STRUCTURE OF A FONT */
}
.QUOTE{
  FONT-SIZE: 38PX;
  PADDING-TOP: 38PX;
  COLOR: #EE7600; /* A DARK ORANGE, REFERENCED FROM COLOR-HEX.COM */
  FONT-WEIGHT: BOLD;
}

CONTACT.HTML
<!--KRITAGYA JUNG ADHIKARI, 16418536-->

<!DOCTYPE HTML>
<HTML>
  <HEAD>
    <META CHARSET="UTF-8">
    <LINK HREF="CONTACT.CSS" REL="STYLESHEET" TYPE="TEXT/CSS">
    <TITLE>CONTACT</TITLE>
  </HEAD>
  <BODY>
    <DIV CLASS="CONTACT1"><LINK HREF="HTTPS://FONTS.GOOGLEAPIS.COM/CSS?FAMILY=MONOTON" REL="STYLESHEET"> HERE IS A CONTACT </DIV> <!-- GOOGLE API FONT -->
    <DIV CLASS="THIS">
     <LINK HREF="HTTPS://FONTS.GOOGLEAPIS.COM/CSS?FAMILY=LOBSTER" REL="STYLESHEET"> <!-- GOOGLE API FONT -->
     <LI><A HREF="INDEX.HTML"><DIV CLASS="FRONT"> HOME </DIV></A></LI> <!--LINKS A CURRENT PAGE TO THE SPECIFIED PAGE WITHIN TAGS-->
     <LI><A HREF="CV.HTML"><DIV CLASS="EXTRA"> CV </DIV></LI>
     <LI><A HREF="PORTFOLIO.HTML"><DIV CLASS="PORTFOLIO"> PORTFOLIO </DIV></A></LI>
     <LI><A HREF="BIO.HTML"><DIV CLASS="MORE"> BIO </DIV></A></LI>
    </DIV>
    <FORM CLASS="CONTACT2"> <!-- TO INSERT A FORM -->
      <DIV CLASS="CONTACT5">
        <LABEL FOR="EMAIL"> EMAIL- </LABEL> <!-- CLASSIFY A PARTICULAR ELEMENT IN A FORM -->
        <INPUT TYPE="TEXT" NAME="EMAIL" ID="EMAIL"> <!-- DEFINES THE ATTRIBUTE VALUE OF A PARTICULAR CLASS -->
      </DIV>
      <DIV CLASS="CONTACT4">
        <LABEL FOR="MESSAGE"> MESSAGE: </LABEL>
        <TEXTAREA NAME="MESSAGE" ID="MESSAGE" ROWS="4" COLS="46"> YOUR MESSAGE HERE.. </TEXTAREA> <!-- DEFINED SIZE FOR A CLASS THROUGH ROWS AND COLUMNS SIZE -->
        <DIV CLASS="BUTTON"><INPUT TYPE="SUBMIT" VALUE="SUBMIT"></BUTTON> <!-- DEFINES BUTTON PROPERTY FOR SUBMISSION -->
      </DIV>
    </FORM>
    <DIV CLASS="FOOTER2">
      <LINK HREF="HTTPS://FONTS.GOOGLEAPIS.COM/CSS?FAMILY=CABIN+SKETCH" REL="STYLESHEET"> <!-- GOOGLE API FONT -->
      NUMBER- 0082 0046 28 <BR> <!-- BREAKS LINE -->
      G-MAIL: BROWNDANIEL163@GMAIL.COM <BR>
      FOLLOW ME ON TWITTER <BR>
      ELSE FACEBOOK.
    </DIV>
  </BODY>
</HTML>

CONTACT.CSS

BODY{
  BACKGROUND-COLOR: BLACK;
}
.CONTACT1{
  COLOR: #E1D4F6; /* REFERENCED FROM COLOR-HEX.COM */
  FONT-FAMILY: 'MONOTON', CURSIVE; /* GOOGLE API FONT */
  FONT-SIZE: 46PX;
  MARGIN-TOP: -128PX;
  MARGIN-LEFT: 418PX;
  POSITION: FIXED;
}
.THIS{
  FONT-SIZE: 20PX;
  FONT-FAMILY: LOBSTER , CURSIVE; /* GOOGLE API FONT */
  DISPLAY: -WEBKIT-FLEX;
  DISPLAY: FLEX; /* DEFINES AN ELEMENT TO FIT IN DIFFERENT SCREEN SIZES */
 -WEBKIT-FLEX-DIRECTION: ROW-REVERSE; /* THE DIRECTION WILL BE DEFINED RIGHT TO LEFT IN A ROW */
  FLEX-DIRECTION: ROW-REVERSE;
  WIDTH: 220PX;
  HEIGHT: 32PX;
  BACKGROUND-COLOR: BLACK;
  BORDER-STYLE: SOLID; /* TYPE OF A BORDER SPECIFIED FOR FLEX PROPERTY */
  BORDER-COLOR: ORANGE;
  ALIGN-ITEMS: CENTER;
  MARGIN-TOP: 200PX;
}
.FRONT{
  FLOAT: LEFT;
  COLOR: #EE7600; /* A DARK ORANGE, REFERENCED FROM COLOR-HEX.COM */
  PADDING-RIGHT: 10PX;
  MARGIN-TOP: -22PX;
}
.FRONT:HOVER{
  -WEBKIT-TRANSFORM: SCALE(1.2);
}
.EXTRA{
  FLOAT: LEFT;
  COLOR: #EE7600; /* A DARK ORANGE, REFERENCED FROM COLOR-HEX.COM */
  PADDING-RIGHT: 10PX;
  MARGIN-TOP: -22PX;
}
.EXTRA:HOVER{
  -WEBKIT-TRANSFORM: SCALE(1.2);
}
.PORTFOLIO{
  FLOAT: LEFT;
  COLOR: #EE7600; /* A DARK ORANGE, REFERENCED FROM COLOR-HEX.COM */
  PADDING-RIGHT: 10PX;
    MARGIN-TOP: -22PX;
}
.PORTFOLIO:HOVER{
  -WEBKIT-TRANSFORM: SCALE(1.2);
}
.MORE{
  FLOAT: LEFT;
  COLOR: #EE7600; /* A DARK ORANGE, REFERENCED FROM COLOR-HEX.COM */
  PADDING-RIGHT: 2PX;
  MARGIN-TOP: -22PX;
  PADDING-LEFT: 4PX;
}
.MORE:HOVER{
  -WEBKIT-TRANSFORM: SCALE(1.2);
}
.CONTACT2{
  PADDING-TOP: 102PX;
  COLOR: WHITE;
  PADDING-RIGHT: 10PX;
  FONT-FAMILY: GEORGIA;
  FONT-WEIGHT: BOLD;
}
.CONTACT4{
  PADDING-LEFT: 102PX;
  PADDING-TOP: 46PX;
  POSITION: FIXED;
}
.CONTACT5{
  PADDING-LEFT: 118PX;
}
.BUTTON{
  MARGIN-LEFT: 82PX;
  PADDING-TOP: 8PX;
}
.FOOTER2{
  BACKGROUND-COLOR: #483D8B;
  PADDING-TOP: 32PX;
  MARGIN-LEFT: 90PX;
  MARGIN-TOP: 82PX;
  WIDTH: 1200PX;
  HEIGHT:96PX;
  TEXT-ALIGN: CENTER;
  FONT-FAMILY: 'CABIN SKETCH', CURSIVE; /* GOOGLE API FONT */
  FONT-WEIGHT: BOLD;
  FONT-SIZE: 18PX;
  TEXT-SHADOW: 6PX 4PX BLACK; /* DEFINES A SHADOW OF A TEXT */
  COLOR: #E1D4F6; /* DEFINES A COLOR OF A TEXT IN A PAGE, REFERENCED FROM COLOR-HEX.COM */
  -WEBKIT-ANIMATION: FOOTER2 4S LINEAR INFINITE; /* A CSS ANIMATION PROPERTY WHICH CHANGES THE COLOR OF A DEFINED FOOTER2 FOR INFINITE LOOP IN A DURATION
                                                    OF 4 SECONDS */
}
@KEYFRAMES FOOTER2{ /* LINKED WITH ANIMATION PROPERTY WHICH DEFINES THE COLOR TO BE SHOWN IN A LOOPED FLOW */
  0%,100% {BACKGROUND: #483D8B;}
  25% {BACKGROUND: GREEN;}
  50% {BACKGROUND: ORANGE;}
  75% {BACKGROUND: MAROON;}
}

CV.HTML
<!--KRITAGYA JUNG ADHIKARI, 16418536-->

<!DOCTYPE HTML>
<HTML>
  <HEAD>
   <META CHARSET="UTF-8"> <!--DEFINES ENCODING VALUES FOR A PARTICULAR PAGE-->
   <LINK HREF="STYLEA.CSS" REL="STYLESHEET" TYPE="TEXT/CSS"> <!--PROVIDES A LINK TO A CSS DEFINED CONSOLE-->
    <TITLE>CV</TITLE>
  </HEAD>
  <BODY>
    <UL CLASS="I"> <!--DEFINES A CLASS AND A LIST AT A SAME TIME-->
      <DIV CLASS="J"> <!--CLASS AND LINE BREAK IS DEFINED AT A SAME TIME-->
      <LI><A HREF="INDEX.HTML"><DIV CLASS="FRONT"> HOME </DIV></A></LI> <!--LINKS A CURRENT PAGE TO THE SPECIFIED PAGE WITHIN TAGS-->
      <LI><A HREF="CV.HTML"><DIV CLASS="EXTRA"> CV </DIV></LI>
      <LI><A HREF="CONTACT.HTML"><DIV CLASS="CONTACT"> CONTACT </DIV></A></LI>
      <LI><A HREF="BIO.HTML"><DIV CLASS="MORE"> BIO </DIV></A></LI>
      </DIV>
    </UL>
    <DIV ID="HEADER">
      <DIV CLASS="TOPBOX">
        <LINK HREF="HTTPS://FONTS.GOOGLEAPIS.COM/CSS?FAMILY=LOBSTER" REL="STYLESHEET"> <!-- GOOGLE API FONT -->
        KRITAGYA JUNG ADHIKARI
      </DIV>
      <DIV CLASS="DOWN">
        <LINK HREF="HTTPS://FONTS.GOOGLEAPIS.COM/CSS?FAMILY=LOBSTER" REL="STYLESHEET"> <!-- GOOGLE API FONT -->
       KATHMANDU, NEPAL
      </DIV>
      <DIV CLASS="TOPBOX IMAGE">
        <IMG SRC="TOPBOX.JPG">
      </DIV>
    </DIV>
    <DIV CLASS="CONTENT">
      <LINK HREF="HTTPS://FONTS.GOOGLEAPIS.COM/CSS?FAMILY=LOBSTER" REL="STYLESHEET"> <!-- GOOGLE API FONT -->
      GMAIL- BROWNDANIEL163@GMAIL.COM
    </DIV>
    <DIV ID="CONTENT1">
     <DIV CLASS="E">
       <LINK HREF="HTTPS://FONTS.GOOGLEAPIS.COM/CSS?FAMILY=LOBSTER" REL="STYLESHEET"> <!-- GOOGLE API FONT -->
       <DIV CLASS="E1"><LINK HREF="HTTPS://FONTS.GOOGLEAPIS.COM/CSS?FAMILY=LOBSTER" REL="STYLESHEET">EDUCATION</DIV>  10+2 (LOYALTY ACADEMY/LITTLE ANGELS' HIGH SCHOOL)
        <DIV CLASS="DATE"><LINK HREF="HTTPS://FONTS.GOOGLEAPIS.COM/CSS?FAMILY=LOBSTER" REL="STYLESHEET"> 2006-2016
     </DIV>
   </DIV>
    <DIV CLASS="R">
      <LINK HREF="HTTPS://FONTS.GOOGLEAPIS.COM/CSS?FAMILY=LOBSTER" REL="STYLESHEET"> <!-- GOOGLE API FONT -->
     RELEVANT COURSEWORK- B.SC.(HONS)COMPUTING
                          <DIV CLASS="NAMI"><LINK HREF="HTTPS://FONTS.GOOGLEAPIS.COM/CSS?FAMILY=LOBSTER" REL="STYLESHEET"> NAMI COLLEGE</DIV>
                          <DIV CLASS="UN"><LINK HREF="HTTPS://FONTS.GOOGLEAPIS.COM/CSS?FAMILY=LOBSTER" REL="STYLESHEET"> UNIVERSITY OF NORTHAMPTON</DIV>
    </DIV>
    <DIV CLASS= "E2">
      <LINK HREF="HTTPS://FONTS.GOOGLEAPIS.COM/CSS?FAMILY=LOBSTER" REL="STYLESHEET"> <!-- GOOGLE API FONT -->
      <DIV CLASS="EXP2"><LINK HREF="HTTPS://FONTS.GOOGLEAPIS.COM/CSS?FAMILY=LOBSTER" REL="STYLESHEET"> EXPERIENCE</DIV>  WORKSHOPS REFLECTING THE BASICS OF NETWORK AND COMMUNICATION
    </DIV>
    <DIV CLASS="SKILLS">
      <LINK HREF="HTTPS://FONTS.GOOGLEAPIS.COM/CSS?FAMILY=LOBSTER" REL="STYLESHEET"> <!-- GOOGLE API FONT -->
     SKILLS- SPECIALIZED IN TECHNIQUES REGARDING NETWORKS<BR>
             <DIV CLASS="FEED"><LINK HREF="HTTPS://FONTS.GOOGLEAPIS.COM/CSS?FAMILY=LOBSTER" REL="STYLESHEET"> SOFTWARE FEEDBACKS</DIV> <!-- GOOGLE API FONT -->
    </DIV>
    <DIV CLASS="RE">
      <LINK HREF="HTTPS://FONTS.GOOGLEAPIS.COM/CSS?FAMILY=LOBSTER" REL="STYLESHEET"> <!-- GOOGLE API FONT -->
      <DIV CLASS="RELATED">
      <LINK HREF="HTTPS://FONTS.GOOGLEAPIS.COM/CSS?FAMILY=LOBSTER" REL="STYLESHEET"> <!-- GOOGLE API FONT -->
      RELATED ACTIVITIES</DIV>  CLAMPING AND BASICS IN WEB DEVELOPEMENT
    </DIV>
    <DIV CLASS="ADD">
      <LINK HREF="HTTPS://FONTS.GOOGLEAPIS.COM/CSS?FAMILY=LOBSTER" REL="STYLESHEET"> <!-- GOOGLE API FONT -->
      <A CLASS= "ADD1"> <LINK HREF="HTTPS://FONTS.GOOGLEAPIS.COM/CSS?FAMILY=LOBSTER" REL="STYLESHEET"> ADDITIONAL SKILLS</A> - WORKING WITH PYTHON AND JAVA
   </DIV>
   </DIV>
  </BODY>
</HTML>

STYLEA.CSS (CV)

BODY{
  BACKGROUND-COLOR: SEASHELL;
  MARGIN: 0;
  PADDING: 0;
}
.I{
  OVERFLOW: HIDDEN; /* HIDES A EXTRA BOUNDARIES FROM AN ELEMENT */
  LIST-STYLE-TYPE: NONE; /* DISCARDS BULLETS AND LISTS INDICATIVES */
  PADDING: 0;
  MARGIN: 0;
  BACKGROUND-COLOR: #000F19; /* DEFINES A BZCKGROUND COLOR I.E. LIGHTENED VALUE, REFERENCED FROM COLOR-HEX.COM */
}
.J{
FONT-FAMILY: GEORGIA;
FONT-WEIGHT: BOLD;
FONT-SIZE: 18PX;
}
.FRONT{
  PADDING-BOTTOM: 10PX;
  PADDING-TOP: 10PX;
  COLOR: #E1D4F6; /*DEFINES A COLOR OF A TEXT I.E. BLUE MAGENTA GROUP .. REFERENCED FROM COLOR-HEX.COM */
  FLOAT:LEFT;
  TEXT-DECORATION: NONE;
}
.FRONT:HOVER{ /* IDENTIFY SOME ELEMENT WITH A SHORT INDICATION WHEN WE MOVE CURSOR TOWARDS IT */
  BACKGROUND-COLOR: MAROON; /* DEFINE THE COLOR OF AN INDICATION WITH MAROON BACKGROUND */
  TRANSITION-DELAY: 0.5S; /* CREATE A TIME INTERVAL FOR INDICATION WHEN A CURSOR IS MOVED TOWARDS TEXT */
}

.EXTRA{
  PADDING-LEFT: 16PX;
  PADDING-BOTTOM: 10PX; /* DEFINES A DISTANCE BETWEEN TEXT AND A PARTICULAR LINE OR AN ELEMENT */
  PADDING-TOP: 10PX;
  COLOR: #E1D4F6; /*DEFINES A COLOR OF A TEXT I.E. BLUE MAGENTA GROUP .. REFERENCED FROM COLOR-HEX.COM */
  FLOAT:LEFT;
  TEXT-DECORATION: NONE;
}
.EXTRA:HOVER{
  BACKGROUND-COLOR: MAROON;
  TRANSITION-DELAY: 0.5S;
  MARGIN-LEFT: 10PX;
  MARGIN-RIGHT: 2PX;
  PADDING-RIGHT: 16PX;
}
.CONTACT{
  PADDING-LEFT: 16PX;
  PADDING-BOTTOM: 10PX;
  PADDING-TOP: 10PX;
  COLOR: #E1D4F6; /*DEFINES A COLOR OF A TEXT I.E. BLUE MAGENTA GROUP .. REFERENCED FROM COLOR-HEX.COM */
  FLOAT: LEFT;
  TEXT-DECORATION: NONE;
}
.CONTACT:HOVER{
  BACKGROUND-COLOR: MAROON;
  TRANSITION-DELAY: 0.5S;
  MARGIN-LEFT: 14PX;
  MARGIN-RIGHT: 4PX;
  PADDING-RIGHT: 16PX;
}
.MORE{
  PADDING-LEFT: 16PX;
  PADDING-BOTTOM: 10PX;
  PADDING-TOP: 10PX;
  COLOR: #E1D4F6; /*DEFINES A COLOR OF A TEXT I.E. BLUE MAGENTA GROUP .. REFERENCED FROM COLOR-HEX.COM */
  FLOAT: LEFT;
  TEXT-DECORATION: NONE;
}
.MORE:HOVER{
  BACKGROUND-COLOR: MAROON;
  TRANSITION-DELAY: 0.5S;
  MARGIN-LEFT: 10PX;
  MARGIN-RIGHT: 2PX;
  PADDING-RIGHT: 14PX;
}
.TOPBOX{
  FONT-SIZE: 38PX;
  COLOR: #AA4069; /*DEFINES A COLOR OF A TEXT I.E. ROUGE .. REFERENCED FROM COLOR-HEX.COM */
  TEXT-ALIGN: LEFT;
  MARGIN-TOP: 40PX;
  FONT-FAMILY: LOBSTER , CURSIVE; /* GOOGLE API FONT */
}
.DOWN{
  MARGIN-LEFT: 4PX;
  FONT-FAMILY: LOBSTER , CURSIVE; /* GOOGLE API FONT */
  FONT-SIZE: 26PX;
  COLOR: #DA2647; /*DEFINES A COLOR OF A TEXT I.E. MARRON FAMILY .. REFERENCED FROM COLOR-HEX.COM */
}
.TOPBOX IMAGE{
  HEIGHT: 200PX;
  WIDTH: 280PX;
  POSITION: ABSOLUTE; /* POSITIONED RELATIVE TO BACKGROUND IMAGE, CAN RUN OVER IMAGE */
  MARGIN-TOP: -102PX;
  LEFT: 758PX;
}
.CONTENT{
  FONT-SIZE: 20PX;
  FONT-FAMILY: LOBSTER , CURSIVE; /* GOOGLE API FONT */
  COLOR: RED;
  MARGIN-TOP: 200PX;
  BACKGROUND-COLOR: BLACK;
  PADDING: 10PX;
  MARGIN-RIGHT: 1082PX;
}
.E{
  MARGIN-TOP: 26PX;
  FONT-SIZE: 18PX;
  COLOR: GREEN;
  FONT-FAMILY: LOBSTER , CURSIVE; /* GOOGLE API FONT */
  MARGIN-LEFT: 8PX;
  BORDER-STYLE: SOLID;
  MARGIN-RIGHT: 900PX;
  MARGIN-LEFT: 14PX;
}
.E1{
  FONT-SIZE: 24PX;
  FONT-FAMILY: LOBSTER , CURSIVE; /* GOOGLE API FONT */
  COLOR:RED;
  PADDING:10PX;
}
.DATE{
  PADDING-LEFT: 126PX;
  FONT-FAMILY: LOBSTER , CURSIVE; /* GOOGLE API FONT */
}
.R{
FONT-SIZE: 20PX;
COLOR: #C32148; /*DEFINES A COLOR OF A TEXT I.E. BRIGHT MARRON.. REFERENCED FROM COLOR-HEX.COM */
PADDING: 14PX;
FONT-FAMILY: LOBSTER , CURSIVE; /* GOOGLE API FONT */
BORDER-STYLE: SOLID;
MARGIN-RIGHT: 900PX;
MARGIN-LEFT: 14PX;
}
.NAMI{
  PADDING-LEFT: 186PX;
  FONT-SIZE: 16PX;
  FONT-FAMILY: LOBSTER , CURSIVE; /* GOOGLE API FONT */
}
.UN{
  PADDING-LEFT: 184PX;
  FONT-SIZE: 16PX;
  FONT-FAMILY: LOBSTER , CURSIVE; /* GOOGLE API FONT */
}
.E2{
  FONT-SIZE: 18PX;
  COLOR: GREEN;
  PADDING: 14PX;
  MARGIN-LEFT: 8PX;
  FONT-FAMILY: LOBSTER , CURSIVE; /* GOOGLE API FONT */
  BORDER-STYLE: SOLID;
  MARGIN-RIGHT: 900PX;
  MARGIN-LEFT: 14PX;
}
.EXP2{
  COLOR:RED;
  FONT-SIZE: 24PX;
  FONT-FAMILY: LOBSTER , CURSIVE; /* GOOGLE API FONT */
MARGIN-BOTTOM: 6PX;
}
.SKILLS{
  FONT-SIZE: 20PX;
  COLOR: #C32148; /*DEFINES A COLOR OF A TEXT I.E. BRIGHT MARRON.. REFERENCED FROM COLOR-HEX.COM */
  PADDING: 14PX;
  FONT-FAMILY: LOBSTER , CURSIVE; /* GOOGLE API FONT */
  BORDER-STYLE: SOLID;
  MARGIN-RIGHT: 900PX;
  MARGIN-LEFT: 14PX;
}
.FEED{
  FONT-SIZE: 20PX;
  PADDING-LEFT: 58PX;
  FONT-FAMILY: LOBSTER , CURSIVE; /* GOOGLE API FONT */
}
.RE{
  COLOR: GREEN;
  FONT-SIZE: 18PX;
  FONT-FAMILY: LOBSTER , CURSIVE; /* GOOGLE API FONT */
  MARGIN-LEFT: 14PX;
  BORDER-STYLE: SOLID;
  MARGIN-RIGHT: 900PX;
}
.RELATED{
  COLOR:RED;
  FONT-SIZE: 24PX;
  PADDING: 14PX;
  FONT-FAMILY: LOBSTER , CURSIVE; /* GOOGLE API FONT */
  MARGIN-LEFT: -8PX;
}
.ADD{
  FONT-FAMILY: LOBSTER , CURSIVE; /* GOOGLE API FONT */
  FONT-SIZE: 22PX;
  COLOR: #C32148; /*DEFINES A COLOR OF A TEXT I.E. BRIGHT MARRON.. REFERENCED FROM COLOR-HEX.COM */
  PADDING-TOP: 18PX;
  PADDING-LEFT: 14PX;
  BORDER-STYLE: SOLID;
  MARGIN-RIGHT: 900PX;
  MARGIN-LEFT: 14PX;
}
.ADD1{
  FONT-SIZE: 18PX
  FONT-FAMILY: LOBSTER , CURSIVE; /* GOOGLE API FONT */
}

TIME DETAILS AND OBSTACLES 

TO COMPLETE THE ASSIGNMENT IT TOOK ME ABOUT 32 HOURS. SOME PROPERTIES SUCH AS HEIGHT AND WIDTH WERE NOT SUPPORTED BY CSS AND BROWSER WOULD NOT GUARANTEE THE SAME FIXATION FOR EVERY PAGES. FOR EXAMPLE: INTERNET EXPLORER SHOWS THE FULL SIZE OF A PAGE BUT CHROME DOESN�T. I TRIED TO DEFINE MAX-WIDTH PROPERTY. BUT IT DIDN�T WORKED.
TO FIGURE OUT THE SOLUTIONS FOR OBSTACLES, THE TIME EXPANSION WAS INCREASING STEP WISE. PERHAPS, SOME ONLINE TUTORIALS AND W3 SCHOOLS HELPED ME A LOT TO BUILD THIS WEB PAGE. 





LIMITATIONS

I) SINCE CSS COULDN�T FETCH HEIGHT AND WIDTH PROPERTY FOR SOME ELEMENTS, IT WAS DEFINED IN HTML PAGE,
II) HUGE VARIATIONS TO DEFINE MARGIN AND PADDING PROPERTY WITH EASE.
























CONCLUSION

AT LAST, CREATING WEB WAS A GREAT PLATFORM FOR SCHOLARS TO SHOW THEIR TOTAL HOUR FOCUSED IN THE GIVEN FIELD. IT LETS THE SCHOLARS TO DO THE THINGS ON THEIR OWN AND LEARN MORE. THIS ASSIGNMENT HELPED ME A LOT TO LEARN ABOUT HTML AND CSS; ALSO IT�S WORLD AND KNOW ITS WORKING. THUS, WEB IS TOO FUNCTIONAL AND IS A CAPSULE FOR BRAINSTORM ORIENTED!!

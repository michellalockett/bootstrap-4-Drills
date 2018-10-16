{\rtf1\ansi\ansicpg1252\cocoartf1504\cocoasubrtf830
{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;\red25\green28\blue31;\red12\green93\blue207;}
{\*\expandedcolortbl;;\cssrgb\c12941\c14510\c16078;\cssrgb\c784\c45882\c84706;}
{\*\listtable{\list\listtemplateid1\listhybrid{\listlevel\levelnfc0\levelnfcn0\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{decimal\}}{\leveltext\leveltemplateid1\'01\'00;}{\levelnumbers\'01;}\fi-360\li720\lin720 }{\listname ;}\listid1}
{\list\listtemplateid2\listhybrid{\listlevel\levelnfc0\levelnfcn0\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{decimal\}}{\leveltext\leveltemplateid101\'01\'00;}{\levelnumbers\'01;}\fi-360\li720\lin720 }{\listname ;}\listid2}
{\list\listtemplateid3\listhybrid{\listlevel\levelnfc0\levelnfcn0\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{decimal\}}{\leveltext\leveltemplateid201\'01\'00;}{\levelnumbers\'01;}\fi-360\li720\lin720 }{\listname ;}\listid3}
{\list\listtemplateid4\listhybrid{\listlevel\levelnfc0\levelnfcn0\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{decimal\}}{\leveltext\leveltemplateid301\'01\'00;}{\levelnumbers\'01;}\fi-360\li720\lin720 }{\listname ;}\listid4}}
{\*\listoverridetable{\listoverride\listid1\listoverridecount0\ls1}{\listoverride\listid2\listoverridecount0\ls2}{\listoverride\listid3\listoverridecount0\ls3}{\listoverride\listid4\listoverridecount0\ls4}}
\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\deftab720
\pard\pardeftab720\partightenfactor0

\f0\fs64 \cf2 \expnd0\expndtw0\kerning0
Objectives\
\pard\pardeftab720\partightenfactor0

\fs32 \cf2 Practice pulling in Bootstrap 4\'92s CDN and using its class based styling.\
\pard\pardeftab720\partightenfactor0

\fs64 \cf2 Setup\
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls1\ilvl0
\fs32 \cf2 \kerning1\expnd0\expndtw0 {\listtext	1	}\expnd0\expndtw0\kerning0
Create a new folder for these drills, title it Bootstrap 4 Drills\
\ls1\ilvl0\kerning1\expnd0\expndtw0 {\listtext	2	}\expnd0\expndtw0\kerning0
Go ahead and initialize a git repository on this project so it will be available to view on your github account.\
\ls1\ilvl0\kerning1\expnd0\expndtw0 {\listtext	3	}\expnd0\expndtw0\kerning0
Create a README.md file, copy and past these drill instructions into that file.\
\ls1\ilvl0\kerning1\expnd0\expndtw0 {\listtext	4	}\expnd0\expndtw0\kerning0
Create an index.html page, use the keyboard shortcut to get the html doc started.\
\ls1\ilvl0\kerning1\expnd0\expndtw0 {\listtext	5	}\expnd0\expndtw0\kerning0
Go to the following {\field{\*\fldinst{HYPERLINK "https://getbootstrap.com/docs/4.0/getting-started/introduction/"}}{\fldrslt \cf3 link}} copy the cdn link and past it in the head of your html document.\
\ls1\ilvl0\kerning1\expnd0\expndtw0 {\listtext	6	}\expnd0\expndtw0\kerning0
You now have connected the bootstrap cdn to your project and can begin using Bootstrap 4! Hooray.\
\ls1\ilvl0\kerning1\expnd0\expndtw0 {\listtext	7	}\expnd0\expndtw0\kerning0
Add a styles.css document, link it to your html document AFTER the bootstrap link.\
\pard\pardeftab720\partightenfactor0

\fs64 \cf2 Containers and the Grid System\
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls2\ilvl0
\fs32 \cf2 \kerning1\expnd0\expndtw0 {\listtext	1	}\expnd0\expndtw0\kerning0
Add a div to your html document, using bootstraps container class, have this be a container.\
\ls2\ilvl0\kerning1\expnd0\expndtw0 {\listtext	2	}\expnd0\expndtw0\kerning0
To visually see what a container class does to a div, we will need to apply some styling to it in css. Let\'92s go to our css document and apply a background-color of blue and a height of 500px to anything with a class named container (Which for know should only be 1 element).\
\ls2\ilvl0\kerning1\expnd0\expndtw0 {\listtext	3	}\expnd0\expndtw0\kerning0
Change the class on the div from a container to a container-fluid. Refresh and take not of the differences. Once you are finished visually seeing the difference between the two, remove or comment out the styling in the css file.\
\ls2\ilvl0\kerning1\expnd0\expndtw0 {\listtext	4	}\expnd0\expndtw0\kerning0
Insert a div inside of the existing container div. Give this div a class name of row, then insert an h1 element inside of the row div. Have the text read \'93First Boostrap Project\'94.\
\ls2\ilvl0\kerning1\expnd0\expndtw0 {\listtext	5	}\expnd0\expndtw0\kerning0
Refer this {\field{\*\fldinst{HYPERLINK "https://getbootstrap.com/docs/4.0/layout/grid/"}}{\fldrslt \cf3 link}} on the grid system to learn how rows and alignment work using bootstrap. Lets try to center align our h1, go to the following link to explore how to do so. (Hint: Jump to the horizontal alignment section of bootstraps documents, you may need to adjust the amount of columns, 1 through 12, to keep everything on 1 line).\
\ls2\ilvl0\kerning1\expnd0\expndtw0 {\listtext	6	}\expnd0\expndtw0\kerning0
Add a new div which will be another row of elements. Add 3 divs, give each some text of your choice and apply bootstrap styling to have 1 div appear at the start of the row, one in the center, and one at the end.\
\pard\pardeftab720\partightenfactor0

\fs64 \cf2 Bootstrap Forms\
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls3\ilvl0
\fs32 \cf2 \kerning1\expnd0\expndtw0 {\listtext	1	}\expnd0\expndtw0\kerning0
Use this {\field{\*\fldinst{HYPERLINK "https://getbootstrap.com/docs/4.0/components/forms/"}}{\fldrslt \cf3 link}} for reference for the next section:\
\ls3\ilvl0\kerning1\expnd0\expndtw0 {\listtext	2	}\expnd0\expndtw0\kerning0
Create a form inside of the existing container but outside of any existing rows or other content (ask for help if nesting elements is confusing).\
\ls3\ilvl0\kerning1\expnd0\expndtw0 {\listtext	3	}\expnd0\expndtw0\kerning0
Have this form contain an input for an email and password. Make sure each input has labels!\
\ls3\ilvl0\kerning1\expnd0\expndtw0 {\listtext	4	}\expnd0\expndtw0\kerning0
Add 2 checkboxes to the form, one for cats and one for dogs.\
\ls3\ilvl0\kerning1\expnd0\expndtw0 {\listtext	5	}\expnd0\expndtw0\kerning0
Add 3 radios, have them say Cheese Pizza, Vegetable Pizza, and Meat Pizza\
\ls3\ilvl0\kerning1\expnd0\expndtw0 {\listtext	6	}\expnd0\expndtw0\kerning0
Make Sure the form has a submit input!\
\pard\pardeftab720\partightenfactor0

\fs64 \cf2 Cards\
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls4\ilvl0
\fs32 \cf2 \kerning1\expnd0\expndtw0 {\listtext	1	}\expnd0\expndtw0\kerning0
Refer to {\field{\*\fldinst{HYPERLINK "https://getbootstrap.com/docs/4.0/components/card/"}}{\fldrslt \cf3 this link}} for more information on cards.\
\ls4\ilvl0\kerning1\expnd0\expndtw0 {\listtext	2	}\expnd0\expndtw0\kerning0
Outside of the form but still inside of the container, create a basic card with a card body and have it have an h3 which will be a friends name, and a paragraph element containing a small piece of info on your friend. Create 6 of these cards.\
\ls4\ilvl0\kerning1\expnd0\expndtw0 {\listtext	3	}\expnd0\expndtw0\kerning0
Have them align so there are 2 per row.\
\ls4\ilvl0\kerning1\expnd0\expndtw0 {\listtext	4	}\expnd0\expndtw0\kerning0
Once you get them aligning 2 per row, change it so it is 3 per row.}
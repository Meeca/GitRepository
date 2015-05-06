{\rtf1\ansi\ansicpg936\cocoartf1347\cocoasubrtf570
{\fonttbl\f0\froman\fcharset0 Times-Roman;}
{\colortbl;\red255\green255\blue255;\red0\green0\blue0;}
{\*\listtable{\list\listtemplateid1\listhybrid{\listlevel\levelnfc0\levelnfcn0\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{decimal\}.}{\leveltext\leveltemplateid1\'02\'00.;}{\levelnumbers\'01;}\fi-360\li720\lin720 }{\listname ;}\listid1}}
{\*\listoverridetable{\listoverride\listid1\listoverridecount0\ls1}}
\paperw11900\paperh16840\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\deftab720
\pard\tx220\tx720\pardeftab720\li720\fi-720
\ls1\ilvl0
\f0\fs24 \cf2 {\listtext	1.	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 #!/bin/sh\'a0\'a0\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	2.	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 PROJ=`find\'a0.\'a0-name\'a0'*.xib'\'a0-o\'a0-name\'a0'*.[mh]'`\'a0\'a0\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	3.	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 \'a0\'a0\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	4.	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 for\'a0png\'a0in\'a0`find\'a0.\'a0-name\'a0'*.png'`\'a0\'a0\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	5.	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 do\'a0\'a0\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	6.	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 \'a0\'a0\'a0\'a0name=`basename\'a0$png`\'a0\'a0\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	7.	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 \'a0\'a0\'a0\'a0if\'a0!\'a0grep\'a0-qhs\'a0"$name"\'a0"$PROJ";\'a0then\'a0\'a0\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	8.	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 \'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0echo\'a0"$png\'a0is\'a0not\'a0referenced"\'a0\'a0\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	9.	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 \'a0\'a0\'a0\'a0fi\'a0\'a0\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	10.	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 done\'a0\'a0\
}
README.txt

SUBJECT: OnSong Chords & Lyrics Formatting Intro
AUTHOR: Eric

This folder contains text files to use as source for Chords & Lyrics to be imported into Jacques' tablet and his OnSong app (used during our rehearsals).

WARNING: The .txt files cannot be edited directly using Google Docs. A "plain text file editor" is needed instead.


User Manual: https://onsongapp.com/docs/features/formats/onsong/

The above manual points to additional sections summarized below.


ONSONG FILE FORMATTING


METADATA
See below example of song metadata positioned at the top of each file. The fields in bold represent optional information but are often used to instruct OnSong to behave as expected for music performance – i.e. auto-scrolling, showing proper chords (in our chosen transposed key)... 

Example:
  Amazing Grace
  Artist: Daniel Thomas
  Duration: 3:59
  Key: D
  TransposedKey: E
  Tempo: 76

More details here:  https://onsongapp.com/docs/features/formats/onsong/metadata/


SECTIONS
Ref.: https://onsongapp.com/docs/features/formats/onsong/section 

The file's body (below the metadata) should have different paragraphs starting with a section name (or heading) ending with colon – e.g. INTRO:, BRIDGE:, CHORUS 1:, VERSE 2:, OUTRO: ...


CHORDS AND LYRICS

Use "chords over lyrics" formatting. You can leverage content on Ultimate Guitar and similar sites to avoid stating from scratch. More details here:  https://onsongapp.com/docs/features/formats/onsong/chords/#chords-over-lyrics 

For example:
  E
  I want to break free

  (NC)                                    E
  Use parenthesis around "No Chord" (NC). Transposing chords in the same line will still work.


MUSICAL INSTRUCTIONS
Use parentheses to include musical instructions such as number of repetitions. For example:

  A
  Fa, la, la, la, la, la, la (Repeat 8x)


COMMENTS
For adding comments in the file that won't be shown while performing, prepend the line with a pound (#). Ref.: https://onsongapp.com/docs/features/formats/onsong/chords/#comments 

For example:
# Rick please add some chords here to support your solo


COLORING AND TEXT FORMATTING
Ref.: https://onsongapp.com/docs/features/formats/onsong/formatting/

Examples
*This line will be bold
/This line will be italicized
!This line will be bold and italicized
&red:This text will be red
&yellow:This text will be yellow
>yellow:This line will be highlighted in yellow


BAND STANDARD
1. Use hard-coded pink color for section names.  For Example:
   &pink:CHORUS

2. Use yellow letter coloring for lines with back-vocals
   &yellow:We will, we will rock you!

#. Use red coloring for instructions
   &red:Wait for visual cue...

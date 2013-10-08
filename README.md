KnightSequenceTour
==================

Knight Sequence Tour

//
// Contents
//

This program finds all n-key sequences that can be keyed into the keypad in the following manner:
•	The initial keypress can be any of the keys.
•	Each subsequent keypress must be a knight move from the previous keypress.  
•	There can be at most 2 vowels in the sequence.

A knight move is made in one of the following ways:
1.	Move two steps horizontally and one step vertically.
2.	Move two steps vertically and one step horizontally.


The KnightSequences program requires Java 7 or higher.

The source files are included in the jar file in source folder.
The source files are KnightSequenceClient.java and KnightSequenceService.java.

There are also junit tests included in the tests folder.

The program was created in Eclipse and the application uses Maven and Spring.  
All required Java API libraries are included.

When running the program, you will be prompted for a number that will represent
the number of sequences that you would like to be run.  
  
//
// Running The Knight Sequence
//

Once you have the jar binary, running the program is straightforward.

On the command line, type

java -cp KnightSequence.jar com.kcg.knight.sequence.KnightSequenceClient


You will be prompted to enter the number of sequences 

Enter the number and click enter
The program will respond with the count of the number of sequences

//
// Details
//


Question/Answer Dataset, Release 1.2
====================================

This is the README file for the Question/Answer dataset generated by students 
who took undergraduate natural language processing courses taught by Noah Smith 
at Carnegie Mellon and Rebecca Hwa at the University of Pittsburgh during 
Spring 2008, Spring 2009, and Spring 2010.

There are three directories, one for each year of students: S08, S09, and S10.

The file "question_answer_pairs.txt" contains the questions and answers. The first line of the file contains 
column names for the tab-separated data fields in the file. This first line follows:

ArticleTitle    Question        Answer  DifficultyFromQuestioner        DifficultyFromAnswerer  ArticleFile

Field 1 is the name of the Wikipedia article from which questions and answers initially came.
Field 2 is the question.
Field 3 is the answer.
Field 4 is the prescribed difficulty rating for the question as given to the question-writer. 
Field 5 is a difficulty rating assigned by the individual who evaluated and answered the question, 
which may differ from the difficulty in field 4.
Field 6 is the relative path to the prefix of the article files. html files (.htm) and cleaned 
text (.txt) files are provided.

Questions that were judged to be poor were discarded from this data set.

There are frequently multiple lines with the same question, which appear if those questions were answered 
by multiple individuals. 

This particular release was prepared by Kevin Gimpel, but the data collection process 
was performed by Noah Smith, Mike Heilman, Rebecca Hwa, Shay Cohen, and many CMU students 
and Pitt students.

License Information:

The contents of S08 and S09 are released under the GFDL (http://www.gnu.org/licenses/fdl.html) and the contents of S10 are released under the CC BY-SA 3.0 (http://creativecommons.org/licenses/by-sa/3.0/). A copy of the GFDL license is included in the file named LICENSE-S08,S09. The reason for the different licenses is because Wikipedia moved from the GFDL to the CC BY-SA 3.0 license in the summer of 2009..

Release history:

2/18/2010: Version 1.0
  * Partial set of question/answer pairs from 2008 and 2009

8/6/2010: Version 1.1
  * All question/answer pairs from 2008, 2009, and 2010

8/23/2013: Version 1.2
  * Same data as Version 1.1, but now released under standard licenses

If you use this data in a publication, please cite the following:

Noah A. Smith, Michael Heilman, and Rebecca Hwa
Question Generation as a Competitive Undergraduate Course Project
In Proceedings of the NSF Workshop on the Question Generation Shared Task and Evaluation Challenge, Arlington, VA, September 2008. 
Available at: http://www.cs.cmu.edu/~nasmith/papers/smith+heilman+hwa.nsf08.pdf

Kevin Gimpel
kgimpel@cs.cmu.edu
kgimpel@ttic.edu
8/23/2013
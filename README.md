# Thesis

This is a quick overview up of how I prepared my thesis.  It should help those of you who are not familiar with LaTeX 
to get up and running fairly quickly if you decide you want to use LaTeX to format your thesis.  

*Disclaimer: I have not yet gained a high amount of proficiency with LaTeX, and this is probably not the best approach.  However,
it gave me a fair amount of flexibility and worked well enough with the tools I had already been using.*

# Tools
1. Papers 3.4.5 - Downloading papers/managing references. Can export a bibliography as a .bib file.

2. Dropbox - Used Dropbox to sync my Papers library across multiple computers.

3. Google Docs - Typing the outline and the thesis. Not ideal for version control, but good for sharing with people who may
provide feedback.

4. Sharelatex.com (free) - Copied written text from google doc to Sharelatex.com to compile a nicely formatted thesis.
https://github.com/mvzink/ucetd-latex (UChicago Thesis template).  Sharelatex also has some version control features that I 
never looked into or learned how to use.


# Approach
1. Typed thesis outline in Google docs, sometimes inserting references from Papers.  Can type command + option + C to copy Bibtex-style reference from Papers, and then command + v to insert it in the text.

			e.g. \cite{Krendel:2005ko}, \cite{Simmons:1996vj,Finer:1994kw,Schliwa:2003jn}

2. Typed individual chapters in separate Google Docs

3. After the text was finished, I wrote the code for the figures/figure legends. 

4. I copied the code for the figures/figure legends to the individual chapters

5. I exported a .bib file from Papers.


# Useful tips/gotchas

0. Closing brackets {} is important

1. \cite{} - command for adding citations in text

2. \textit{} - command for italicizing text. e.g. \textit{C. elegans}

3. \textbf{} - command for making text bold e.g. \textbf{Chapter 1}

4. can combine bold and italics: \textit{textbf{C. elegans}} 

5. \chapter{Title} - creates new chapter

6. \section{Title} - creates a new section with Title

7. \subsection{Title} - creates numbered subsections with Title

8. \newpage - This command forces everything that comes after to show up on a new page

9. Might have to rearrange the order of citations in text (not really necessary).  For example the citation \cite{Simmons:1996vj,Finer:1994kw,Schliwa:2003jn} could be compiled to [44,43,45] in the text if you happened to cite Finer:1994kw earlier.

10. You might have to scale the size of your figures to fit nicely on the page

11. You might have to adjust the placement of the code for each figure in the text file to control where the figure shows up in the compiled PDF.  For example, I like my figure to show up just after the text that references it. 

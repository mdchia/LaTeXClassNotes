# LaTeXClassNotes
LaTeX templates for lecture notes.

## Usage
For each course (or single set of notes), copy the "template" folder. Edit the "Settings" portion of the file as desired. 

For each class/note-taking session, make a new copy of the sample listing block. Type as you normally would within the block; tab spaces and newlines are preserved!

To write equations and math symbols, enclose the TeX-formatted math in `$` symbols. To write regular LaTeX codes, enclose them in `~` symbols.

## Example notes block
```
\section*{Lecture title}
\begin{lstlisting}
Main bullet point
	Sub-point
	Some LaTeX command ~\LaTeX~
	Some math $ \frac{1}{2} $
\end{lstlisting}
```
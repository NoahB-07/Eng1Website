
# Group 3.7 Engineering project

This is a regular Markdown description of my repository. Below is the PlantUML diagram rendered natively using LaTeX TikZ.

$
\begin{tikzpicture}[yscale=-1, transform shape]
  % 1. Paste your raw PlantUML TikZ code right here
@startgantt
printscale daily zoom 2
Project starts the 14st of October 2026
[Deadline] requires 32 days
-- Separator --
[Requirements] requires 5 days
[Risk assessment] requires 5 days
Then [Design] requires 1 week
Then [Architecture] requires 1 week
[Implementation] requires 15 day
[Implementation] starts at [Design]'s end
Then [Testing] requires 4 days
Then [Review] requires 1 days
mondays are coloured in Lightblue
wednesdays are coloured in lightBlue
@endgantt
  
  % Example PlantUML TikZ nodes:
  \draw[black,fill=white,shape=rectangle] (0,0) rectangle (2,1) node[pos=.5] {Alice};
  \draw[->,>=black] (2,0.5) -- (5,0.5) node[midway,above] {Hello};
  \draw[black,fill=white,shape=rectangle] (5,0) rectangle (7,1) node[pos=.5] {Bob};
\end{tikzpicture}
$
 
You can continue writing your normal markdown down here after the diagram block.


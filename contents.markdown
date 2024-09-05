\newtcolorbox{examplebox}{ 
  colback=yellow!10!white, 
  colframe=yellow!50!black, 
  title=Exemplo,
}

\newtcolorbox{codebox}{ 
  colback=gray!10!white, 
  colframe=gray!50!black, 
  title=Código de Exemplo
}

\newtcolorbox{attentionbox}{ 
  colback=blue!10!white, 
  colframe=blue!50!black, 
  title=Detalhe importante!
}

\newtcolorbox{todobox}{ 
  colback=green!10!white, 
  colframe=green!50!black, 
  title=Lista de Tarefas
}

\newtcolorbox{exercisebox}{ 
  colback=orange!10!white, 
  colframe=orange!50!black, 
  title=Exercícios
}

\lstset{
  language=Python,
  basicstyle=\ttfamily\footnotesize,
  keywordstyle=\color{blue},
  commentstyle=\color{green!50!black},
  stringstyle=\color{red},
  showstringspaces=false,
  columns=fullflexible,
  keepspaces=true,
}

\lstdefinestyle{CStyle}{
  language=C,
  basicstyle=\ttfamily\footnotesize,
  keywordstyle=\color{blue},
  commentstyle=\color{green!50!black},
  identifierstyle=\color{red!50!black},  
  stringstyle=\color{red},
  showstringspaces=false,
  columns=fullflexible,
  keepspaces=true,  
  morekeywords={printf},
}


\newcolumntype{L}{>{\raggedright\arraybackslash}p{3cm}}

\newlist{todolist}{itemize}{4}
\setlist[todolist]{label=$\square$, left=0pt, labelsep=1em}

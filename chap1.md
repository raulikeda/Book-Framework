\pagebreak
# Capítulo 1

## Seção

Texto aqui

\begin{examplebox}

Exemplo! Pode usar LateX

\end{examplebox}

Outas caixas de texto. Ver contents.markdown para customização.

\begin{attentionbox}
Caixa de Exemplo
\end{examplebox}

### Subseção

Fórmulas normalmente em Markdown:

$$ G = (V, \Sigma, P, S)$$


Figuras (Figura \ref{chap1-fig-ref})

![Exemplo de Figura\label{chap1-fig-ref}](./images/chap1-teste.png){ width=41px }

Código python:

\begin{codebox}
\begin{lstlisting}

print("I want goto!")

\end{lstlisting}
\end{codebox}

Lista de Tarefas

\begin{todobox}
{\footnotesize
\begin{todolist}
  \item Módulo 1
  \begin{todolist}
    \item Tarefa 1
    \item Tarefa 2
  \end{todolist}
  \item Módulo 2
  \begin{todolist}
    \item Submódulo 2.1
    \begin{todolist}
        \item Tarefa X
    \end{todolist}
  \end{todolist}
\end{todolist}
}
\end{todobox}

Rodapé[^chap1-cit]

[^chap1-cit]: Nunca use rodapé para referência bibliográfica convencional.
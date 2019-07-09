# DICAS E TRUQUES LATEX
## Posicionamento de imagem:
Se voce quiser posicionar exatamente no lugar eexato é so usar o pacote "float":
```tex
\usepackage{float}
```
E na imagem voce colocar o atributo "H", conforme o exemplo a baixo:
```tex
\begin{figure}[H]
    \centering
    \includegraphics[scale=0.6]{image.png}
    \caption{image}
    \label{image}
\end{figure}
```
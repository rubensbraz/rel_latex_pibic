# Modelo de Relatório PIBIC - LaTeX

Este repositório contém um modelo não oficial em LaTeX para a elaboração de relatórios finais ou parciais do **Programa Institucional de Bolsas de Iniciação Científica (PIBIC)**.

O template foi desenvolvido para seguir as normas de formatação exigidas, facilitando a escrita de artigos e relatórios técnicos com estrutura acadêmica profissional.

### 📄 Exemplo de Resultado

Você pode visualizar o documento final compilado (com exemplos de texto, tabelas e figuras) no link abaixo:

🔗 **[Visualizar Relatório Compilado (Resultado.pdf)](https://github.com/rubensbraz/rel_latex_pibic/blob/main/Resultado.pdf)**

---

## 🚀 Funcionalidades do Modelo

Este modelo baseado na classe `report` já vem configurado com:

* **Cabeçalho Institucional:** Formatação padrão da UnB/Faculdade de Tecnologia.
* **Margens Configuradas:** Ajustadas para normas acadêmicas (`left=2.8cm`, `right=2.8cm`, `top=4cm`).
* **Suporte a Idioma:** Configurado para Português (Brasil) com hifenização correta (`babel`, `hyphenat`).
* **Elementos Gráficos:** Suporte nativo para imagens, subfiguras (`subfigure`) e legendas personalizadas.
* **Códigos Fonte:** Pacote `listings` incluído para inserir trechos de código de programação no relatório.

## 📂 Estrutura dos Arquivos

* **`script.tex`**: O arquivo mestre do projeto. Contém todo o código LaTeX, estrutura do texto e bibliografia.
* **`Resultado.pdf`**: Arquivo PDF gerado a partir da compilação do script, servindo de referência visual.
* **`imagens/`**: Pasta (necessária criar) onde você deve salvar as figuras (JPG, PNG, PDF) citadas no texto.

## 🛠️ Como Utilizar

### Opção 1: Overleaf (Online)

1.  Faça um cópia do projeto e começe a editar: https://www.overleaf.com/read/zcqpmszdhmwb

### Opção 2: Editor Local (VS Code / TeXShop)

1.  Clone este repositório ou baixe os arquivos.
2.  Certifique-se de ter uma distribuição LaTeX instalada (TeX Live, MiKTeX, etc.).
3.  Abra o arquivo `script.tex` e compile.

## 📝 Editando o Relatório

Para personalizar o relatório com seus dados, edite o início do arquivo `script.tex`:

```latex
% Cabeçalho e Título
\large \textbf{\textsc{Seu Título do Projeto Aqui}}

% Dados do Aluno e Orientador
Aluno: Seu Nome Completo\\
Pesquisador Responsável: Prof. Dr. Nome do Orientador
```

Inserindo Figuras:

```latex
\begin{figure}[ht!]
    \centering
    \includegraphics[width=0.7\linewidth]{imagens/sua_imagem.jpg}
    \caption{Legenda da imagem.}
    \label{fig:exemplo}
\end{figure}
```

## 📄 Licença

Este modelo é de uso livre. Desenvolvido por Rubens Braz.

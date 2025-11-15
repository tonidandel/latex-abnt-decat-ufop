# Template ABNT LaTeX para TCCs  -- DECAT-UFOP

Modelo para Trabalho Final de Curso (TCC) - Departamento de Engenharia de Controle e Automação da Universidade Federal de Ouro Preto (DECAT-UFOP).

O modelo não segue uma aplicação exaustiva das normas, mas algumas de suas possibilidades. Antes de tudo, converse com seu orientador ou orientadora, mostre uma cópia do PDF gerado por este modelo e certifique-se de que não terá problemas futuros com relação à aceitação ou não por meio de uma banca ou comitê de avaliação.

## Instalação e utilização

A última versão (release v25.09) pode ser acessada na aba releases, ou [aqui](https://github.com/tonidandel/latex-abnt-decat-ufop/releases/tag/v25.09-tcc-latex-decat-ufop).

Se tiver alguma dúvida em como usar o modelo, acessar [uma pequena oficina LaTeX.](https://tonidandel.github.io//oficina-latex/).

### **GNU/Linux**:

Basta utilizar o gerenciador de aplicativos da sua distribuição Linux favorita e instalar o pacote `texlive-fulll`,  que é a base sob a qual o sistema funciona e que reune todos os requisitos necessários para a utilização do \LaTeX. Além disso, é necessário o editor, propriamente dito. Uma sugestão é o aplicativo [TexStudio](https://www.texstudio.org/#download).

Se prerefir utilizar um terminal, entre com os comandos abaixo (o sistema irá pedir sua senha de super-usuário depois do primeiro comando):

```
$ sudo apt update && apt install texlive-full && apt install texstudio -s
```

Após isso basta abrir o editor de texto texstudio no seu menu de aplicativos e começar a utilizar o programa.

**Observações:** 

- É recomendável utilizar alguma distribuição do sistema operacional GNU/Linux para rodar o template. 

- Para configurar o editor, utilizar o compiladores LuaLaTeX (para o arquivos fonte ".tex") e Biber (compilação de referências).

### **Windows**:

Há uma distribuição completa disponibilizada pelo TUG (TeX and friends) chamada [TeXLive](https://www.tug.org/texlive/windows.html) para o **"windows"**, que instala o TeXLive (conjunto de pacotes básicos) + o editor [TeXstudio - A LaTeX editor](https://www.texstudio.org/#home) .

**Observações:**

- Para configurar o editor, utilizar o compiladores LuaLaTeX (para o arquivos fonte ".tex") e Biber (compilação de referências).

### **MacOs**:

Há uma distribuição do TexLive para o MacOS, também disponibilizada pelo TUG chamada [MacTeX](https://tug.org/mactex/). Na página é possível encontrar instruções de instalação e download dos programas.

### **Web**:

Uma evolução da computação foi certamente a possibilidade de execução de aplicatitvos em nuvem. Há um sistema completo de desenvolvimento em $\LaTeX$ que pode ser executado totalmente online, chamado **[OverLeaf](https://www.overleaf.com/)**.  

**Mas atenção: embora gratuito, o Overleaf possibilita um número limitado para criação de projetos em \LaTeX. Após algumas compilações, a plataforma começará a apresentar "erros" (o que, na verdade, representam uma obsolescência programada!)** 

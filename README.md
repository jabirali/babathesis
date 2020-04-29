# Thesis template
This is a LaTeX template intended for academic theses, and was put together by
Jabir Ali Ouassou while preparing his PhD dissertation. The template itself is
released under a Creative Commons Attribution licence [CC BY 4.0][1]. This
basically means that you are free to use the template for any purpose as 
long as you give appropriate credit.

The template bundles the [Libertinus fonts][2], which is used for all regular text 
and mathematics, and the [URW Classico][3] fonts, which are used for chapter and 
section headings. The former is available under the Open Font Licence (SIL OFL 1.1),
and is free for both private and commercial use. The latter is available under the 
Aladdin Free Public Licence (AFPL), and is only free for non-commercial use. For 
commercial use, a suitable replacement for URW Classico would be the Libertinus 
Sans fonts, which are also bundled. Note that this template relies on LuaLaTeX 
for e.g. font customization, and on BibTeX for reference handling. For 
command-line users, the easiest way to compile the document is to run 
`latexmk -lualatex thesis.tex`. If using an IDE, please check the program 
settings for how to enable compilation with LuaLaTeX and BibTeX. The 
template is based on the KOMA-Script book class (`scrbook`), so for further 
customization of the template, please check out [their documentation][4].

The template does not include a title page. This is because the style
requirements typically varies between universities, and many institutions
will anyway autogenerate a titlepage upon thesis submission.

[1]: https://creativecommons.org/licenses/by/4.0/
[2]: https://github.com/libertinus-fonts/libertinus
[3]: https://ctan.org/tex-archive/fonts/urw/classico
[4]: https://ctan.org/pkg/koma-script.

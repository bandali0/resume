# Resume

The source code of my professional resume, based on Steven
Hair's [blog post][stevenhair] on typesetting resumes according to Matthew
Butterick's [Practical Typography resumes][mbresumes].

You'll need XeTeX since I'm using [fontspec][fontspec] for typesetting the
beautiful [Calluna][calluna] and [Calluna Sans][callunasans] typefaces by Jos
Buivenga.

Use `xelatex resume.tex` to generate the PDF. Or alternatively,
use `latexmk -pvc -xelatex resume.tex` to preview and automatically re-compile
when saving changes.

## License

The source code is licensed under the LaTeX Project Public License, either
version 1.3 of this license or (at your option) any later version.
See [LICENSE](LICENSE).

[stevenhair]: http://stevenhair.com/blog/2014/2/11/buttericks-practical-typography-and-xelatex-resumes/
[mbresumes]: http://practicaltypography.com/resumes.html
[fontspec]: https://www.ctan.org/pkg/fontspec?lang=en
[calluna]: http://www.exljbris.com/calluna.html
[callunasans]: http://www.exljbris.com/callunasans.html

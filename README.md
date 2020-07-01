# How to Write Your Resume in LaTeX
A step-by-step guide to creating your very own LaTeX resume.

## You've probably heard of LaTeX...
LaTeX *(pronounced "lay-tech" or "lah-tech")* is a collection of TeX macros, written by Leslie Lamport, that run on top of the TeX typesetting system created by Donald Knuth.

To learn more about the history of LaTeX, check out [this Wikipedia article](https://en.wikipedia.org/wiki/LaTeX).

The major benefit that you get from working with LaTeX compared to other word processing systems is that you can separate the content of your document from its style and format. This allows you to think clearly about logical subdivisions in the content rather than convoluting the meaning of your writing with aesthetics and layout. The process is similar to laying out an HTML document and editing the style with CSS.

## 5 Steps to Your New LaTeX Resume
1. Head over to [latex-project.org](https://www.latex-project.org/get/) and download the correct distribution for your operating system. 
*If you prefer not to download anything, you can work completely online at [Overleaf.com](https://www.overleaf.com/).*
2. Read as much of the documentation as you need to get familiar enough with the language to understand and manipulate one of the default templates. Start with the **Read Me First** document that comes with your distribution. It should show you how to create your first .tex file. You'll probably end up Googling a whole bunch of macros and keywords from there. There is also a .pdf file for \*every package out there, and many of them are included with your download. Or, you can find additional packages and documentation online at the [CTAN: Comprehensive TeX Archive Network](https://ctan.org/).
3. Work from a quality text editor, like Visual Studio Code. This was my preference compared to the MacOS version of TeXShop I downloaded. There are probably other tools that work just as well. Whatever you choose, use something that you are familiar with and that provides decent syntax highlighting. By doing this, you can learn the language without getting hung up on the particulars of the development environment.
4. Write down your content. Decide what you want to include on your resume. Usually, you'll want about five major sections for your resume.
    * Contact Information
    * Education
    * Skills
    * Professional Experience
    * Projects
5. Refine the style and layout of your content. Like, HTML and CSS, you can add the style into a separate file with a .cls extension, add style to a header-like section before the \begin{document} macro, or add style adjustments inline.

Take a look at [my example](Resume.tex), and feel free to copy it, use it, and modify it however you want. It's not perfect, but it should provide you with a decent starting point.

--------------------------------------------------------------
\* I have yet to find a package that doesn't have some kind of .pdf with all the documentation you'll need to use it.

#### Thank you Clément
You inspired me to pursue this project by mentioning it [in one of your YouTube Videos](https://youtu.be/aKjsy-b00QM).

#### Thank you Logan
You helped me take the first steps with your article, ["Why I write my resume in LaTeX"](https://loganmarchione.com/2019/03/why-i-write-my-resume-in-latex/).
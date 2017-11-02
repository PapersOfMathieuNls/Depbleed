# Combined

## ICSE 2018 - Demonstrations

A demonstration submission may not exceed four pages (including all text, references and figures). Each submission MUST be accompanied by a short video (between three and five minutes long) illustrating the demonstration. The video should be made available online at the time of submission. Videos should (i) provide an overview of the tool’s capabilities and/or dataset characteristics; (ii) walk through (some of) the tool capabilities and/or data analysis process; (iii) where appropriate, provide clarifying voice-over and/or annotation highlights; and (iv) be engaging and exciting for the watcher! A submission may not have been previously published in a demonstration form. The paper submission must be in PDF.

Papers must be submitted electronically through EasyChair submission page by November 20, 2017. (The submission webpage will be opened 3 months before the submission deadline).

At the end of the abstract, please append the URL at which your demo video can be found. Please note that for consistency, we require that ALL videos be uploaded to YouTube and made accessible during the time of reviewing. Authors of successful submissions will have the opportunity to revise both the paper and the video (and its hosting location) by the camera-ready deadline.

For examples of previously successful short videos, please see the examples from ICSE 2016 demo: https://www.youtube.com/playlist?list=PLv2z5tdv5mKzXeyzegBq6YONhwBNqeeMY

Important Dates

- Submission deadline: November 20, 2017
- Notification deadline: January 22, 2018
- Camera ready copy: February 12, 2018

## Collaborate

Edit the bianca.md file using whichever text editor you want (Vim, Sublime, Word).
You can even edit it online, directly on github: https://github.com/PapersOfMathieuNls/depbleed/edit/master/depbleed.md

The only thing that matters is to save it in text format.

## Build the pdf

The pdf generation is based on [Pandoc](http://pandoc.org/). Pandoc transforms the markdown to latex and then, to pdf.
Here's the command, assuming pandoc, latex, pandoc-citeproc and pdf-latex are installed on your system and that you are on the Depbleed directory :

```bash
./build.sh
```

A docker container is available with all the tools you need installed at : https://hub.docker.com/r/mathieunls/latex/

```bash
docker pull mathieunls/latex
docker run -dit -v /path/to/local_depbleed:/mnt/depbleed --name latex
docker attach latex
cd /mnt/depbleed
./build.sh
```
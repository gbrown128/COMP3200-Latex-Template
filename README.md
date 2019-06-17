# COMP3200 Latex Report Template


I've compiled it on a Linux machine using the 2017, 2018, and 2019 distributions
of texlive and it works fine.

If you're on Linux, the following command may be useful for compiling the report:
`latexmk -pvc -pdf -jobname=output/report report.tex`
(You'll need to `mkdir output` first!)

That command should continue to fully compile the report as you write it, and
show a preview in your system PDF viewer. I use Evince, which automatically
reloads the PDF as it is updated, and usually doesn't crash when that happens.

Users may also like `texcount` for word counting. It does a pretty good job at
word counting without all of the headings. I received the guidance that the
report word count was not super strict, and "as long as your below the limit with
your counting tool then it's ok". Of course check with your supervisor!

If you don't fancy setting up and maintaining a texlive distribution on your
machine, or aren't using Linux, then [Overleaf](https://www.overleaf.com/) has
been widely recommended to me by peers for preparing latex documents. I've found
it to be mostly acceptable, if a little slow at times.

# Licensing

I've done my best to make this compliant with the relevant university standards
at the time I wrote this template for my own degree (2018).

This template is available for all to freely use, under no licence and is
provided without warranty. To my knowledge there's nothing here to violate
academic integrity rules, but all responsibility is left to the user.


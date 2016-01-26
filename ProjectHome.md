As you work your way up the learning curve of CCD photometry one of the later refinements is to develop transform coefficients for your telescope/filter/CCD camera setup. There are several references from the AAVSO website on how to do this and I’ve included some of them below. Once you have your coefficients you need to apply them to your observations. This can be a confusing process and usually involves transcribing your data to various spreadsheets. I offer here an application that is meant to make that process of applying your coefficients simple, consistent and easily traceable.

There is lots of discussion on how exactly you should apply your coefficients. Starting from the AAVSO website you have the article by Benson, Priscilla. "CCD Transformation Coefficients" , AAVSO Information Sheet, www.aavso.org, 1993. ( http://www.aavso.org/sites/default/files/benson.pdf )

And then Lou Cohen’s article tries to explain it further and correct minor errors : Cohen, Lou. "Computing and Using CCD Transformation Coefficients", AAVSO Information Sheet, www.aavso.org, 2002.  ( http://www.aavso.org/sites/default/files/ccdcoeff.pdf )

I’ve found Bruce Gary’s webpage lays it out even clearer, at least for me, as it also extrapolates the technique to various filter combinations: CCD TRANSFORMATION EQUATIONS FOR USE WITH SINGLE IMAGE (DIFFERENTIAL) PHOTOMETRY . ( http://reductionism.net.seanic.net/CCD_TE/cte.html )

The TransformApplier application offers the above transform equations as well as a set that is recommended and preferred by the AAVSO.

The process I have in TransformApplier is to take the file with your untransformed observations and have the Transformer application scan it and rewrite it with the transformed observations. Care is taken to include in the output file comments fully describing the process applied to the data.


The application is a Windows app written with Borland BCB5. Please download and try it. If there are problems or errors, do email me and I will get them fixed straight away. If you would, please send me your input file so I can see what went wrong.

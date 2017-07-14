gao: resume_chen_gang.pdf rev_resume_chen_gang.pdf
	echo 'ft'

resume_chen_gang.pdf:  english_resume_chen_gang.pdf chinese_resume_chen_gang.pdf 
	pdfunite english_resume_chen_gang.pdf chinese_resume_chen_gang.pdf resume_chen_gang.pdf
	open resume_chen_gang.pdf

rev_resume_chen_gang.pdf:  english_resume_chen_gang.pdf chinese_resume_chen_gang.pdf
	pdfunite  chinese_resume_chen_gang.pdf english_resume_chen_gang.pdf rev_resume_chen_gang.pdf
	open rev_resume_chen_gang.pdf


english_resume_chen_gang.pdf: english_resume_chen_gang.tex
	xelatex english_resume_chen_gang.tex

chinese_resume_chen_gang.pdf: chinese_resume_chen_gang.tex
	xelatex chinese_resume_chen_gang.tex

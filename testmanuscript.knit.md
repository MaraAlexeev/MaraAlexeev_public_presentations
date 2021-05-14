---
title: '**Title of Your Submission**'
author:
- Jane Doe, MD, MPH:
    email: example@example.com
    institute: institute_1
- name: John Doe, MD, MBI
  institute: institute_2
institute:
- institute_1: Institution, City, State, Country
- institute_2: Institution, City, State, Country
output:
  bookdown::pdf_document2:
    keep_tex: yes
    toc: no
    number_sections: no
    pandoc_args:
    - --lua-filter=scholarly-metadata.lua
    - --lua-filter=author-info-blocks.lua
  pdf_document2: default
csl: vancouver-superscript.csl
link-citations: yes
bibliography: CIC_example.bib
---



## What might the attendee be able to do after being in your session?

This section should describe what the attendee might be able to do with the knowledge you are sharing. “Clinical” is part of this meeting’s name, and “Best Practices” is a pillar of the AMIA 2020 Clinical Informatics Conference. This short statement of 1 - 2 sentences is your opportunity to tell attendees the practical implications of your findings on what clinical informaticians do, or on patient/population outcomes

## Description of the Problem or Gap

Define the problem or gap here. EG, what HIT tool is poorly designed, or non-existent, or creating barriers to better clinician performance or patient/population outcomes?

Please use this format for reference citations[@pryor_help_1983; @gardner_computer-critiqued_1990].

## Methods: What did you do to address the problem or gap?

This text uses a paragraph to describe methods. 

## Results: What was the outcome(s) of what you did to address the problem or gap?

This is a write-up of your results.

Use the examples below if you will include a figure or a table. Figures \@ref(fig:nice-fig) need to be placed as close to the corresponding text as possible and not extend beyond one page.

\begin{figure}

{\centering \includegraphics[width=0.8\linewidth]{testmanuscript_files/figure-latex/nice-fig-1} 

}

\caption{Here is a nice figure!}(\#fig:nice-fig)
\end{figure}

This paragraph contains a reference to Table \@ref(tab:nice-tab) just below. This table contains information on word and page limits per meeting format submission abstract. All tables need to be placed as close to the corresponding text as possible, but each individual table should be on one page and not extend to multiple pages unless labeled as “Continued.”

\begin{table}

\caption{(\#tab:nice-tab)Submission type, abstract length, and page length maximum for AMIA submissions.}
\centering
\begin{tabular}[t]{lll}
\toprule
Submission Type & Abstract Length* & Page Length Maximum**\\
\midrule
Workshop & 250-300 words & Four\\
Presentation & 50-75 words & Two***\\
Panel & 150-200 words & Three\\
Poster & 50-75 words & One\\
Ignite-style Talk & 50-75 words & One\\
\bottomrule
\multicolumn{3}{l}{\rule{0pt}{1em}\textit{Note: }}\\
\multicolumn{3}{l}{\rule{0pt}{1em}Here is a general comments of the table. }\\
\multicolumn{3}{l}{\rule{0pt}{1em}\textsuperscript{1} Footnote 1; }\\
\multicolumn{3}{l}{\rule{0pt}{1em}\textsuperscript{2} Footnote 2; }\\
\multicolumn{3}{l}{\rule{0pt}{1em}\textsuperscript{a} Footnote A; }\\
\multicolumn{3}{l}{\rule{0pt}{1em}\textsuperscript{b} Footnote B; }\\
\multicolumn{3}{l}{\rule{0pt}{1em}\textsuperscript{*} Footnote Symbol 1; }\\
\multicolumn{3}{l}{\rule{0pt}{1em}\textsuperscript{\dag} Footnote Symbol 2}\\
\end{tabular}
\end{table}

## Discussion of Results

This text uses a paragraph to describe important findings of the project. This text uses a paragraph to describe important findings of the project. This text uses a paragraph to describe important findings of the project. This text uses a paragraph to describe important findings of the project.

## Conclusion

Your conclusion goes at the end, followed first by Attendee’s Take-away Tool, then followed by References, which must follow the [Vancouver Style](http://www.citethisforme.com/). 

## Attendee’s Take-away Tool

This text describes the take-away tool. This may be a strategy, an algorithm, an app, etc. The “tool” is what the attendee can use to reproduce your study in his/her own practice setting. The presenter may use an illustration to depict the tool on the 2nd page of the submission abstract.

## Use of Knowledge Acquired at Previous AMIA Events

Did something you learned at a previous AMIA event contribute to your awareness of the problem or to the solution or strategy you describe in this submission? If so, mention it here. This section may go over to an additional page and will not be counted against you if you have this as an extra page in the page count.

Roses are \textcolor{red}{red}, violets are \textcolor{blue}{blue}.

## References


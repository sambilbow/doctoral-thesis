<div align="right">
<b>

A DOCTORAL THESIS IN MUSIC TECHNOLOGIES BY SAM BILBOW (12/2022)

UNIVERSITY OF SUSSEX, FALMER, EAST SUSSEX, BN1 9RG

SCHOOL OF MEDIA, ARTS AND HUMANITIES

DEPARTMENT OF MUSIC

</b>
</div>

## Material, Embodied, and Spatial Relations in Augmented Reality

**An Exploration of AR as a Medium for Musical Performance and Experience**



### Thesis Summary
It has been thirty years since the original definition of augmented reality (AR) as a technology used to ‘augment the visual field of a user with information necessary in the performance of tasks’. In this first instance, it was developed with the purpose to ‘improve the efficiency and quality of human workers in their performance of manufacturing activities’ ([Caudell and Mizell, 1992](https://doi.org/10.1109/HICSS.1992.183317)). Alongside subsequent decades of funding from the US military-industrial complex, we have also seen the uptake and reappropriation of AR in creative fields, such as computational art, performance, design, and entertainment - these works often proposing do-it-yourself (DIY) and open-source approaches to their design. Despite these developments, AR within sound-driven forms of art have been relatively under-explored. If an AR system can be thought of as one that can combine real and virtual multisensory processes, is interactive in real-time, and is registered in three dimensions ([Azuma, 1997](https://doi.org/10.1162/pres.1997.6.4.355)); why do we, thirty years on, witness the paradigmatic form of AR still being heavily biased ([Billinghurst et al., 2015](https://doi.org/10.1561/1100000049)) towards it being a method of visual information overlay? 

Standing in stark contrast to the currently unfolding and hyper-commercialised view of AR – as defined by the corporate ‘Metaverse’ – this thesis resituates AR as an artistic medium for the creation of interactive and expressive works by musicians and sound artists. It is guided primarily by the questions: ‘What are AR’s affordances as an artistic medium, what is the resultant experience for participants and audiences (or ‘immersants’) in these experiences, and what might a future corpus of AR digital music instruments look, sound, and feel like?’ 

To address these questions, this practice-based piece of research takes a DIY Approach to Sound ARt, arguing that, as an medium that combines real and virtual multisensory processes, it must explored with a sensory-process agnostic approach – that is, to approach AR as more than mere visual information overlay – instead as ‘real-time computationally mediated perception’ ([Chevalier and Kiefer, 2020](https://dx.doi.org/10.1162/leon_a_01740)). This has involved making and hacking technology as an necessary aesthetic and political stance against commercial AR technologies in their typical form. 

Three sound augmented reality art (ARt) experiences are outlined, and embody the majority of the practical contribution of this thesis: [area~](https://www.github.com/sambilbow/area), [polaris~](https://www.github.com/sambilbow/polaris), and [polygons~](https://www.github.com/sambilbow/polygons). In discussing the results of these three study chapters, theoretical propositions are made: ‘augmented materiality’, ‘augmented embodiment’, and ‘augmented space’, that have implications for the use of AR as a sonic medium. Moreover, out of the iterated design of the AR experiences, their study, evaluation, and discussion, [three ‘design guidelines'](https://sambilbow.github.io/thexrtspace/design-patterns/) for those in the field interested in reproducing or developing similar sound ARt have been developed: Designing for Rich AR Experience, Consideration of the AR Instrument, and Role of the Virtual in the AR Environment.

---
### Bibliography
- Azuma, R. (1997) ‘A Survey of Augmented Reality’, *Presence: Teleoperators and Virtual Environments*, **6**(4), pp. 355–385. Available at: https://doi.org/10.1162/pres.1997.6.4.355
- Billinghurst, M., Clark, A. and Lee, G. (2015) ‘A Survey of Augmented Reality’, *Foundations and Trends® in Human–Computer Interaction*, **8**(2–3), pp. 73–227. Available at: https://doi.org/10.1561/1100000049
- Caudell, T. and Mizell, D. (1992) ‘Augmented reality: an application of heads-up display technology to manual manufacturing processes’, *in* Proceedings of the Twenty-Fifth Hawaii International Conference on System Sciences. Proceedings of the Twenty-Fifth Hawaii International Conference on System Sciences, Kauai, HI, USA: IEEE, pp. 659–669 vol.2. Available at: https://doi.org/10.1109/HICSS.1992.183317
- Chevalier, C. and Kiefer, C. (2020) ‘What Does Augmented Reality Mean as a Medium of Expression for Computational Artists?’, *Leonardo*, **53**(3), pp. 263–267. Available at: https://doi.org/10.1162/leon_a_01740
---
### Publications and Texts
The following publications and texts are drawn from in parts of this thesis: 

#### Chapter 3: Aesthetic Experience, Complex Music Systems, and the Metaverse

(Bilbow et al., 2021) 
- Bilbow, S., Kiefer, C. and Chevalier, C. (2021), The Value of Sound within a Multisensory Approach to AR in the Arts, *in* ‘Proceedings of the Multisensory Augmented Reality Workshop’, Interact, Italy, p. 8. Available at: https://doi.org/10.5281/zenodo.7421488 

#### Chapter 4: A DIY Approach to AR in the Sonic Arts 

(Bilbow, 2020b, 2021b) 
- Bilbow, S. (2020), ‘Impact on human perception and expression, using augmented reality technology as a medium for computational art’, in ‘Internal Research Proposal’ Available at: https://doi.org/10.5281/zenodo.7421529 
- Bilbow, S. (2021b), Developing Multisensory Augmented Reality As A Medium For Computational Artists, *in* ‘Proceedings of the Fifteenth International Conference on Tangible, Embedded, and Embodied Interaction’, ACM, Salzburg Austria, pp. 1-7. Available at: https://doi.org/10.1145/3430524.3443690 

#### Chapter 5: Composing area~ 

(Bilbow, 2021a) 
- Bilbow, S. (2021a), ‘The area~ system: Exploring real and virtual environments through gestural ambisonics and audio augmented reality’, *Sonic Scope: New Approaches to Audiovisual Culture* **2**. Available at: https://doi.org/10.21428/66f840a4.b74711a8 

#### Chapter 6: Evaluating polaris~ 

(Bilbow, 2022a) 
- Bilbow, S. (2022), Evaluating polaris~ - An Audiovisual Augmented Reality Experience Built on Open-Source Hardware and Software, *in* ‘NIME 2022’, New Interfaces for Musical Expression PubPub, The University of Auckland, New Zealand. Available at: https://doi.org/10.21428/92fbeb44.8abb9ce6
---
### LaTeX Compilation
1. Install Java for `bib2gls` (e.g. via `asdf`)
2. Correctly configure %OUTDIR% with pdftex, bibtex, bib2gls and latex-workshop (VSCode) if using.
    ```
    "latex-workshop.latex.tools": [
        {
            "name": "pdflatex",
            "command": "pdflatex",
            "env": {},
            "args": [
                "-synctex=1",
                "-interaction=nonstopmode",
                "-file-line-error",
                                //* make pdftex use modified outdir
                "-output-dir=%OUTDIR%",
                "%DOC%"
            ],
        },
        {
            "name": "bibtex",
            "command": "bibtex",
            "env": {},
            "args": [
                                //* make bibtex look for modified outdir
                                //! had to change to `openout_any = a` in /usr/share/texmf-dist/web2c/texmf.cnf
                                //* .bbl not counted by texcount currently
                "%OUTDIR%/%DOCFILE%"
            ]
        },
        {
            "name": "bib2gls",
            "command": "bib2gls",
            "args": [
                                // *make pdftex use modified outdir
                "-d",           // *chdir
                "%OUTDIR%",     // *aux dir
                "%DOCFILE%"     // *file name
            ]
        }
    ]
    ```
3. Build with pdftex -> bibtex -> bib2gls -> pdftex -> pdftex using LaTeX Workshop
   ```
    {
        "name": "pdfLaTeX -> bibTeX -> bib2gls -> pdfLaTeX x2",
        "tools": [
            "pdflatex",
            "bibtex",
            "bib2gls",
            "pdflatex",
            "pdflatex"
        ]
    }
    ```
4. Pre-compiled .pdf can be found [here](https://github.com/sambilbow/doctoral-thesis/blob/main/build/doctoral-thesis.pdf)

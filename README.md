# misaligned_circumbinary_planets
circumbinary.ipynb and circumbinary_unfiltered.ipynb generates and evolves a population of circumbinary planets. They pull out stellar masses from the masses.xlsx file, which is an excel spreadsheet containing stellar masses of Kepler targets.

circumbinary.ipynb outputs observable subsequences (with length equal to one Kepler window, 4.35 years) of the generated and evolved circumbinary planets.
circumbinary_unfiltered.ipynb outputs the raw transits per epoch sequences (without dividing into subsequences and filtering for observability) obtained directly from evolving the generated circumbinary planets.

The data of different populations.rar file contains the data (transit counts per epoch, # of epoches in one Kepler window, and inclination of binary orbit) we obtained from evolving circumbinary populations with different inclination distributions. 

The data of unfiltered sequences.rar file contains examples of the raw transits per epoch sequences (without dividing into subsequences and filtering for observability) obtained directly from evolving the generated circumbinary planets.

Case A-D.ipynb contains code on how we dealt with the data (transit per epoch sequences) generated from the circumbinary populations in each of the 4 possible scenarios (as discussed in Section 2.8 of our paper).

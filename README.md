# nsn...
Scattering properties and signatures of entanglement in composite normal & superconducting nanowires (https://www.sciencedirect.com/science/article/abs/pii/S0921452621007493)

Required software:<br />
-Mathematica12.0 (or greater)<br />

scattering_matrix_arbitrary_number_of_segments<br />
-software used to compute the scattering matrix of a nanowire with an arbitrary number of normal and super conducting segments<br />

deliverables<br />
-Entanglement in normal & super - conducting nanowires was used as part of the qualifying exam in UT Austin<br />

within nsnsnsnsn:<br />
-NSNSNSNSN_Smatrix_from_Tmatrix.mx is the scattering matrix for this nanowire (4 superconducing segments, 5 normal segments)<br />

--main programs<br />
---(hh,pp,ph)_shot_noise_contributions compute the shot noise due to (holes and holes, particles and particles, particles and holes) coming out of the outer normal leads<br />
---terms_in_shot_noise_with_highest_contribution.nb is used to find terms in shot noise expressions with highest numerical contributions for certain energies<br />

--results<br />
---contains data obtained from (hh,pp,ph)_shot_noise_contributions programs<br />

--visualization_of_results<br />
---shot_noise_contributions_and_smatrix_poles.nb contains plots of the three contributions of shot noise as well as the total shot noise. It also includes the pole structure of certain scattering amplitudes<br />
---pole_structure_of_terms_in_shot_noise_with_highest_contribution.nb contains the pole structure of terms in shot noise expressions with highest numerical contributions at certain energies<br />


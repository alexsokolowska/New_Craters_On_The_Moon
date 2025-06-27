# New Craters On The Moon

This is a repository that clones the Zenodo dataset 'Dataset for "Open-sourcing a reconstructed catalog of new impacts on the Moon"' with the intent of providing continuity in cataloging new impacts on the Moon.

New impacts on the Moon are defined as impact sites of meteoroids with the surface of the Moon which occur in the period of spacecraft observation and can be time-constrained because the before-impact and after-impact images exist.

### Table of contents

- Summary
- Data description
- How to reuse and cite
- References
- Acknowledgements

### Summary

This dataset contains  85 locations of sites where meteoroids impacted the lunar surface before 2016, including:

- 69 craters reconstructed from Speyerer et al. 2016 
- 8 new craters from Oberst et al. 2012 and Robinson et al. 2015
- 7 impact splotches

Details of how we obtained this data can be found in Sokołowska et al. 2025, PCC (see reference below).

### Data description
| Filename    | Description | Columns    | 
| -------- | -------- | ------------------------ |
| Sokolowska_etal_2025_PCC_snapshots.pdf | 	This file contains thumbnails of all 69 craters that we reconstructed from Speyerer et al. (2016), as well as of 7 impact splotches. These are screenshots of the Quickmap tool (see ref).	Numbers in each row correspond to the IDs in Sokolowska_etal_2025_PCC-Craters.csv and Sokolowska_etal_2025_PCC-Splotches.csv.  | -------- |
| Sokolowska_etal_2025_PCC-Craters-Not-Found.csv | Contains approximate locations of craters where we were not able to find new craters (see Sokolowska et al. 2025 PCC). | Crater ID: identifier (arbitrary) <br> approximate latitude: latitude in degrees <br> approximate longitude: longitude in degrees <br> Comment: LROC NAC pairs we identified as locations of those craters, those are image IDs |
| Sokolowska_etal_2025_PCC-Craters.csv| Contains exact locations of new craters, as well as their formation times, diameters, and image IDs. | Crater ID: identifier, 1-69 reconstructed, Lit1-8 come from literature <br> measured diameter: crater diameter in meters <br> exact lat/lon: in degrees <br> coords from image ID: image ID in which exact lat/lon should point directly to the crater in Quickmap <br> Latest before ID: latest image where the crater was absent <br> Earliest after ID: earliest image where crater was present <br> formed after: date of Latest before ID image <br> formed before: date of Earliest after ID image <br> Comment: denotes images that did not come from LROC NAC |
| Sokolowska_etal_2025_PCC-Splotches.csv | Contains exact locations of new impact splotches, and image IDs. | <br>  Impact Splotch ID: identifier (matches _PCC_snapshots.pdf) <br>  exact lat/lon: coordinates in degrees <br>  before/after image ID: LROC NAC image IDs before/after formation of the splotch, not necessarily the tightest constraint |


### How to reuse & cite

When using this data, please cite the PCC abstract (Sokołowska et al. 2025 PCC), this dataset on Zenodo, as well as the original papers (Speyerer et al. 2016, Robinson et al. 2015, Oberst et al. 2012). If you find more new craters on the Moon, please also consider making a pull request on this GitHub page after expanding this list for the mutual benefit of the lunar community.

### References

Original Zenodo dataset: Sokolowska, A. (2025). Dataset for "Open-sourcing a reconstructed catalog of new impacts on the Moon" (https://github.com/alexsokolowska/New_Craters_On_The_Moon) [Data set]. Open-sourcing a reconstructed catalog of new impacts on the Moon (16th Planetary Crater Consortium), Flagstaff, Arizona / Hybrid. Zenodo. https://doi.org/10.5281/zenodo.15755155

Sokołowska, A.,  Bernstein-Schalet, J., Khan, S., Daubar, I., Rajsic, A., Gao, T. OPEN-SOURCING A RECONSTRUCTED CATALOG OF NEW IMPACTS ON THE MOON, 16th Planetary Crater Consortium (2025) https://www.hou.usra.edu/meetings/crater2025/abstracts/

Speyerer, E., Povilaitis, R., Robinson, M. et al. Quantifying crater production and regolith overturn on the Moon with temporal imaging. Nature 538, 215–218 (2016). https://doi.org/10.1038/nature19829

Robinson, M., Boyd, A., Denevi, B.,  Lawrence, S., McEwen, A., Moser, D., Povilaitis, R., Stelling, R., Suggs, R.,  Thompson, S., Wagner, R., 
New crater on the Moon and a swarm of secondaries, Icarus,Volume 252, 2015, Pages 229-235, ISSN 0019-1035, https://doi.org/10.1016/j.icarus.2015.01.019.

Oberst, J., Christou, A.A., Suggs, R., Moser, D., Daubar, I.J., McEwen, A.S., Burchell, M.J., Kawamura, T., Hiesinger, H., Wünnemann, K., Wagner, R., Robinson, M.S., 2012. The present-day flux of large meteoroids on the lunar surface—A synthesis of models and observational techniques. Planetary and Space Science 74, 179–193. https://doi.org/10.1016/j.pss.2012.10.005

Quickmap tool: http://quickmap.lroc.asu.edu/

###  Acknowledgements

We acknowledge funding support from NASA SSERVI LunaSCOPE and NASA grant 80NSSC20K0789. We also thank researchers on whose work we were building when compiling this dataset (and those who plan to append more craters to this list).

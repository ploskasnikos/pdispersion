# pdispersion
Library of benchmark instances for the p-dispersion problem with distance constraints. The problems under this repository are used in the following paper:

Ploskas, N., Stergiou, K., & Tsouros, D. C. (2023). The p-Dispersion Problem with Distance Constraints. In 29th International Conference on Principles and Practice of Constraint Programming (CP 2023). Schloss-Dagstuhl-Leibniz Zentrum für Informatik.

Please cite the above papers if you use the instances.

The repository includes the following instances in separate folders:
- RANDOM: randomly generated instances with a desired number of facilities and location points
- MDPLIB: instances taken from the MDPLIB as basis and then adding distance constraints.

The files have the following format:
- The first line includes the number of facilities (n) and p
- The next $`\sum\limits_{i=1}^{n-1} n - i`$ lines include the distances between each pair of facilities.
- The next $`\sum\limits_{i=1}^{p-1} p - i`$ lines include the distances between each pair of facility sites.

# ASP_Project

This is a class project for `Applied Stochastic Process`. The author is _Jiahao Yu_ and _Sun Bo_ from PHBS 2020 class. Our instructor is _Prof. Jaehyuk Choi_.

This project mainly recover the works of: 

[1] Capriotti, L., Jiang, Y., & Shaimerdenova, G. (2019). Approximation methods for inhomogeneous geometric Brownian motion.  𝐼𝑛𝑡𝑒𝑟𝑛𝑎𝑡𝑖𝑜𝑛𝑎𝑙 𝐽𝑜𝑢𝑟𝑛𝑎𝑙 𝑜𝑓 𝑇ℎ𝑒𝑜𝑟𝑒𝑡𝑖𝑐𝑎𝑙 𝑎𝑛𝑑 𝐴𝑝𝑝𝑙𝑖𝑒𝑑 𝐹𝑖𝑛𝑎𝑛𝑐𝑒 ,  22 (02), 1850055.

[2] Tubikanec I, Tamborrino M, Lansky P, et al. Qualitative properties of numerical methods for the inhomogeneous geometric Brownian motion[J]. arXiv preprint arXiv:2003.10193, 2020.

These two papers are included in this repository as "Approximation methods for inhomogeneous geometric brownian motion.pdf" and "QualitativeIGBM.pdf".

Moreover, we modify PyFENG package (also included in the repository as a reference) to add two classes in garch_2.py:

**GarchMcTubikanec2020** and **GarchCapriotti2018**

This two classes can help us price options under Garch Diffusion Model and are more advanced than previous method (e.g. Milstein scheme).
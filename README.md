# TICOG2023
Taiwan International Conference on Ocean Governance

## Developing a Low-Cost Microplastic Screening Station using Homemade Microfluidic Devices and Computer Vision for STEM Education in Secondary Schools

**Authors**  
Syuan Chen Wong¹, Daniel Gau², Yuki Shibata³, Jadon Alexander Tang⁴, Tiffany Gau⁵, Shan Yin Tsai*  
¹ Grade 8 Student, Morrison Academy Kaohsiung  
² Grade 9 Student, Kaohsiung American School  
³ Grade 8 Student, Morrison Academy Kaohsiung  
⁴ Grade 8 Student, Morrison Academy Kaohsiung  
⁵ Grade 7 Student, Kaohsiung American School  
*Associate Director, Pathology Department, An Nan Hospital, China Medical University, Tainan, Taiwan.  

---

## Abstract

Taiwan is a maritime nation that has relied on marine resources for its development throughout its history. To achieve sustainable development in this country, marine science education is increasingly important. However, the integration of STEM education into this topic is rarely applied in secondary schools due to a lack of availability of laboratory-level equipment. 

Microplastic pollution is a pressing environmental issue, and detecting microplastics in the marine environment is essential for developing effective strategies to mitigate this problem. However, existing detection tools are limited in terms of accessibility and convenience, while high equipment costs also restrict research in secondary school-level academia.

To address these challenges, we modified kitchen-based equipment to create a low-cost and user-friendly microplastic screening station using homemade microfluidic devices and computer imaging algorithms. In our preliminary results, we evaluated the reaction time for microplastic staining and compared it to conventional staining techniques. Our fabricated device provides an alternative method for detecting microplastics that is more standardized and automatic.

This study has important implications for STEM education, as it provides an accessible direction for undergraduate students in biotechnology research and extends their research field to an advanced level. By offering a low-cost and user-friendly screening method, our study can also help promote research on microplastic pollution in a broader range of academic settings.

**Keywords:** computer vision, education, homemade, microplastic, microfluidic, STEM.

---

## Introduction

Microplastic pollution is a global problem that significantly impacts marine ecosystems, including those in Taiwan. Taiwan, being an island nation, is particularly vulnerable to plastic waste, with an estimated 15,000 tons of plastic waste entering its oceans every year (Greenpeace East Asia, 2022). 

Microplastics are small plastic particles that accumulate in the environment from various sources such as industrial effluents and ocean debris (Geyer et al., 2017). Traditional detection methods—such as FTIR, Raman spectroscopy, and SEM—are expensive and require expertise, making them unsuitable for secondary school education.

Microfluidic devices and computer vision technology offer cost-effective, accessible alternatives. Homemade PDMS-based microfluidic devices can replace expensive laboratory equipment, while computer vision automates detection and classification through image analysis. This combination allows for effective detection of microplastics at a low cost, making marine science education more inclusive and practical.

---

## Methodology

### Microfluidic Chip Fabrication
Soft lithography was used to create PDMS microfluidic chips with zigzag and serpentine channels. The molds were 3D-printed and cured in a modified toaster oven at 80°C. Argon plasma bonding was performed using a custom-built microwave-based plasma treater.

### Sample Preparation
Polyethylene microplastics were ground, sieved, and mixed with reverse osmosis (RO) water. Control samples contained only RO water.

### Nile Red Staining
A 1 mg/mL Nile Red solution in methanol was diluted 50× for staining microplastic samples.

### Conventional Staining
Microplastic and dye solutions were heated to 80°C for 5, 15, and 20 minutes.

### Microfluidic Reactor Staining
The same staining process was conducted inside the PDMS microchannel at controlled flow rates (0.05–0.025 mL/min).

### Computer Vision Analysis
Fluorescent images were captured using a USB microscope and analyzed using Python-based image processing. The algorithm isolated the red fluorescence channel to count stained particles automatically.

---

## Results

| Staining Method | Time | Particle Count |
|-----------------|------|----------------|
| Control | — | 0 |
| Conventional | 5 min | 6 |
| Conventional | 15 min | 14 |
| Conventional | 20 min | 13 |
| Microfluidic | 5 min | 4 |
| Microfluidic | 15 min | 12 |
| Microfluidic | 20 min | 16 |

**Observation:** The microfluidic system achieved similar or better staining efficiency at controlled flow rates, showing enhanced mixing and reaction dynamics.

---

## Discussion

Marine science education in Taiwan faces equipment and cost barriers that limit student engagement in practical experiments. This project demonstrates that with simple household tools—3D printers, microwaves, and PDMS—students can fabricate functional microfluidic systems. 

Argon plasma bonding was chosen for safety and availability, and after extensive trials, a suitable Pyrex microwave container was found for low-pressure plasma generation. Although challenges such as PDMS fragility and irregular particle size occurred, these were mitigated through iterative design improvements.

This study also emphasizes the pedagogical impact: enabling secondary students to gain hands-on experience in microfluidics, computer vision, and environmental science, fostering curiosity and innovation.

---

## Conclusion

This research developed a **low-cost, user-friendly microplastic screening station** integrating homemade microfluidic devices and computer vision algorithms.  
It demonstrates that meaningful scientific research and marine education can be achieved using accessible materials, supporting STEM learning and environmental awareness.  

This system not only contributes to microplastic research but also provides a scalable model for **STEM-based environmental education** in resource-limited settings.

---

## References

- Elvira, K. S., i Solvas, X. C., Wootton, R. C. R., & deMello, A. J. (2013). *The past, present and potential for microfluidic reactor technology in chemical synthesis.* Nature Chemistry, 5(11), 905–915.  
- Farhadi, T. S. et al. (2021). *Microplastics in the environment: Occurrence, risks and remediation.* Science of The Total Environment, 758, 143555.  
- Geyer, R., Jambeck, J. R., & Law, K. L. (2017). *Production, use, and fate of all plastics ever made.* Science Advances, 3(7).  
- Greenpeace East Asia (2022). *Annual Report 2021.*  
- Huang, Z., Hu, B., & Wang, H. (2023). *Analytical methods for microplastics in the environment: a review.* Environ Chem Lett 21, 383–401.  
- Lai, C. S. (2021). *A study of the learning outcomes on marine education.* International Journal on Social and Education Sciences, 3(3), 589–602.  
- Mesquita, P., Gong, L., & Lin, Y. (2022). *A Low-Cost Microfluidic Method for Microplastics Identification.* Micromachines, 13(4), 499.  
- Nascimento, F. D. et al. (2015). *Treatment of PDMS surfaces using pulsed DBD plasmas.* arXiv, 1504.03633.  
- Tsai, L. T., Chang, C. C., & Cheng, H. T. (2021). *Effect of a STEM-oriented course on students’ marine science motivation.* Journal of Baltic Science Education, 20(1), 134–145.  
- Taiwan Ministry of Education (2020). *Promotion of Marine Education Implementation Project.*  
- Taha, B. T. et al. (2022). *Nanotechnology and Computer Science: Trends and advances.* Memories, 2:100011.  
- Vecchi, S. et al. (2021). *Field evidence for microplastic interactions in marine benthic invertebrates.* Sci Rep 11:20900.  

---


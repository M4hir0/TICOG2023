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

Taiwan is a maritime nation that has relied on marine resources for its development throughout its history. To achieve sustainable development in this
country, marine science education is increasingly important. However, the integration of STEM education into this topic is rarely applied in secondary schools due to a lack
of availability of laboratory-level equipment. Microplastic pollution is a pressing environmental issue, and detecting microplastics in the marine environment is
essential for developing effective strategies to mitigate this problem. However, existing detection tools are limited in terms of accessibility and convenience, while
high equipment costs also restrict research in secondary school-level academia.

To address these challenges, we modified kitchen-based equipment to create a low-cost and user-friendly microplastic screening station using homemade
microfluidic devices and computer imaging algorithms. In our preliminary results, we evaluated the reaction time for microplastic staining and compared it to conventional
staining techniques. Our fabricated device provides an alternative method for detecting microplastics that is more standardized and automatic.

This study has important implications for STEM education, as it provides an accessible direction for undergraduate students in biotechnology research and
extends their research field to an advanced level. By offering a low-cost and user-friendly screening method, our study can also help promote research on microplastic
pollution in a broader range of academic settings.

**Keywords:** computer vision, education, homemade, microplastic, microfluidic, STEM.

---

## Introduction

Microplastic pollution is a global problem that has a significant impact on marine ecosystems, including those in Taiwan. Taiwan is an island nation that is particularly
vulnerable to plastic waste, with an estimated 15,000 tons of plastic waste entering its oceans every year (Greenpeace East Asia, 2022). This pollution threatens the health of marine
organisms, as well as the livelihoods of those who rely on the ocean for food and tourism (Megan,2021).

Microplastics are small plastic particles that accumulate in the environment due to various reasons, such as plastic waste, industrial effluents, and plastic debris in oceans
(Geyer, Jambeck &amp; Law,,2017). These microplastics have become a significant environmental concern as they can have severe impacts on the ecosystem (Vecchi, Bianchi,
Scalici, Massimiliano, Fabroni &amp; Tomassetti, 2021). To address this problem, there is a growing need to educate students in Taiwan about microplastic pollution and its impact on
the marine environment (Lai, 2021). Tsai&#39;s study showed that STEM-based implementation in marine science teaching increases the success rate and attitude of younger students (Tsai,
Chang &amp; Cheng, 2021).

However, traditional methods of detecting microplastics are expensive and require specialized equipment and expertise, making it difficult to incorporate them into marine
science education in lower-secondary schools. The detection of microplastics in the environment is a challenging task and requires specialized techniques and equipment.
Techniques for microplastic detection include visual observation with or without staining maneuvers, ultrasound scanning, Fourier-transform infrared spectroscopy (FTIR), Raman
spectroscopy, and scanning electron microscopy (SEM) (Huang, Hu &amp; Wang, 2023). However, all of this equipment is expensive, time-consuming, and technically challenging,
which makes it difficult to expand screening detection.

One of the recent advancements in this field is the use of microfluidic devices for the detection of microplastics. Microfluidic devices are miniature devices that use channels and
chambers to manipulate small volumes of fluids. These devices typically consist of microchannels, chambers, and valves that are fabricated on a substrate using microfabrication techniques. Microfluidic devices have several advantages over traditional analytical techniques, such as reduced sample volume, improved sensitivity, and faster
analysis time (Novotny &amp; Foret, 2016). These devices are used in various applications, such as chemical analysis (Elvira, i Solvas, Wootton &amp; deMello, 2013), medical
diagnostics , and environmental monitoring (Sachedva, Davis &amp; Saha, 2021). In marine science , the use of microfluidic devices allows for the separation and identification of
microplastics from complex environmental matrices. The detection of microplastics using microfluidic devices involves several steps, such as sample collection, sample preparation,
and analysis.

Microfluidic devices and computer vision technology are relatively new ideas in the field of microplastic detection. While traditional methods of detecting microplastics, such as
microscopy and spectroscopy, require expensive laboratory equipment and trained personnel. Our homemade microfluidic devices, which can be made using
polydimethylsiloxane (PDMS) materials, offer a low-cost alternative to commercial microfluidic devices. Computer vision technology, on the other hand, refers to the use of
algorithms and software to analyze images and videos. In the context of microplastic detection, computer vision technology can be used to analyze images of microplastics that
are captured using a microscope or a camera. This technology offers a fast and accurate way to detect and classify microplastics.

By combining homemade microfluidic devices and computer vision technology, it is possible to detect microplastics in a cost-effective and accessible manner. This has
significant implications for marine science education, as it allows students to learn about microplastic pollution and contribute to the efforts of monitoring and reducing microplastic
pollution in their local communities.

In this paper, we demonstrate how to make a microplastic detection apparatus with limited and relatively low-cost fabrication settings. The accuracy and availability were also tested compared with the conventional bench manner. The tricks of the trade were also discussed for microfluidic chip fabrication.

---

## Methodology

1. Microfluidic chip fabrication

The method of soft lithography is used for creating microfluidic devices. The channel design was created using SolidWorks 2013 x64 bit edition. The staining chip consists of two
functional units: a zigzag mixing channel and a serpentine-shaped reactor channel (Figure 1). The total length of the channel was calculated, and a mold for casting polydimethylsiloxane
(PDMS) was created using a resin 3D printer (Phrozen mini 8K, Aqua 8K gray resin, 0.022um layer height, Chitubox slicing software). PDMS (Dowsil™, Sylgard 184, Density
1.03 g/cm3) was then prepared in a 10:1 ratio and fully degassed in a vacuum chamber. The PDMS was carefully poured into the mold without any bubbles and cured in a modified
toaster oven with a temperature control unit (Figure 2). The mold was placed at 80 degrees Celsius for 60 minutes, and after the PDMS had completed the crosslinking reaction, it was
carefully demolded using a flat-shaped instrument with a special rotational maneuver.

The PDMS layer and slide glass were surface-treated using homemade microwave Argon plasma treatment under pressure down to 0.5 miniTorr (using a Whirlpool microwave
700W). A 3-way air tube system was created with argon air supplementary and vacuum pressure for the modification of the microwave (Figure 3). After plasma treatment, the
PDMS chip was sealed with further baking at 80 degrees Celsius for 10 minutes (Figure 4). 

The inlet and outlet of the microfluidic chip were punch-cut using a 4mm puncher and
connected using a 4mm PTFE tube. A ceramic microheater was used and set up beneath the microfluidic chip . A temperature sensor with an Arduino board controlled the microfluidic
working temperature to around 80 degrees Celsius (Figure 5). A double-channel peristaltic pump was used for the microfluidic devices, and the PTFE tube was connected with flow
speed control from 0.0033 to 10.03ml/min. The concentration and temperature of the staining process were controlled at 50X and 80 degrees Celsius, respectively.

2. Microplastic sample preparation

In this study, the microplastic sample polyethylene (PE) was prepared using a machine grinder. Two milligrams of ground PE was filtered through a sieve to a size of 2mm and
mixed with 2 ml of reverse osmosis (RO) water. Additionally, 0.5 ml of RO water was prepared as a control sample.

3. Nile Red (9-diethylamino-5H-benzo[α]phenoxazine-5-oneStain) Preparation

The staining solution was prepared by dissolving Nile Red (99%, thermo scientific,CAS no:7385673 ) in methanol( 99.5%, Miani Chem, Cas No.67-56-1 ) (1 mg/ml) with dilution of
50X .

4. Conventional staining procedure

For conventional bench staining procedure, 0.25ml Nile Red staining solution was mixed with 0.25ml of microplastic sample solution inside the Eppendorf tube. The tube
was placed in the temperature control toast oven with 80 Celsius degrees. The time for reaction was tested: 5,15 and 20 minutes.

5. Microfluidic reactor staining experiment

For the microfluidic device staining procedure, Nile Red prepared solution was connected to Inlet A, and the microplastic sample solution was connected to Inlet B. The total
microchannel length was 6 mm, and the cross-sectional area was 3 x 3 mm. To compare with the conventional bench experiment, the corresponding flow rate of 0.05, 0.0333and 0.025
mL/min were set for 5, 15 and 20 minutes, respectively. The mixture was then directed to the outlet C and flowed into the observation reservoir.

6. Computer vision and auto counting setting.

After the staining reaction, the sample was infused into the observation reservoir, and immediate analysis was conducted. Image acquisition and analysis were performed using a
460 nm wavelength USB blue light (EHE, model U12H1-B, 460 nm, 120 degrees, made in Taiwan), which was illuminated towards the observation reservoir chip. Images were captured
using a generic USB microscope. A Kapton Tape was used for background filtering of microscope imaging, and the fluorescent signals from the samples were observed. The
acquired images, with a resolution of 1920 x 1440 pixels, were processed using a web base online computer vision technique. The Nile-Red-stained particles were marked using
computer vision with Python code. The algorithm extracted the red channel of the image, which corresponded to the fluorescence emission wavelength of Nile Red, and automatically
calculated the number of particles. The number of microplastic particles was counted and recorded in correlation with the residency time in the microfluidic device.

### Microfluidic Chip Fabrication
Soft lithography was used to create PDMS-based microfluidic chips with zigzag and serpentine channels. Molds were designed in SolidWorks and 3D printed. PDMS was poured, degassed, and cured in a **modified toaster oven**. Surface bonding was achieved with **homemade microwave Argon plasma**.

![Figure 1: Steps of soft lithography for making PDMS layer](images/image1.jpg)
![Figure 2: PDMS curing process in modified toaster oven](images/image2.png)
![Figure 3: Modified microwave with Argon plasma setup](images/image3.jpg)
![Figure 4: Completed PDMS-glass bonded chip](images/image4.jpg)
![Figure 5: Microfluidic setup including microscope and heater](images/image5.jpg)

### Microplastic Sample Preparation
Ground polyethylene (PE) was sieved to <2mm and suspended in reverse osmosis (RO) water. Control samples used RO water only.

### Nile Red Staining
Nile Red (1 mg/mL in methanol) was diluted 50× for fluorescence staining.

### Conventional Staining
Microplastic and dye solutions were mixed and heated at 80°C for 5, 15, and 20 minutes.

### Microfluidic Reactor Staining
Nile Red and sample solutions flowed through the microfluidic chip at 0.05–0.025 mL/min, allowing on-chip staining and mixing.

### Computer Vision Analysis
Fluorescent images were captured under a 460 nm blue light microscope and analyzed using a **Python-based computer vision algorithm** that counted Nile-Red-stained particles automatically.

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

**Observation:**  
The microfluidic method achieved comparable or superior staining efficiency, especially for longer reaction times due to improved flow mixing.

![Figure 6: Microfluidic chip fabrication equipment](images/image6.jpg)

---

## Discussion

Marine science education in Taiwan is constrained by the lack of lab equipment. Our project demonstrates that **household tools can replace professional instruments** for meaningful STEM learning.  

Key takeaways:
- Argon plasma bonding provided a safer, cost-effective alternative to commercial plasma systems.  
- DIY adaptations reduced cost from >NT$70,000 to <NT$400 while maintaining functionality.  
- Challenges such as PDMS fragility and irregular microplastic shapes were overcome through iterative design and programming fixes.

![Figure 7: Argon plasma generation during bonding process](images/image7.jpg)
![Figure 8: Common pitfalls—glass breakage and lid melting](images/image8.jpg)
![Figure 9: Final Pyrex microwave container setup](images/image9.jpg)
![Figure 10: Demolding using curved tweezers](images/image10.jpg)
![Figure 11: Captured image of irregular microplastic debris](images/image11.jpg)
![Figure 12: Online automatic labeling via computer vision](images/image12.jpg)

This approach provides a **millifluidic system** practical for secondary school settings—bridging environmental science, engineering, and computer vision.

---

## Conclusion

This study developed a **low-cost, user-friendly microplastic screening station** integrating homemade microfluidic devices and computer vision.  

It:
- Makes advanced microplastic research accessible to students and educators.  
- Promotes STEM engagement and environmental awareness.  
- Encourages innovation in resource-limited educational environments.

The project demonstrates how **DIY microfluidics and AI-based imaging** can inspire sustainable science education.

---

## References

- Elvira, K. S., i Solvas, X. C., Wootton, R. C. R., & deMello, A. J. (2013). *The past, present and potential for microfluidic reactor technology in chemical synthesis.* Nature Chemistry, 5(11), 905–915.  
- Farhadi, T.S. et al. (2021). *Microplastics in the environment: Occurrence, risks and remediation.* *Science of The Total Environment*, 758, 143555.  
- Geyer, R., Jambeck, J. R., & Law, K. L. (2017). *Production, use, and fate of all plastics ever made.* *Science Advances*, 3(7).  
- Greenpeace (2022). *Annual Report 2021.*  
- Huang, Z., Hu, B., & Wang, H. (2023). *Analytical methods for microplastics in the environment: a review.* *Environmental Chemistry Letters*, 21, 383–401.  
- Lai, C.S. (2021). *A study of the learning outcomes on marine education.* *International Journal on Social and Education Sciences*, 3(3), 589-602.  
- Mesquita, P., Gong, L., & Lin, Y. (2022). *A Low-Cost Microfluidic Method for Microplastics Identification.* *Micromachines*, 13(4), 499.  
- Nascimento, F.D. et al. (2015). *Treatment of PDMS surfaces using pulsed DBD plasmas.* *arXiv*, 1504.03633.  
- Tsai, L.T., Chang, C.C., & Cheng, H.T. (2021). *Effect of a STEM-oriented course on students’ marine science motivation.* *Journal of Baltic Science Education*, 20(1), 134–145.  
- Taiwan Ministry of Education (2020). *Promotion of Marine Education Implementation Project.*  
- Taha, B.T. et al. (2022). *Nanotechnology and Computer Science: Trends and advances.* *Memories*, 2:100011.  
- Vecchi, S. et al. (2021). *Field evidence for microplastic interactions in marine benthic invertebrates.* *Scientific Reports*, 11:20900.  

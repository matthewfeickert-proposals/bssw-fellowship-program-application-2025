# Application

## Experience

### Describe your work relevant to scientific software (1000 - 1500 characters).

> Include your background in scientific software products, and what "hands-on" experience you have had that would make you a credible expert in some aspect of scientific software.

```
$ wc --chars wc.txt
1492 wc.txt
```

My career as an experimental high energy physicist has a strong focus on building open source scientific software for the particle physics community and creating scientific software ecosystems that span across domains in physics and the broader scientific open source community.
I am the Analysis Systems focus area lead for the Institute for Research and Innovation in Software for High Energy Physics (IRIS-HEP) (https://iris-hep.org/) where I lead work creating next generation Pythonic data analysis tools and cyberinfrastructure designed to meet the challenges of the data intensive scientific research at the planned High Luminosity Large Hadron Collider (HL-LHC) at CERN.
I additionally serve on the IRIS-HEP Executive Board where I work with the other board members to guide the institute towards success.
As part of my work in IRIS-HEP, and as a member of the ATLAS experiment at CERN, I am a developer and maintainer of the statistical modeling and inference library pyhf (https://github.com/scikit-hep/pyhf).
pyhf implements a family of statistical models used extensively in experimental particle physics and leverages automatic differentiation and hardware acceleration to improve inference speed while allowing for expressive modeling.
pyhf is a NumFOCUS Affiliated Project and has been used across multiple subdomains of particle physics in publications of LHC experiment analyses, across multiple experimental collaborations, and in particle physics phenomenology and theory.

### Describe your background and experience relevant to being a BSSw Fellow (1000 - 1500 characters).

> Include evidence that you could be an effective advocate for better scientific software, reaching out to others to convey what you know as an expert.

```
$ wc --chars wc.txt
1501 wc.txt
```

I am involved with multiple organizations and efforts across the scientific open source software community that are aligned with the BSSw Fellowship program's goals of promoting best practices and tools for improving productivity and software sustainability.
I serve as an associate editor for the Journal of Open Source Software (JOSS) (https://joss.theoj.org) in the scientific tracks of Physics and Engineering and Data Science, AI, and Machine Learning.
JOSS improves research software through peer review and also creates pathways to receive scholarly credit for scientific software development.
I also serve on the organizing committee for the international SciPy conference, where I work to bring the broader scientific Python community together to share research across scientific domains and organize community efforts.
In my role as a physicist in the ATLAS collaboration I also serve as the Analysis Preservation Contact where I develop and teach methods of analysis and software preservation.
I have organized and taught multiple workshops for ATLAS on best practices for software development and efficient software sustainability.
Similarly, in my leadership roles in IRIS-HEP I have both organized and taught multiple training events for scientific analysis tooling, and also mentored more than ten early career IRIS-HEP Fellows.
I have also lectured at the US Research Software Sustainability Institute (URSSI) summer school on Research Software and Open Science on software packaging.

## Proposed work and impact

The fellowship period of performance will begin March 1, 2025 and end March 31, 2026. Proposed activities should result in one or more well-documented, publicly available artifacts.

### What would you do as a BSSw Fellow? (1500 - 2000 characters).

> The proposed work should be relevant to scientific software and can benefit the Department of Energy (DOE) and/or National Science Foundation (NSF), and the broader high-performance computing (HPC) and computational science and engineering (CSE) communities.
> Work should be well-scoped with clear deliverables and likely to be accomplished within the period of performance.

```
$ wc --chars wc.txt
1986 wc.txt
```

As a BSSw Fellow I will develop an open source course (website) on the process of packaging scientific and AI/machine learning (ML) software and making reusable applications; I will teach the course as a module at multiple workshops and conference tutorial sessions.
The course will have a focus on packaging scientific Python libraries and distribution on package indexes (e.g. PyPI and conda-forge), but will be scoped broadly and cover packaging and distribution of C and C++ libraries on conda-forge as well.
Beyond packaging their software, scientists need reproducible computing environments for "applications" that need to be run across multiple computing platforms &mdash; e.g. scientific analyses, visualization tools, data transformation pipelines, and ML applications on hardware accelerator platforms.
While workflow engines and Linux containers offer a gold standard for scientific computing reproducibility, they require additional layers of training and software engineering knowledge.
Modern multi-platform environment management tools, e.g. pixi (https://pixi.sh/), provide automatic multi-platform hash-level lock file support for all dependencies of software on Python or Conda package indexes while still providing a high level interface well suited for scientists.
The course will cover using these tools to create reproducible software environments for AI/ML applications, including all CUDA dependencies, which is becoming a more relevant issue as AI/ML becomes a standard part of modern science.
I will also create a workshop to teach the content of the course to scientists.
The workshop will be incubated at the University of Wisconsin-Madison Data Science Hub, and will solicit a national call for applications for workshop participants, whose travel will be supported by the BSSw Fellow award funds.
This course will also be submitted as a proposal for a tutorial at the 2025 SciPy conference, and will be recommended as a module for future URSSI workshops.

### What technical impact do you foresee from your efforts? (1000 - 1500 characters).

> The proposed work should have broad technical impact that spans beyond a single community/event and result in one or more artifacts that are available beyond the fellowship period of performance.

```
$ wc --chars wc.txt
1483 wc.txt
```

Reproducible software environments are critical not only for reproducibility of results, but, arguably more importantly, for practically sharing complex scientific environments with many dependencies for scientists to work collaboratively.
The open source website, course, and workshop series together will practically teach researchers how to make their software reusable and their exact software environments easily and immediately shareable.
It is without exaggeration that today researchers can spend hours building bespoke software environments for their work that have complex enough dependency trees that they require great effort to rebuild even on the same machines.
Providing researchers with not only a best practice workflow for lock-file-based reproducible software environments, but also the tools to immediately implement them across multiple platforms will scale the human time savings across science significantly as researchers adopt these methods in their research groups.
It will also increase computational savings by avoiding running of scientific workflows with improperly defined environments that could alter results, fail to reproduce key findings, or result in errors and crashes.
As GPU based workflows are notoriously difficult for sharing their exact environment specifications, this will provide a huge reproducibility benefit.
Additionally, I will share the course widely and encourage other scientists to adopt it in their own research and teaching.

### What broader community impact do you foresee from your efforts? (1000 - 1500 characters).

> We value work that has broader community impact: the potential to benefit society and contribute to the achievement of specific, desired societal outcomes, including but not limited to: inclusion, STEM education, public engagement.

```
$ wc --chars wc.txt
1495 wc.txt
```

Most scientists do not receive a formal education in software development and engineering and the associated best practices.
However, these skills are vital to tackle the complex scientific questions of today.
Through the course and workshops I will be able to train early career researchers (university and graduate students, and junior postdocs) across multiple scientific domains on how to improve the maintainability of their software, reproducibility of their work, and ultimately the quality of their science.
The impact of investing in the technical education of early career researchers will grow over time as they bring what they have learned to bear in their research and spread their knowledge in new collaborations.
All the course and workshop content, and the website source code, will be open source under a permissive license, making it easy for other researchers to use the course material in their own lectures and workshops.
Access to high quality scientific computing educational resources is an equity issue and open sourcing that knowledge makes it more accessible.
The course will also not be static, but will be updated as new improvements and recommendations are made available.
I will encourage sharing of the material and by having the workshops target a wide range of scientific domains I will ensure that this knowledge spreads and helps multiple scientific communities develop better workflows and practices around reproducible and sustainable software development.

### Which BSSw focus areas and subtopics apply to your proposed work? (500 characters).
Specify all that apply.
See https://bssw.io for a list of focus areas and subtopics (e.g., Focus Area: Planning; Subtopic: Requirements).

* Focus Area: Planning; Subtopic: Software Engineering
* Focus Area: Planning; Subtopic: Software Sustainability
* Focus Area: Development; Subtopic: Configuration and Builds
* Focus Area: Development; Subtopic: Release and Deployment
* Focus Area: Performance; Subtopic: High-Performance Computing (HPC)
* Focus Area: Reliability; Subtopic: Reproducibility
* Focus Area: Skills; Subtopic: Online Learning
* Focus Area: Skills; Subtopic: In-Person Learning

# Application

## Experience

### Describe your work relevant to scientific software (1000 - 1500 characters).

```
$ wc --chars wc.txt
1402 wc.txt
```

My career as an experimental high energy physicist has a strong focus on building open source scientific software for the particle physics community and building scientific software ecosystems spanning domains in physics and the broader scientific open source community.
I am the Analysis Systems focus area lead for the Institute for Research and Innovation in Software for High Energy Physics (IRIS-HEP) where I lead work creating next generation Pythonic data analysis tools and cyberinfrastructure designed to meet the challenges of the data intensive scientific research at planned High Luminosity Large Hadron Collider (HL-LHC) at CERN.
I additionally serve on the IRIS-HEP Executive Board where I work with the other board members to guide the institute towards success.
As part of my work in IRIS-HEP, and as a member of the ATLAS experiment at CERN, I am a developer and maintainer of the statistical modeling and inference library pyhf (https://github.com/scikit-hep/pyhf).
pyhf implements a family of statistical models used extensively in experimental particle physics and leverages automatic differentiation and hardware acceleration to improve inference speed while allowing for expressive modelling.
pyhf has been used across multiple subdomains of particle physics for physics publications, across multiple experimental collaborations, and in particle physics phenomenology and theory.

### Describe your background and experience relevant to being a BSSw Fellow (1000 - 1500 characters).

```
$ wc --chars wc.txt
1498 wc.txt
```

I am involved with multiple organizations and efforts across the scientific open source software community that are aligned with the BSSW Fellowship program's goals of promoting best practices and tools for improving productivity and software sustainability.
I serve as an associate editor for the Journal of Open Source Software (JOSS) (https://joss.theoj.org) in the scientific tracks of Physics and Engineering and Data Science, AI, and Machine Learning.
JOSS improves research software through peer review and also creates opportunities to receive scholarly credit for scientific software development.
I also serve on the organizing committee for the international SciPy conference, where I work to bring the broader scientific Python community together to share research across scientific domains and organize community efforts.
In my role as a physicist in the ATLAS collaboration I also serve as the analysis preservation contact where I develop and teach methods of analysis and software preservation.
I have organized and taught multiple workshops for ATLAS on best practices for software development and efficient software sustainability.
Similarly, in my leadership roles in IRIS-HEP I have both organized and taught multiple training events for scientific analysis tooling, and also mentored more than ten early career IRIS-HEP Fellows.
I have also lectured at the US Research Software Sustainability Institute summer school on Research Software and Open Science on software packaging.

## Proposed work and impact

### What would you do as a BSSw Fellow? (1500 - 2000 characters).

```
$ wc --chars wc.txt
2159 wc.txt
```

As a BSSW Fellow I will develop an open source course (website) on the process of packaging scientific and AI/machine learning (ML) software and making reusable applications, and I will teach the course as a module at multiple workshops and conference tutorial sessions.
The course will have a focus on packaging scientific Python libraries and distribution on PyPI and conda-forge indexes, but will be scoped broadly and cover packaging and distribution of C and C++ libraries on conda-forge as well.
Beyond packaging their software, many scientists need reproducible scientific computing environments for "applications" that need to be run across multiple computing platforms --- e.g. scientific analyses, visualization tools, data transformation pipelines, and ML applications on hardware accelerator platforms.
While workflow engines and Linux containers offer a gold standard for scientific computing reproducibility, they require additional layers of training and software engineering knowledge.
Modern multi-platform environment management tools, i.e. pixi (https://pixi.sh/), provide automatic multi-platform hash-level lock file support for all dependencies for all software available on conda-forge and PyPI while still providing a high level interface well suited for scientists.
The course will cover using these tools to create reproducible software environments for AI/ML applications including all CUDA dependencies, which is becoming a more relevant issue as AI/ML becomes a standard part of modern science.
I will also create a workshop to teach the content of the course to scientists.
The workshop will be incubated at the University of Wisconsin-Madison Data Science Hub, and will solicit a national call for applications for workshop participants, whose travel will be supported by the BSSW Fellow award.
This course will also be submitted as a proposal for a tutorial at the 2025 SciPy conference, and will be recommended as a module for URSSI workshops in 2025.

---

* Workshops on packaging and distribution of scientific software, using conda-forge.
Also using pixi for cross platform software environment reproducibility allowing for scientific applications to be shared easily.
* Add a focus on AI/ML applications benefitting from GPU.
* Write this all as open website training material with examples and teach the workshops using the websites.
* Propose a tutorial at SciPy 2025.

### What technical impact do you foresee from your efforts? (1000 - 1500 characters).

```
$ wc --chars wc.txt
1297 wc.txt
```

Reproducible software environments are critical not only for reproducibility of results, but, arguably more importantly, for practically sharing complex scientific environments with many dependencies for scientists to work collaboratively.
The open source website and course and workshop series together will practically teach researchers how to make their software reusable and their exact software environments easily shareable.
It is without exaggeration that today researchers can spend hours building bespoke software environments for their work that are complex enough that they require great effort to rebuild even on the same machines.
Providing researchers with not only a best practice workflow for lock file based reproducible software environments but also the tools to immediately implement them across multiple platforms will scale the human time savings across science significantly as researchers adopt these methods across their research groups.
It will also increase computational savings by avoiding running of scientific workflows with improperly defined environments that could alter results or fail to reproduce key findings.
As GPU based workflows are notoriously difficult to share the exact environment specifications of, this will provide a huge reproducibility benefit.

### What broader community impact do you foresee from your efforts? (1000 - 1500 characters).

```
$ wc --chars wc.txt
1245 wc.txt
```

Most scientists do not receive a formal education in software development and engineering and the associated best practices.
However, they generally are interested to learn and apply them if they are shown the positive impacts on their research.
Through the course and workshops I will be able to reach early career researchers (university and graduate studies, and junior postdocs) across multiple scientific domains, improving the maintainability of their software and reproducibility of their work.
This impact will cascade forward in time making them more productive and the software they produce more useful.
All the course and workshop content and the software for the website will be open source under a permissive license, making it easy for other researchers to use the course material in their own lectures and workshops.
The course will also not be static, but will be updated as new improvements and recommendations are made available.
I will encourage sharing of the material and through having the workshops target a wide range of scientific domains I will ensure that this knowledge spreads and helps multiple scientific communities develop better workflows and practices around reproducible and sustainable software development.

---

NOTE: Revise as this is not clear what the **broader** community impact is.

### Which BSSw focus areas and subtopics apply to your proposed work? (500 characters).
Specify all that apply.
See https://bssw.io for a list of focus areas and subtopics (e.g., Focus Area: Planning; Subtopic: Requirements).

* Focus Area: Planning; Subtopic: Software Sustainability
* Focus Area: Performance; Subtopic: High-Performance Computing (HPC)
* Focus Area: Performance; Subtopic: Big Data
* Focus Area: Reliability; Subtopic: Reproducibility

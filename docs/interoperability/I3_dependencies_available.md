# I3. Dependencies Availability 

Whether dependencies are documented and mechanisms to obtain them exist. 

- ### I3.1 Dependencies documentated.

    Whether the software includes details about dependencies. 

    | Why should we measure it?  | How do we measure it? | Types it applies to  |
    |----------------------------|-----------------------|----------------------|
    | A dependencies statement allows the user to know what additional software they must install in order to get a software running  | At least one dependency is stated.  | all | 
   
- ### I3.2 Dependencies available.

    Whether the software includes its dependencies or mechanisms to access them 
    
    | Why should we measure it?  | How do we measure it? | Types it applies to  |
    |----------------------------|-----------------------|----------------------|
    | Even if dependencies are stated, the process of downloading and installing them can be incredibly hard, except the dependencies are directly provided with software or the mechanisms to obtain them are provided.  |  The software is available at, at least, one of the following: Bioconductor, Bioconda, Galaxy, Conda, PyPI, CRAN, npm, CPAN, RubyGems, BioJS, DockerHub, GitHub Container Registry, GitLab Container Registry, or BioContainers.  | all  | 
    
    
- ### I3.3 Distribution through dependencies aware systems.

     Whether the software is distributed via a dependencies aware system. 
     
    | Why should we measure it?  | How do we measure it? | Types it applies to  |
    |----------------------------|-----------------------|----------------------|
    | Even if dependencies are stated, the process of downloading and installing them can be incredibly hard. Dependencies-aware systems like 'bioconda' are the easiest and most straightforward way to obtain and install all the dependencies a software needs. | The software is available at, at least, one of the following: Bioconductor, Bioconda, Galaxy, Conda, PyPI, CRAN, npm, CPAN, RubyGems, BioJS.  | all |
     


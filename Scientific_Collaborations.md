## Work related to the collaboration with researchers
 
Again, the people from this background have a different culture.
 
My core contribution to the collaboration is basically data engineering using the cloud since Genomics is extremely resource heavy. I got started in this field because I wanted to help a Biologist friend and initially I rolled out my own ad-hoc solution for this (using the same ammonite shell I used for web scraping) https://github.com/emilyncosta/tese
 
But later on, I realized that this is not scalable and I invested  time in learning a proper tool called Nextflow (https://www.nextflow.io/) which is an alternative to Apache Spark (big data analytics tool) and relies on Linux based CLI tools rather than requiring the user to implement tools using the spark framework itself. I’ve given professional training based on this tool and it’s usage with AWS as well. Here’s one such recorded session https://www.youtube.com/watch?v=rOZXfAhI0Q8
 
Slowly, I became a member of community driven orgs like nf-core and felt uncomfortable in working with 3000+ Lines of Code pipelines (https://github.com/nf-core/rnaseq/blob/master/main.nf) which work fine but cause a lot of friction during customization. Therefore I started nextflow-hub which offers granular (60 LOC - https://github.com/nextflow-hub/tb-profiler/blob/master/main.nf ) and composable process based pipelines with sensible defaults such that anyone without a deep technical background could use the tools which are containerized either by bioconda project or by myself  https://github.com/nextflow-hub-containers for true reproducibility.
 
Unfortunately, bioinformaticians/computational biologists often end up abandoning projects after the publication of their papers or simply because they are now working on different problems. However, I am not comfortable as an engineer with the status quo so I try to do some maintenance work (as I need to use these tools) rather then adding features (which requires domain knowledge).
 
- https://github.com/cguyeux/pyMTC/pull/1
- https://github.com/xiaeryu/SpoTyping-v2.0/pull/4
- https://github.com/xiaeryu/SpoTyping-v2.0/pull/3
- https://github.com/xiaeryu/SpoTyping-v2.0/pull/2
- https://github.com/xiaeryu/RD-Analyzer/pull/5
- https://github.com/xiaeryu/RD-Analyzer/pull/4
- https://github.com/xiaeryu/RD-Analyzer/pull/3
- https://github.com/bebatut/enasearch/pull/43
 
 

# Abstract of the Pending NSF Award

# Non-technical summary

Soon, computer main memories will likely use new technology, *non-volatile memory* (NVM).  While current memories lose their contents when power is removed, NVM will retain its contents.  However, computers keep some recent information inside the processor.  That data will *still* be lost.  So, NVM will not *by itself* enable users to get back to exactly where they were.  To make full recovery possible, programs will need to use NVM carefully.  Doing this well for modern programming languages (such as Java and Python) is hard.  This project will provide a common base of support for NVM for such languages.

# Technical summary

Clean language semantics for non-volatility is called *persistence*.  Managed languages (ones with garbage collection and threads) require both appropriate persistence semantics and a robust performant implementation.  Adding clean persistence in the presence of threads and garbage collection is hard, and modern multi-core machines present additional challenge because of their weak memory consistency models.  The project will extend a language-independent virtual machine with flexible persistence semantics.  This will help avoid having every language project build its own support from scratch.  The project direction is to support transactions over a persistent heap of containers and versioned objects.

# Broader impacts

The project will build on Mu (http://microvm.org), an existing virtual machine that has commercial interest.  A persistent virtual machine will save development effort and encourage creative use of persistence in applications.  This will contribute to innovation, reliability, and trustworthiness of software.  The project team will continue to engage in recruiting students from under-represented groups, including mentoring of future applicants and visits to historically minority institutions.

# Project repository

The project's products will reside in a repository at https://github.com/umass-moss-lab/persistent-mu, which will continue to be available for at least three years after the project concludes.  The repository will contain released code, data, etc.  Non-code materials will be available under the Creative Commons license, and code under the Apache open source license, subject to the University of Massachusetts policy on intellectual property.

<!-- A summary of no more than 400 words. This summary should have a total of four paragraphs. This abstract should we written from scratch as distilling from the submitted project abstract will NOT serve the purpose. (Note that the paragraphs DO NOT have any headers, such as summary, intellectual merit, etc.) -->

<!-- The first paragraph should describe in less than 100 words what this entire project does in a non-technical high-level language that can be understood by a middle-school student. The second paragraph should describe in less than 100 words in technical terms what are the intellectual merits embedded into the proposed tasks and showcasing the work organization, e.g. task, thrust, etc. The third paragraph should describe in less than 100 words the broader impact of the project.  The last paragraph must describe in less than 100 words how and for how long you will maintain the project repository (data, code, results, emulators, simulators, etc). Please provide a URL to the repository. -->

<!-- Please write the abstract in third person (e.g. the project) and avoid words, such as we, PI, proposed, and I. Please also do not refer to past accomplishments and the abstract is about the work at hand.  Lastly, please define ALL acronyms. -->

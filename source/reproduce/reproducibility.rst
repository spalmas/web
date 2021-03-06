Reproducibility
===============

Reproducibility has at least two aspects that can be considered: (1) if new data were collected and analyzed, would the results be similar to previously reported results? and (2) if the same data were analyzed again, would that lead to the same results as were previously reported?

The inability to collect new data that shows results previously described in psychology and other social sciences ir referred to as the *reproducibility* or *replication* `crisis <https://en.wikipedia.org/wiki/Replication_crisis>_`. But it is also a serious problem in biomedical research — and the topic of the `most accessed paper in PLoS-ONE <https://journals.plos.org/plosmedicine/article?id=10.1371/journal.pmed.0020124?_` *Why Most Published Research Findings Are False*.

Here we focus on the second aspect. Given a dataset, can we derive the same results when applying the same methods? Assuring that we can is fundamental to science. And reproducing results is not just to check somebody else’s work. More often it is necessary to improve one’s own work, for example to make a revision based on suggestions by a reviewer. It is also fundamental to building on prior research.

Access
Reproducibility of research fundamentally depends on access. Access to results (publications), the underlying data, and to the exact steps taken in the data processing.

The need for improved access to results, through open publishing is perhaps best established and understood. Most scientific journals now allow for open-access publishing if the authors are willing to pay a fee. In other journals, such as the `PLoS journals <https://journals.plos.org/>` and `PeerJ <https://peerj.com/>_` only have open access articles. Some organizations have an open-access policy. For example, the University of California requiring that all research publications are made `openly available <https://escholarship.org/search?type_of_work=article>_` in some form.

The benefit of open publishing is that anyone with an Internet connection has access, not only the privileged few that work in well funded research institutes or universities or can visit a rich university library. Open publishing is of prime importance to public research institutes and their funders to assure that research findings are a public good that can be used by anyone.

More recently there has also been a sea-change in the availability of research data. Primary (“raw”) data was for a long time treated as private information that was not to be shared, and at best summaries of some data were provided as tables or appendices in research articles. For a variety of reasons, an increasing number of researchers are now also providing easy access to the raw data they used in research through on-line repositories. The degree to which this is done depends on the field of study.

An increasing number of researchers working in public institutions now publish their data in full; in part because they themselves use open data in their research, in part because research funders such as the United States National Science Foundation and the Bill and Melinda Gates Foundation, and an increasing number of academic journals, now also require that data is made available. In agricultural research. the CGIAR has been at the forefront of this movement in agriculture, and their research data can easily be searched through the `Gardian website https://gardian.bigdata.cgiar.org/>_`.

The freedom of use of “open data” can vary. Most datasets come with a license. Some licenses restrict use of data for commercial, or any other that has not been explicitly approved. Such restrictions may make the data much less useful and form a major barrier to their use.

The third pillar of reproducibility is open data analysis. The need for this has not received the attention it merits. Data processing is the connection between data and (published) results. With only the raw data and the methods described in an article, it can be difficult, if not practically impossible, to reproduce the results described. The only way to assure reprodicbility is to have all of the analytical workflow in a script, or scripts. Ideally, such scripts would run in free softare such that not having a licens is not a barrier.

Perfect reprodicbility is difficult to achieve — for example a script may depend on partcular version of R or the packeges used. While there are solutions to deal with such problems, for now it seems more important to worry about the more basic problem of how to reproduce research in the absence of any scripts, and how to get researchers to use scripting and to make the scripts avaialable wth the data.
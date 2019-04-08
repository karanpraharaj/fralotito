+++
title = "FBK’s Multilingual Neural Machine Translation System for IWSLT 2017"
date = 2017-12-15T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Surafel M. Lakew", "Quintino F. Lotito", "Matteo Negri", "Marco Turchi", "Marcello Federico"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "In *Proceedings of the 14th International Workshop on Spoken Language Translation (IWSLT 2017)*"
publication_short = "In *IWSLT 2017*"

# Abstract.
abstract = "Neural Machine Translation has been shown to enable inference and cross-lingual knowledge transfer across multiple language directions using a single multilingual model. Focusing on this multilingual translation scenario, this work summarizes FBK's participation in the IWSLT 2017 shared task. Our submissions rely on two multilingual systems trained on five languages (English, Dutch, German, Italian, and Romanian). The first one is a 20 language direction model, which handles all possible combinations of the five languages. The second multilingual system is trained only on 16 directions, leaving the others as zero-shot translation directions (i.e representing a more complex inference task on language pairs not seen at training time). More specifically, our zero-shot directions are Dutch↔German and Italian↔Romanian (resulting in four language combinations). Despite the small amount of parallel data used for training these systems, the resulting multilingual models are effective, even in comparison with models trained separately for every language pair (i.e. in more favorable conditions). We compare and show the results of the two multilingual models against a baseline single language pair systems. Particularly, we focus on the four zero-shot directions and show how a multilingual model trained with small data can provide reasonable results. Furthermore, we investigate how pivoting (i.e using a bridge/pivot language for inference in a source→pivot→target translations) using a multilingual model can be an alternative to enable zero-shot translation in a low resource setting."

# Links (optional).
url_pdf = "https://cris.fbk.eu/retrieve/handle/11582/313114/21547/iwslt17-system.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = "files/poster_iwslt17.pdf"
url_source = ""

# Summary. An optional shortened abstract.
summary = "Description of the system we used for the IWSLT 2017 shared tasks on multilingual NMT."

# Digital Object Identifier (DOI)
doi = ""

# Is this a featured publication? (true/false)
featured = false

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Deep Learning", "NLP", "NMT"]

# Does this page contain LaTeX math? (true/false)
math = true
+++

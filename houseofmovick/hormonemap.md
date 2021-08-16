Hormone Map

name Cortisol
shape Rectangle
color Teal
outputs Enkephalins, Glucose, Endorphins, POMC, alpha-MSH, ACTH, POMC
inputs NPY
description "The stress hormone"
class glucocorticoid

name NPY
shape Rectangle
color yellow
outputs cortisol, ACTH, Leptin, CRH, 
inputs stress, CRH, fasting, Leptin, Insulin, Canabinoids, 
description "vasoconstrictor"
class peptide

name ACTH
shape Rectangle
color Teal
outputs Epinephine, Norepinephrine
inputs NPY, Cortisol, CRH
description "messenger"
class polypeptide

name Epinephine
shape Rectangle
color Teal
outputs Leptin, Glucose
inputs ACTH
description "flight or flight hormone"
class organic_chemical

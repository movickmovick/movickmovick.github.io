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

name glucose
shape elipse
color teal
outputs none;
inputs Adiponectin Insulin resistance Insulin Testosterone Glucagon Epinephrine Cortisol 
description recieved in the hypothalamus
class monosaccharides

name nitrosamine //what is a nitrate because a nitrosamine is formed when a protein reacts with a nitrate
shape elipse
color green 
outputs insulin receptor
inputs none
description "the cancerous meat one" 
class organic_compound

name ocytocin
shape rectangle
color green
outputs insulin insuling_receptor
intputs none
description "the feel good hormone"
class "G-protein-coupled receptor"

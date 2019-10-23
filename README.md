# latin_diplo_model

CRF textual structures recognition to medieval charters

#This is a automatic model to entails automatic textual structures recognition on medieval diplomatic charters.

#Model was trained on a 5 thousands-items database of Italian notarial charters (from XIth - XIIth centuries).

#Model have a single core working in recognition of 15 main structural parts in medieval diplomatics charters.

#Tagging of the model can be activated on well-known tabular txt format (*.crf) used in machine learning training. (As minimal token splited words)

#To annotation you must download Wapiti CNRS package (or any other machine learning model annotation tool) from: https://wapiti.limsi.fr/#download

#Tagging order must follow the pattern: wapiti label -m ~/model.txt -c ~/input.txt ~/output.txt

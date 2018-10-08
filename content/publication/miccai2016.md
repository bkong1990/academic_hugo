+++
title = "Recognizing End-Diastole and End-Systole Frames via Deep Temporal Regression Network"
date = 2016-10-02T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Bin Kong", "Yiqiang Zhan", "Min Shin", "Thomas Denny", "Shaoting Zhang"]

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
# publication = "In *International Conference on Multimedia and Expo Workshops (ICMEW)*, IEEE."
publication = "In *International conference on medical image computing and computer-assisted intervention (MICCAI)*."
publication_short = "In *MICCAI*"

# Abstract and optional shortened version.
abstract = "Accurate measurement of left ventricular volumes and Ejection Fraction from cine MRI is of paramount importance to the evaluation of cardiovascular functions, yet it usually requires laborious and tedious work of trained experts to interpret them. To facilitate this procedure, numerous computer aided diagnosis (CAD) methods and tools have been proposed, most of which focus on the left or right ventricle segmentation. However, the identification of ES and ED frames from cardiac sequences is largely ignored, which is a key procedure in the automated workflow. This seemingly easy task is quite challenging, due to the requirement of high accuracy (i.e., precisely identifying specific frames from a sequence) and subtle differences among consecutive frames. Recently, with the rapid growth of annotated data and the increasing computational power, deep learning methods have been widely exploited in medical image analysis. In this paper, we propose a novel deep learning architecture, named as temporal regression network (TempReg-Net), to accurately identify specific frames from MRI sequences, by integrating the Convolutional Neural Network (CNN) with the Recurrent Neural Network (RNN). Specifically, a CNN encodes the spatial information of a cardiac sequence, and a RNN decodes the temporal information. In addition, we design a new loss function in our network to constrain the structure of predicted labels, which further improves the performance. Our approach is extensively validated on thousands of cardiac sequences and the average difference is merely 0.4 frames, comparing favorably with previous systems."
abstract_short = "A mobile visual clothing search system is presented whereby a smart phone user can either choose a social networking image or capture a new photo of a person wearing clothing of interest and search for similar clothing in a large cloud-based ecommerce database. The phone's GPS location is used to re-rank results by retail store location, to inform the user of local stores where similar clothing items can be tried on."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's filename without extension.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
#projects = ["example-external-project"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "https://link.springer.com/chapter/10.1007/978-3-319-46726-9_31"
#url_preprint = "http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf"
#url_code = "#"
#url_dataset = "#"
#url_project = "#"
#url_slides = "#"
#url_video = "#"
url_poster = "files/MICCAI16_poster.pdf"
#url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = ""

# Does this page contain LaTeX math? (true/false)
math = true

# Does this page require source code highlighting? (true/false)
#highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
#[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++

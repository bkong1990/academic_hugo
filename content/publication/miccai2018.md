+++
title = "Invasive Cancer Detection Utilizing Compressed Convolutional Neural Network and Transfer Learning"
date = 2018-09-16T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Bin Kong", "Shanhui Sun", "Xin Wang", "Qi Song", "Shaoting Zhang"]

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
abstract = "Identification of invasive cancer in Whole Slide Images (WSIs) is crucial for tumor staging as well as treatment planning. However, the precise manual delineation of tumor regions is challenging, tedious and time-consuming. Thus, automatic invasive cancer detection in WSIs is of significant importance. Recently, Convolutional Neural Network (CNN) based approaches advanced invasive cancer detection. However, computation burdens of these approaches become barriers in clinical applications. In this work, we propose to detect invasive cancer employing a lightweight network in a fully convolution fashion without model ensembles. In order to improve the small network’s detection accuracy, we utilized the “soft labels” of a large capacity network to supervise its training process. Additionally, we adopt a teacher guided loss to help the small network better learn from the intermediate layers of the high capacity network. With this suite of approaches, our network is extremely efficient as well as accurate. The proposed method is validated on two large scale WSI datasets. Our approach is performed in an average time of 0.6 and 3.6 min per WSI with a single GPU on our gastric cancer dataset and CAMELYON16, respectively, about 5 times faster than Google Inception V3. We achieved an average FROC of   81.1%  and   85.6%  respectively, which are on par with Google Inception V3. The proposed method requires less high performance computing resources than state-of-the-art methods, which makes the invasive cancer diagnosis more applicable in the clinical usage."
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
url_pdf = "https://link.springer.com/chapter/10.1007/978-3-030-00934-2_18"
#url_preprint = "http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf"
#url_code = "#"
#url_dataset = "#"
#url_project = "#"
#url_slides = "#"
#url_video = "#"
url_poster = "files/miccai2018_poster.pdf"
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


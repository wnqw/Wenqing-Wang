---
title: 'Audio-Driven Emotional 3D Talking-Head Generation [Under Review]'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Wenqing Wang
  - Yun Fu



publishDate: 2024-09-30
# doi: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: IEEE International Conference on Automatic Face and Gesture Recognition
publication_short: FG

abstract: Audio-driven talking-head generation is a crucial and useful technology in virtual human interaction and film- making applications. Recent advancements have focused on improving the image fidelity and lip-synchronization. How- ever, generating accurate emotional expressions is an impor- tant aspect of realistic talking-head generation, which has remained underexplored in previous works. In this paper, we present a novel framework for synthesizing high-fidelity, audio- driven video portraits with accurate emotional expressions. Specifically, we utilize a variational autoencoder (VAE)-based audio-to-motion module to generate facial landmarks. These landmarks are concatenated with emotional embeddings to produce emotional landmarks through our motion-to-emotion module. These emotional landmarks are then used to render realistic emotional talking-head video using a Neural Radiance Fields (NeRF)-based emotion-to-video module. Additionally, we propose a pose sampling method that generates natural idle- state (non-speaking) videos in response to silent audio inputs. Extensive experiments show that our method demonstrates high-fidelity emotion generation compared to previous methods.
 
tags: ["NeRF", "Digital Human", "emotion", "Audio-driven talking-head generation"]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: ''
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

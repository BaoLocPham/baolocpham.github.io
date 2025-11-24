---
title: "An Approach to Hummed-tune and Song Sequences Matching"
collection: publications
category: conferences
permalink: /publication/2022-10-2-an-approach-to-hummed-tune-and-song-sequences-matching
excerpt: 'This paper is about the hummed tune searching for a song sequence. Similar to Google Search feature Hum to Search.'
date: 2022-10-20
venue: 'FDSE'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
# paperurl: 'https://link.springer.com/chapter/10.1007/978-981-19-8069-5_49'
paperurl: '/files/papers/Benchmarking_Vietnamese_Embedding_MarkdownTable.pdf'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
citation: 'Pham, B.L., Luong, H.H., Tran, T.P., Ngo, H.P., Nguyen, H.V., Nguyen, T. (2022). An Approach to Hummed-tune and Song Sequences Matching. In: Dang, T.K., Küng, J., Chung, T.M. (eds) Future Data and Security Engineering. Big Data, Security and Privacy, Smart City and Industry 4.0 Applications. FDSE 2022. Communications in Computer and Information Science, vol 1688. Springer, Singapore. https://doi.org/10.1007/978-981-19-8069-5_49'
---
Melody stuck in your head, also known as “earworm”, is tough to get rid of, unless you listen to it again or sing it out loud. But what if you can not find the name of that song? It must be an intolerable feeling. Recognizing a song name base on humming sound is not an easy task for a human being and should be done by machines. However, there is no research paper published about hum tune recognition. Adapting from Hum2Song Zalo AI Challenge 2021 - a competition about querying the name of a song by user’s giving humming tune, which is similar to Google’s Hum to Search. This paper covers details about the pre-processed data from the original type (mp3) to usable form for training and inference. In training an embedding model for the feature extraction phase, we ran experiments with some states of the art, such as ResNet, VGG, AlexNet, MobileNetV2. And for the inference phase, we use the Faiss module to effectively search for a song that matched the sequence of humming sound. The result comes at nearly 94% in MRR@10 metric on the public test set, along with the top 1 result on the public leaderboard.
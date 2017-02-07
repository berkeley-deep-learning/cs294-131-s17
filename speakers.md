## Devi Parikh: Visual Question Answering (VQA)

### Abstract
Wouldn't it be nice if machines could understand content in images and communicate this understanding as effectively as humans? Such technology would be immensely powerful, be it for aiding a visually-impaired user navigate a world built by the sighted, assisting an analyst in extracting relevant information from a surveillance feed, educating a child playing a game on a touch screen, providing information to a spectator at an art gallery, or interacting with a robot. As computer vision and natural language processing techniques are maturing, we are closer to achieving this dream than we have ever been.

Visual Question Answering (VQA) is one step in this direction. Given an image and a natural language question about the image (e.g., “What kind of store is this?”, “How many people are waiting in the queue?”, “Is it safe to cross the street?”), the machine’s task is to automatically produce an accurate natural language answer (“bakery”, “5”, “Yes”). In this talk, I will present models, datasets, and open research questions in free-form and open-ended Visual Question Answering (VQA). 

Visual questions selectively target different areas of an image, including background details and underlying context. As a result, a system that succeeds at VQA typically needs a more detailed understanding of the image and complex reasoning than a system producing generic image captions. Answering any possible question about an image is one of the ‘holy grails’ of AI requiring integration of vision, language, and reasoning.

I will end with a teaser about the next step moving forward: Visual Dialog. Instead of answering individual questions about an image in isolation, can we build machines that can hold a sequential natural language conversation with humans about visual content?

### [Slides](slides/Parikh_VQA.pptx)

### Bio
Devi Parikh is an Assistant Professor in the School of Interactive Computing at Georgia Tech, and a Visiting Researcher at Facebook AI Research (FAIR). 

From 2013 to 2016, she was an Assistant Professor in the Bradley Department of Electrical and Computer Engineering at Virginia Tech. From 2009 to 2012, she was a Research Assistant Professor at Toyota Technological Institute at Chicago (TTIC), an academic computer science institute affiliated with University of Chicago. She has held visiting positions at Cornell University, University of Texas at Austin, Microsoft Research, MIT, and Carnegie Mellon University. She received her M.S. and Ph.D. degrees from the Electrical and Computer Engineering department at Carnegie Mellon University in 2007 and 2009 respectively. She received her B.S. in Electrical and Computer Engineering from Rowan University in 2005. 

Her research interests include computer vision and AI in general and visual recognition problems in particular. Her recent work involves exploring problems at the intersection of vision and language, and leveraging human-machine collaboration for building smarter machines. She has also worked on other topics such as ensemble of classifiers, data fusion, inference in probabilistic models, 3D reassembly, barcode segmentation, computational photography, interactive computer vision, contextual reasoning, hierarchical representations of images, and human-debugging.

She is a recipient of an NSF CAREER award, a Sloan Research Fellowship, an Office of Naval Research (ONR) Young Investigator Program (YIP) award, an Army Research Office (ARO) Young Investigator Program (YIP) award, an Allen Distinguished Investigator Award in Artificial Intelligence from the Paul G. Allen Family Foundation, three Google Faculty Research Awards, an Amazon Academic Research Award, an Outstanding New Assistant Professor award from the College of Engineering at Virginia Tech, a Rowan University Medal of Excellence for Alumni Achievement, Rowan University's 40 under 40 recognition, and a Marr Best Paper Prize awarded at the International Conference on Computer Vision (ICCV).



## Richard Socher: Tackling the Limits of Deep Learning for NLP	

### Abstract
Deep learning has made great progress in a variety of language tasks.
However, there are still many practical and theoretical problems and limitations.
In this talk I will introduce solutions to some of these:

* How to predict previously unseen words at test time.
* How to have a single input and output encoding for words.
* How to grow a single model for many tasks.
* How to use a single end-to-end trainable architecture for question answering.

### Slides
* [Introductory material](slides/socher-intro.pdf)
* [Main talk](slides/socher-talk.pdf)

### Bio
Richard Socher is the Chief Scientist at Salesforce. Prior he was the CEO and founder of MetaMind, a startup which was recently acquired by Salesforce. MetaMind seeks to improve artificial intelligence and make it widely accessible. He obtained his PhD from Stanford working on deep learning with Chris Manning and Andrew Ng and won the best Stanford CS PhD thesis award. He is interested in developing new AI models that perform well across multiple different tasks in natural language processing and computer vision.

He was awarded the Distinguished Application Paper Award at the International Conference on Machine Learning (ICML) 2011, the 2011 Yahoo! Key Scientific Challenges Award, a Microsoft Research PhD Fellowship in 2012 and a 2013 "Magic Grant" from the Brown Institute for Media Innovation and the 2014 GigaOM Structure Award.

## Rahul Sukthankar: Recent Progress on CNNs for Object Detection and Image Compression

### Abstract
This talk will feature two pieces of current research from my group at Google.  I’ll give an overview of object detection and focus on some key ideas behind the winning G-RMI entry to the 2016 COCO challenge.  I will also give an introduction to neural-net based image and video compression (an application area that is still relatively unexplored) and present recent work on image compression using recurrent CNNs.

### Bio
Rahul Sukthankar leads exploratory research efforts in the Machine Perception group at Google. He is also an adjunct research professor at CMU’s Robotics Institute and courtesy faculty at UCF. He was previously a senior principal researcher at Intel, a senior researcher at HP/Compaq and a research scientist at Just Research. He received his Ph.D. in Robotics from CMU in 1997 and his B.S.E. in Computer Science from Princeton in 1991.

## Bryan Catanzaro: Scaling Deep Learning

### Abstract
Deep learning benefits from larger datasets in ways that many other AI approaches have not. This is one of the advantages deep learning has over other AI approaches, and it means that systems concerns have renewed importance for modern AI. In this class, we’ll be covering two papers that I was involved with that showed techniques for scaling deep learning training and deployment. We’ll be discussing the fundamental ways of parallelizing the training process, their limitations, and the future of systems for deep learning.

### Bio
Bryan Catanzaro leads a team solving problems in fields ranging from video games to chip design using deep learning. Prior to his current role at NVIDIA, he worked at Baidu with Adam Coates and Andrew Ng to create next generation systems for training and deploying end-to-end deep learning based speech recognition. Before that, he was a researcher at NVIDIA, where he wrote the research prototype and drove the creation of CUDNN, the low-level library now used by most AI researchers and deep learning frameworks to train neural networks. Bryan earned his PhD from Berkeley, where he built the Copperhead language and compiler, which allows Python programmers to use nested data parallel abstractions efficiently. He earned his MS and BS from Brigham Young University, where he worked on computer arithmetic for FPGAs.

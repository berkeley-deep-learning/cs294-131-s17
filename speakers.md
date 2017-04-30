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

### [Slides](slides/sukthankar-UC-Berkeley-InvitedTalk-2017-02.pdf)

### Bio
Rahul Sukthankar leads exploratory research efforts in the Machine Perception group at Google. He is also an adjunct research professor at CMU’s Robotics Institute and courtesy faculty at UCF. He was previously a senior principal researcher at Intel, a senior researcher at HP/Compaq and a research scientist at Just Research. He received his Ph.D. in Robotics from CMU in 1997 and his B.S.E. in Computer Science from Princeton in 1991.

## Bryan Catanzaro: Scaling Deep Learning

### Abstract
Deep learning benefits from larger datasets in ways that many other AI approaches have not. This is one of the advantages deep learning has over other AI approaches, and it means that systems concerns have renewed importance for modern AI. In this class, we’ll be covering two papers that I was involved with that showed techniques for scaling deep learning training and deployment. We’ll be discussing the fundamental ways of parallelizing the training process, their limitations, and the future of systems for deep learning.

### [Slides](slides/Catanzaro_Berkeley_CS294.pdf)

### Bio
Bryan Catanzaro leads a team solving problems in fields ranging from video games to chip design using deep learning. Prior to his current role at NVIDIA, he worked at Baidu with Adam Coates and Andrew Ng to create next generation systems for training and deploying end-to-end deep learning based speech recognition. Before that, he was a researcher at NVIDIA, where he wrote the research prototype and drove the creation of CUDNN, the low-level library now used by most AI researchers and deep learning frameworks to train neural networks. Bryan earned his PhD from Berkeley, where he built the Copperhead language and compiler, which allows Python programmers to use nested data parallel abstractions efficiently. He earned his MS and BS from Brigham Young University, where he worked on computer arithmetic for FPGAs.

## Aaron Hertzmann: Artistic Stylization and Geometry Processing

### Abstract
I’ll give a survey of two research topics. First, I’ll describe artistic stylization (NPR) methods, including procedural methods, patch-based methods (including Image Analogies), and our recent work in neural stylization. Second, I’ll describe our work in machine learning for geometry processing from noisy artist-created models on the web.

### [Slides](slides/NPR-2017.pdf)

### Bio
Aaron Hertzmann is a Principal Scientist at Adobe. He received a BA in Computer Science and Art/Art History from Rice University in 1996, and a PhD in Computer Science from New York University in 2001, respectively. He was a Professor at University of Toronto for ten years, and has also worked at Pixar Animation Studios, University of Washington, Microsoft Research, Mitsubishi Electric Research Lab, Interval Research Corporation and NEC Research. He is an associate editor for ACM Transactions on Graphics. His awards include the MIT TR100 (2004), a Sloan Foundation Fellowship (2006), a Microsoft New Faculty Fellowship (2006), the CACS/AIC Outstanding Young CS Researcher Award (2010), and the Steacie Prize for Natural Sciences (2010).

## Kate Saenko: Attentive Captioning without Attention: Designing and understanding LSTM-based captioning models

### Abstract
In this talk, I will present models based on Long-Short Term Memory networks which produce natural language descriptions of in-the-wild images and video. The task has important applications in visual indexing, human-robot interaction, and interfaces for the blind. First, I will describe an LSTM encoder-decoder approach that combines visual and audio input to produce captions, achieving 3rd place in the ACM Multimedia 2016 Grand Challenge. Then, I will show how we can explain the model's captions by recovering spatial or spatiotemporal heatmaps. Unlike recent efforts that introduce explicit "attention" layers to selectively attend to certain inputs while generating each word, our approach recovers salient regions without the overhead of explicit attention layers. Aside from providing localization for words/phrases, our method can be used to analyze a variety of existing model architectures and improve their design.

### [Slides](slides/saenko-talk.pdf)

## Diedrik Kingma: Unsupervised Deep Learning with Variational Autoencoders: Recent Advances and Applications

### Abstract
Current deep learning mostly relies on supervised learning: given a vast amount of examples of humans performing tasks such as labeling images or translation, we can teach computers to mimic humans at these tasks. Since supervised methods only focus on modeling the task directly, however, these methods are not particularly efficient: they need much more examples than humans require for learning new tasks. Unsupervised learning lets us model not only the task, but their context, potentially greatly improving data efficiency. We discuss the framework of Variational Autoencoders (VAEs), a principled yet practical approach towards unsupervised deep learning.

We discuss recent advances such as inverse autoregressive flows (IAF), PixelVAE, and combinations with Real NVP. We also discuss current scientific and practical applications of VAEs for semi-supervised learning and artificial creativity, such as image resynthesis and drug discovery.

### [Slides](slides/VAE talk.compressed.pdf)

### Bio
Durk Kingma is a research scientist at OpenAI, working on the intersection of deep learning with Bayesian inference. His contributions include the Variational Autoencoder (VAE), a framework for principled unsupervised deep learning, and Adam, a method for stochastic gradient descent popular for optimizing deep neural networks. He previously worked with Yann LeCun, Max Welling and researchers at DeepMind.

## Jianxiong Xiao: Learning Affordance for Autonomous Driving

### Abstract
Today, there are two major paradigms for vision-based autonomous driving systems: mediated perception approaches that parse an entire scene to make a driving decision, and behavior reflex approaches that directly map an input image to a driving action by a regressor. In this work, we propose a third paradigm: a direct perception based approach to estimate the affordance for driving. We propose to map an input image to a small number of key perception indicators that directly relate to the affordance of a road/traffic state for driving.

Our representation provides a set of compact yet complete descriptions of the scene to enable a simple controller to drive autonomously. Falling in between the two extremes of mediated perception and behavior reflex, we argue that our direct perception representation provides the right level of abstraction. We evaluate our approach in a virtual racing game as well as real world driving and show that our model can work well to drive a car in a very diverse set of virtual and realistic environments.

### Bio
Jianxiong Xiao (a.k.a., Professor X) is the Founder and CEO of AutoX, Inc., a high-tech startup currently in stealth mode. Previously, he was an Assistant Professor in the Department of Computer Science at Princeton University and the founding director of the Princeton Computer Vision and Robotics Labs from 2013 to 2016. He received his Ph.D. from the Computer Science and Artificial Intelligence Laboratory (CSAIL) at the Massachusetts Institute of Technology (MIT) in 2013. Before that, he received a BEng. and MPhil. in Computer Science from the Hong Kong University of Science and Technology in 2009. His research focuses on bridging the gap between computer vision and robotics by building extremely robust and dependable computer vision systems for robot perception. In particular, he is a pioneer in the fields of 3D Deep Learning, Autonomous Driving, RGB-D Recognition and Mapping, Big Data, Large-scale Crowdsourcing, and Deep Learning for Robotics. His work has received the Best Student Paper Award at the European Conference on Computer Vision (ECCV) in 2012 and the Google Research Best Papers Award for 2012, and has appeared in the popular press. Jianxiong was awarded the Google U.S./Canada Fellowship in Computer Vision in 2012, the MIT CSW Best Research Award in 2011, and two Google Faculty Awards in 2014 and in 2015 respectively. He co-lead the MIT+Princeton joint team to participate in the Amazon Picking Challenge in 2016, and won the 3rd and 4th place worldwide. More information can be found at: http://www.jianxiongxiao.com.

## Le Song: Embedding as a Tool for Algorithm Design

### Abstract
Many big data analytics problems are intrinsically complex and hard, making the design of effective and scalable algorithms very challenging. Domain experts need to perform extensive research, and experiment with many trial-and-errors, in order to craft approximation or heuristic schemes that meet the dual goals of effectiveness and scalability. Very often, restricted assumptions about the data, which are likely to be violated in real world, are made in order for the algorithms to work and obtain performance guarantees. Furthermore, previous algorithm design paradigms seldom systematically exploit a common trait of real-world problems: instances of the same type of problem are solved repeatedly on a regular basis, differing only in their data. Is there a better way to design effective and scalable algorithms for big data analytics? 

I will present a framework for addressing this challenge based on the idea of embedding algorithm steps into nonlinear spaces, and learn these embedded algorithms from problem instances via either direct supervision or reinforcement learning. In contrast to traditional algorithm design where every step in an algorithm is prescribed by experts, the embedding design will delegate some difficult algorithm choices to nonlinear learning models so as to avoid either large memory requirement, restricted assumptions on the data, or limited design space exploration. I will illustrate the benefit of this new design framework using large scale real world data, including a materials discovery problem, a recommendation problem over dynamic information networks, and a problem of learning combinatorial algorithms over graphs. The learned algorithms can reduce memory usage and runtime by orders of magnitude, and sometimes result in drastic improvement in predictive performance. 

### [Slides](slides/learning_algorithm.pdf)

### Bio
Le Song is an Associate Professor in the Department of Computational Science and Engineering, College of Computing, and an Associate Director of the Center for Machine Learning, Georgia Institute of Technology. He received his Ph.D. in Machine Learning from University of Sydney and NICTA in 2008, and then conducted his post-doctoral research in the Department of Machine Learning, Carnegie Mellon University, between 2008 and 2011. Before he joined Georgia Institute of Technology in 2011, he was a research scientist at Google briefly. His principal research direction is machine learning, especially nonlinear models, such as kernel methods and deep learning, and probabilistic graphical models for large scale and complex problems, arising from artificial intelligence, network analysis, computational biology and other interdisciplinary domains. He is the recipient of the Recsys’16 Deep Learning Workshop Best Paper Award, AISTATS'16 Best Student Paper Award, IPDPS'15 Best Paper Award, NSF CAREER Award’14, NIPS’13 Outstanding Paper Award, and ICML’10 Best Paper Award. He has also served as the area chair or senior program committee for many leading machine learning and AI conferences such as ICML, NIPS, AISTATS, AAAI and IJCAI, and the action editor for JMLR.

## Alexander Rush: Attention, Seq-to-Seq, and Language Structure

### Abstract
Recent deep learning systems for NLP and related fields have relied heavily on the use of neural attention, which allows models to learn to focus on selected regions of their input or memory. The use of neural attention has proven to be a crucial component for advances in machine translation, image captioning, question answering, summarization, end-to-end speech recognition, and more. In this talk, I will give an overview of the current uses of neural attention and memory, describe how the selection paradigm has provided NLP researchers flexibility in designing neural models, and demonstrate some applications of this approach. I will then argue that selection-based attention may be an unnecessarily simplistic approach for NLP, and discuss our recent work on Structured Attention Networks [Kim et al 2017]. These models integrate structured prediction as a hidden layer within deep neural networks to form a variant of attention that enables soft-selection over combinatorial structures, such as segmentations, labelings, and even parse trees. While this approach is inspired by structured prediction methods in NLP, building structured attention layers within a deep network is quite challenging, and I will describe the interesting dynamic programming approach needed for exact computation. Experiments test the approach on a range of NLP tasks including translation, question answering, and natural language inference, demonstrating improvements upon standard attention in performance and interpretability.

### Bio
Alexander "Sasha" Rush is an Assistant Professor at Harvard School of Engineering and Applied Sciences where he runs the HarvardNLP group. Alexander received his PhD from MIT (2014) under the guidance of Michael Collins and worked as a postdoc at Facebook Artificial Intelligence Research (FAIR) under Yann LeCun. He is interested in machine learning and deep learning methods for large-scale natural language processing and understanding, including applications in neural machine translation (http://opennmt.net), abstractive summarization, image-to-text prediction, and long-form generation. His past work introduced novel combinatorial methods for structured prediction with applications to syntactic parsing and machine translation. His work has received three best paper/honorable mention awards at major NLP conferences. His group web page is http://nlp.seas.harvard.edu/, and he tweets at http://twitter.com/harvardnlp.

## Sanjeev Arora: Generalization and Equilibrium in Generative Adversarial Nets (GANs)

### Abstract
This paper makes progress on several open theoretical issues related to Generative Adversarial Networks. A definition is provided for what it means for the training to generalize, and it is shown that generalization is not guaranteed for the popular distances between distributions such as Jensen-Shannon or Wasserstein. We introduce a new metric called neural net distance for which generalization does occur. We also show that an approximate pure equilibrium in the 2-player game exists for a natural training objective (Wasserstein). Showing such a result has been an open problem (for any training objective).

Finally, the above theoretical ideas lead us to propose a new training protocol, MIX+GAN, which can be combined with any existing method. We present experiments showing that it stabilizes and improves some existing methods.

### [Slides](slides/arora-talk.pptx)

## Bryan Russell: ActionVLAD: Learning spatio-temporal aggregation for action classification

### Abstract
In this talk I will describe ActionVLAD, a new video representation for action classification that aggregates local convolutional features across the entire spatio-temporal extent of a video.  The resulting architecture is end-to-end trainable for whole-video classification. We show that our representation outperforms a two-stream base architecture by a large margin (13% relative) as well as outperforms other baselines with comparable base architectures on the public HMDB51, UCF101, and Charades video classification benchmarks.

### Bio
Bryan Russell is a Research Scientist at Adobe Research in San Francisco.  He received his Ph.D. from MIT in the Computer Science and Artificial Intelligence Laboratory under the supervision of Professors Bill Freeman and Antonio Torralba. He was a post-doctoral fellow in the INRIA Willow team at the Département d'Informatique of Ecole Normale Supérieure in Paris, France. He was a Research Scientist with Intel Labs as part of the Intel Science and Technology Center for Visual Computing (ISTC-VC) and was Affiliate Faculty at the University of Washington.

---
title: "Context Aware Data Reduction for Highly Automated Driving"
collection: publications
category: books
permalink: /publication/2024-02-20-context_aware_data_reduction
excerpt: 'A novel method to data reduction for the usage in highly automated driving'
date:  2024-02-20
#venue: 'Accident Analysis & Prevention'
slidesurl: 'http://kai-storms.github.io/files/2024-02-20-context_aware_data_reduction-slides.pdf'
paperurl: 'http://kai-storms.github.io/files/2024-02-20-context_aware_data_reduction.pdf'
citation: '<b>Storms K.</b>, "Context Aware Data Reduction for Highly Automated Driving," (2024) Dissertation, Darmstadt.

---

 	
This research addresses the emerging challenge of data handling in the development of automated driving systems. The increasing volumes of data generated in the development and operation of these systems necessitate efficient handling strategies. A comprehensive review of the current state of the art reveals data reduction as a viable solution to manage these large data volumes. Further, an analysis of the state of the art establishes various challenges where established methodologies are insufficient, such as the open context. This leads to the primary research question of this dissertation:

(1) how to effectively implement data reduction while addressing these challenges. 

The proposed solution in this work is a novel data reduction approach that integrates the concept of relevance, aiming to precisely define the informational needs within the data. This approach hypothesizes an enhanced control over performance loss in subsequent use cases, leading to two secondary research questions:

(2) How can relevance be formally defined to facilitate its use in data reduction?

(3) What is the impact of this data reduction method on the performance of subsequent use cases?

To answer the second question, the concept of relevance is extensively explored in the literature. A general relevance model for automated driving is developed, along with a methodology for deriving and validating use case-specific relevance models. Application of this methodology to a selected use case demonstrates its effectiveness. Addressing the third question, an architecture for relevance-guided data reduction is proposed. A prototype implementing this architecture is evaluated in the contexts of perception and neural network training, focusing on semantic segmentation and object detection tasks. The findings indicate that relevance-guided data reduction can effectively control performance loss in perception tasks. However, in neural network training, a strong task dependency is observed, highlighting limitations of the approach and opportunities for future research. In conclusion, this work represents a contribution in two areas. First, to overcoming the challenges of handling large amounts of automotive data and reducing this data to only those parts with relevant information. Second, to an explicit consideration of the wide variety of relevance concepts in the development of automated driving.
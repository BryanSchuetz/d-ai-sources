---
title: Reflections on Machine Learning for Gender Inclusion in Afghanistan
date: 2020-12-03 06:00:00 -05:00
published: false
categories:
- Information
- Innovation
tags:
- Machine Learning
- Afghanistan
Author: Greg Maly
social-image: "/uploads/AI%202%20copy%20(002).jpg"
thumbnail: "/uploads/AI%202%20copy%20(002).jpg"
---

This past summer, DAI’s [Promote: Women in the Economy (WIE)](https://www.dai.com/our-work/projects/afghanistan-women-in-the-economy) project came to an end. Funded by the U.S. Agency for International Development, the project bolstered women’s inclusion in Afghanistan’s economy through technical assistance, access to finance, and business training. In 2016, our team [wrote](https://dai-global-digital.com/machine-learning-will-help-development-projects-achieve-scale.html) about the possibility of leveraging machine learning to “automate the alignment of unstructured CVs and resumes with available jobs, thereby facilitating the Afghan women's access to employment opportunities.” Four years later, this use case for machine learning is one of our favorite examples. We reflect on five lessons from this initiative, and how we can translate its success into future endeavors.

<!--more-->

## Lesson 1: Define a Clear Use Case

The first lesson is the most obvious, but also the most challenging, and that is to have a clear use for machine learning. Despite the term “artificial intelligence,” computers are not smart, however, they can process repetitive jobs quickly. To this end, machine learning is best used to handle clear, replicable tasks. Many of these tasks go sight unseen in the technologies that we use every day, changing our user experience based on our behavior. And while machine learning use cases are mature in the world of e-commerce, social media, and [remote sensing](https://dai-global-digital.com/visualizing-remotely-sensed-data-true-color-and-false-color.html), there are fewer high-impact examples for projects that relate to governance, economics, agriculture, health, and others. Identifying a clear way to leverage machine learning is a challenge.

The WIE program used machine learning to handle a clear, repetitive task—that of reading and classifying resumes by job type. This method of machine learning uses what is known as feature extraction and natural language processing (NLP). After training the machine learning model, our algorithm was integrated with a database of resumes and job openings. Each day, our algorithm read and tagged resumes and available jobs, tagging them by a pre-defined set of occupations, and providing recommendations to a team of people who engage job seekers on professional development opportunities.

![WIE ML Classifier.png](/uploads/WIE%20ML%20Classifier.png)

## Lesson 2: Gather or Create a Clean, Robust Dataset

This type of tool can feel like magic but is ultimately based on a simple set of concepts that rely on pre-existing data. Machine learning can broadly be broken down into two categories—supervised and unsupervised. Unsupervised machine learning is used to detect patterns in a dataset with no pre-existing labels. In this case, you feed the computer some information and ask it to identify groupings (or patterns) of information and to provide you with a summary of the results. Supervised learning, on the other hand, requires that you feed the computer training data. In this case, you want to teach the computer how to act.

In our case, we leveraged supervised machine learning to classify resumes based on a pre-defined taxonomy. In other words, we knew how we wanted the computer to behave, so we trained it accordingly. To achieve this type of behavior, we tagged more than 1,000 regionally appropriate resumes, and provided them to the computer. Over time, the computer learned to interpret the resume text with a high degree of accuracy and provided us results that aligned with our needs. Without lots of resumes relevant our use case, this would not have been possible.

## Lesson 3: Engage Stakeholders Throughout the Process

Ultimately, a computer-based intelligence like this is designed to support a process, and processes involve people. Therefore, you’ll need to spend a good amount of time talking with those involved in the process about their needs. How would users like to receive information? Are there existing database systems that they use? What happens if the algorithm does not provide outputs that align with their expectations? These are all questions that need be considered throughout the lifecycle of the project.

In our case, we worked closely with staff responsible for professional development, and technical staff who managed a large database of resume information. We designed the system to integrate with their workflow, and to mirror their decision-making process. This involved everything from reviewing how staff accessed information, involving them in the tagging process, and checking back in regularly to ensure the system was meeting their needs.

The other critical stakeholder group are those responsible for integrating the machine learning tool into a broader technical workflow. Many machine learning tools live in the background of a user interface, making decisions that change the user experience. This was the case on WIE, which maintained a large knowledge management portal (KMP) with information on job seekers. Once we developed the machine learning model, we created an application programming interface (API), which allowed the developers of the KMP to use the model and use it as a dedicated function. Doing this required regular interaction between data science and web development staff.

## Lesson 4: Beware of Algorithmic Bias

Machine learning algorithms trained by people will learn to think and make decisions like those very same people. This can be a good thing, but it can also have negative consequences. My colleague [Gratiana Fu](https://dai-global-digital.com/authors/gratiana-fu/) wrote a great [article](https://dai-global-digital.com/algorithms-in-development.html) on this topic not long ago, and highlighted a case where, due to bias in the training data, mobile phone-based image classifiers were more accurate at detecting skin cancer on people with white skin than those with black or brown skin. To prevent this sort of bias, she made four recommendations, including to diversify technical staff, use appropriate training data, question the need for automation altogether, and to raise your individual awareness of algorithms.

On WIE, we took steps to try to mitigate negative consequences as a result of our work. First, the machine learning algorithm was never involved in deciding whether someone should receive job training. The algorithm served to aid in an inclusive process. Second, the training data was collected and tagged by staff on the project, as opposed to by our technical team. This ensured a diversity of perspectives went into the training data. Finally, we maintained open communication with project staff, checking back in to make sure that the model was providing high-quality expected results.

## Lesson 5: Use Machine Learning to Support People, Not Replace Them

Science fiction often depicts artificial intelligence as becoming more powerful than humans. While this may be the case sometime in the future, that is not the case today. As noted up top, computers are best suited to process repetitive jobs quickly, supporting pre-existing workflows, and ultimately, people. While we could have hired dozens of people to sift through and read resumes day after day, this type of task is well suited for computers, and thus enabled our staff to focus on something a computer still cannot achieve—and that’s maintaining relationships with people.

## Looking Ahead

As a technology team, we always strive to find ways to integrate new tools and methods into our work and to share our lessons and experiences with the broader community. We are proud of the work DAI supported through WIE and were honored to be able to support this work by creating time-saving efficiencies through technology. As we live in an increasingly digital world, machine learning will undoubtedly continue to play a role in facilitating the management of data and information. We hope that examples like this provide some insight into how to use machine learning in a clear and ethical way.
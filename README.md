# Mathematical Formula Markup Generation for Collaborative Q&A Sites
Collaborative editing questions and answers plays an important role in quality control in Mathematics Stack Exchange which is a math Q&A Site. Our study of post edits in Mathematics Stack Exchange shows that a large number of edits are about converting the blurred math formula screenshots to LaTeX sequence which is further rendered to display math with better readability and accessibility. Despite its importance, editing one formula screenshot into LaTeX is time-consuming and error-prone even for experienced users. 
To assist post owners and editors to do this editing, we have developed an edit-assistance tool, MathFormGen, to generate the LaTeX sequences, given the formula screenshot. We formulate this formula editing task as a translation problem, in which an original image is translated to a LaTeX sequence. MathFormGen implements a deep learning based approach including an encoder-decoder model with domain-specific inference and visualization. 
It is trained on 1 million screenshot-formula pairs which are synthesized with LaTeX formulas collected from Mathematics Stack Exchange. Our evaluation of MathFormGen not only demonstrates the accuracy of our model, but also the usefulness of MathFormGen in editing real-world posts which are accepted in Mathematics Stack Exchange.

## COLLABORATIVE EDITING ANALYSIS OF MATHEMATICS STACK EXCHANGE
We downloaded the latest data dump of Mathematics Stack Exchange which contains 2,886,174 posts (including 1,216,368 questions and 1,669,806 answers) and all post edits since its launch on July 20, 2010 to March 1, 2020. Based on this large dataset, we carried out an empirical study of post edits in Mathematics Stack Exchange to understand the characteristics of post editing in Mathematics Stack Exchange and to motivate the required tool support.

<div style="color:#0000FF" align="center">
<img src="figures/figure1.pdf"/> 
<figcaption>Fig. 1. The numbers of posts and three kinds of post edits in each year in Mathematics Stack Exchange
</figcaption>
</div>

**Pranav Kumarsubha**  
pkumarsubha@ucsd.edu

**Section & Mentor**  
Section: A02
Mentor: Dr. Rajesh Gupta



## 1. What is the most interesting topic covered in your domain this quarter?  
The topic that I found the most interesting was how approximate arithmetic, such as the L-Mul algorithm, can significantly reduce the hardware computation cost while still achieving competitive accuracy of the model. It was interesting how this topic compared the trade-off of numerical precision, efficiency, and downstream ML performance, all of which contributed to a relationship between the hardware design and machine learning outcome. I was surprised by the fact that everything is really centered around optimization. The L-Mul algorithm was a unique way of finding that optimization compared to what I would typically look at for optimization or what I've covered in class and that is why exploring this new area was very eye-opening.

## 2. Describe a potential investigation you would like to pursue for your Quarter 2 Project?
We are currently just trying to test ouf if L-Mul is useful and if we can replicate the tests and code. I would want to look into the impact of L-Mul on gradient, convergence speeds, and training stability under various parameters. This will help understand whether L-Mul can be utilized throughout the complete ML pipeline, or only for inference and open the possibility to more parts of the process we can find and tune.

## 3. What is a potential change you’d make to the approach taken in your current Quarter 1 Project? 
One change I might consider making is to evaluate L-Mul in a more complex neural architecture, such as a transformer or an LSTM, rather than using only an MLP, to determine if the preservation of accuracy observed generalizes beyond the simpler MNIST classification, and can provide more informative insights. We did take some time to get into the Hardware side and I would try to speed up this process by finding out more information early on by contacting leads from last year's project.

## 4. What other techniques would you be interested in using in your project?
I’d also be interested in exploring model compression and distillation methods I learned in one of my internships such as quantization-aware training or knowledge distillation to see how simpler models perform compared to standard full-precision models. It would be interesting to test whether combining these ML efficiency solutions with L-Mul can preserve accuracy and reduce computation.

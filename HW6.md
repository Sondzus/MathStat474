---
output:
  html_document: default
  pdf_document: default
---
# MathStat474 - HW 6

> Posted Wed 18 Feb. **Due: Thu Feb 26.** 


<!-- 
### Problem 1. 

(Applying the concepts of a random variable and its mean.)

The Acme Shipping Company has learned from experience that it costs $14.80 to deliver a small package overnight. 
The company charges $20 for such a shipment,  but guarantees that they will refund the $20 charge if it does not arrive within 24 hours.

Let X be a discrete random variable representing the outcomes for the Acme Shipping Company. What are the possible values for X?

Suppose Acme successfully delivers 96% of its packages within 24 hours. What are the probabilities that correspond to the values for X you found in the previous question?

Using the information from the previous two questions, what is the expected gain or loss for delivering a package?



### Problem 2. 

The probabilities that a service station will pump gas into 0, 1, 2, 3, 4, or 5 or more cars during a certain 
30-minute period are 0.03, 0.18, 0.24, 0.28, 0.10, and 0.17, respectively. 

Find the probability that in this 30-minute period: 

(a) more than 2 cars receive gas; 
(b) at most 4 cars receive gas; 
(c) 4 or more cars receive gas.
--> 

<!-- 
### Problem 3. 

Solve exercise **2.108** in the textbook: 

If the probability is 0.1 that a person will make a mistake on his or her state income tax return, find the probability that

(a) four totally unrelated persons each make a mistake;
(b) Mr. Jones and Ms. Clark both make mistakes, and Mr. Roberts and Ms. Williams do not make a mistake.
--> 

### Problem 1. 

Suppose that you work for an insurance company and you sell a $100,000 fire insurance policy at an annual premium of $1,350. Experience has shown that:

The probability of total loss (due to fire) to a house in that area and of the size of your customer's house is .002 (in which case the insurance company will pay the full $100,000 to the customer).

The probability of 50% damage (due to fire) to a house in that area and of the size of your customer's house is .008 (in which case the insurance company will pay only $50,000 to the customer).

For simplicity, we'll ignore any other partial losses.

Let the random variable X be the insurance company's annual gain from such a policy (i.e., the amount of money made by the insurance company from such a policy).

a) Find the probability distribution of X. In other words, list the possible values that X can have, and their corresponding probabilities. (Hint: There are three possibilities here: no fire, total loss due to fire, 50% damage due to fire).

b) What is the mean (expected) annual gain for a policy of this type? In other words, what is the mean of X?

c)  The insurance company gets information about gas leakage in several houses that use the same gas provider that your customer does. In light of this new information, the probabilities of total loss and 50% damage (that were originally .002 and .008, respectively) are tripled (to .006 for total loss and .024 for 50% damage). Obviously, this change in the probabilities should be reflected in the annual premium, to account for the added risk that the insurance company is taking. What should be the new annual premium (instead of $1,350), if the company wants to keep its expected gain of $750?

 **Guidance**: Let the new premium (instead of 1,350) be denoted by N, for new. Set up the new probability distribution of X using the updated probabilities, and using N instead of 1,350. (The answer to question 1 will help.)
The question now is: What should the value of N (the new premium) be, if we want the mean of X to remain 750?
Set up an equation with N as unknown, and solve for N.

### Problem 2. 

A manufacturing company uses an acceptance scheme on items from a production line before they are shipped. The plan is a two-stage one. Boxes of 25 items are readied for shipment, and a sample of 3 items is tested for defectives. If any defectives are found, the entire box is sent back for 100% screening. If no defectives are found, the box is shipped.

(a) What is the probability that a box containing 3 defectives will be shipped?
(b) What is the probability that a box containing only 1 defective will be sent back for screening?


### Problem 3. 

Find the probability that a person flipping a coin gets

(a) the third head on the seventh flip; 
(b) the first head on the fourth flip.


### Problem 4. 

Three people toss a fair coin and the odd one pays for coffee. If the coins all turn up the same, they are tossed again. Find the probability that fewer than 4 tosses are needed.

### Problem 5. 

The manufacturer of a tricycle for children has received complaints about defective brakes in the product. According to the design of the product and considerable preliminary testing, it had been determined that the probability of the kind of defect in the complaint was 1 in 10,000 (i.e., 0.0001). 

After a thorough investigation of the complaints, it was determined that during a certain period of time, 200 products were randomly chosen from production and 5 had defective brakes.

(a) Comment on the “1 in 10,000” claim by the manufacturer. Use a probabilistic argument. Use the binomial distribution for your calculations.

(b) Repeat part (a) using the Poisson approximation. 

### Problem 6. 

Solve Exercise **4.10.84**: 

Suppose that lesions are present at 5 sites among 50 in a patient. A biopsy selects 8 sites randomly (without replacement).

(a)
What is the probability that lesions are present in at least one selected site?


(b) What is the probability that lesions are present in two or more selected sites?


(c) 
Instead of eight sites, what is the minimum number of sites that need to be selected to meet the following objective? The probability that at least one site has lesions present is greater than or equal to 0.9.



---

---


### Typing up work 

If you *want* to type up your homework, I suggest you don't use Microsoft Word or the like. You can get great formatted documents in Markdown! Check out the links below. 
But whatever you use, please make sure your submission is either a PDF document, a photo of the document, or a nicely formatted text document. 

Get familiar with professionally formatting documents using Markdown [here](https://sondzus.github.io/MathStat474/DocumentFormattingGuidelines.html). 
Want more information? Simple .md templates for PDF documents are available [here](https://sondzus.github.io/MathStat474/DocumentFormattingGuidelines.html). 

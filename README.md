# Dog-Adoption
This repository contains code I wrote to clean, explore and analyze dog adoption data. The goal of this project was to find factors that influence whether a dog is adopted, and how quickly they are adopted.

## Key Findings
### Factors associated with whether a dog is adopted 

1. Having special needs
   * these dogs are less likely to be adopted and take longer to be adopted than dogs without special needs
     * 60% of dogs with special needs were adopted vs. 70.3% of dogs without special needs


2. Dog size
   * small dogs have higher adoption rates than other sizes of dogs
     * 80.95% of small dogs were adopted
     * 69.88% of medium dogs were adopted
     * 61.96% of large dogs were adopted
     * 42.86% of extra large dogs were adopted


3. Dog age
   * "baby" dogs have the highest adoption rates across all age groups
     *   84.69% of "baby" dogs were adopted
     *   72.28% of younger dogs were adopted
     *   61.13% of adult dogs were adopted
     *   57.63% of senior dogs were adopted


4. Purebred vs. Mixed-Breed
   * purebred dogs have higher adoption rates than mixed-breed dogs
     * 74.64% of purebred dogs were adopted
     * 63.82% of mixed-breed dogs were adopted
    
  

### Factors associated with adoption time

1. Having special needs
   * dogs with special needs have longer average adoption times
   * average adoption times (in days)
     * dogs with special needs: 12.82 days
     * dogs without special needs: 8.24 days


2. Dog size
   * small dogs have the shortest average adoption time
   * average adoption times (in days)
     * small dogs: 7.8 days
     * medium dogs: 8.18 days
     * large dogs: 9.4 days
     * extra large dogs: 9.97 days


3. Dog age
   * "baby" dogs have the shortest average adoption time
   * average adoption times (in days): 
     * "baby" dogs: 7.24 days
     * young dogs: 8.09 days
     * adult dogs: 8.95 days
     * senior dogs: 11.83 days



## Notes
- Dogs with an age of "baby" are puppies. I kept the dataset's initial classification and used this term in my analysis and findings
- I defined adoption time as the time between when a dog's adoption ad is posted and the dog's status is changed
   - an adoption time of 0, means the dog's status hasn't changed and it hasn't been adopted

Data Source: https://www.kaggle.com/datasets/velazquezelsa/petadoption

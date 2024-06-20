# **Pricing-Research**

### **Van Westendorp Price Sensitivity Meter (PSM) method**

**Hypothetical Case:** I am researching the price sensitivity for a new smartwatch.

**My Assumptions:**
- The target audience consists of tech-aware individuals aged 25-40. Tech-aware consumers, particularly those within the 25-40 age range, are likely to be more informed about the latest technological trends and products. Considering this, they are typically familiar with the pricing landscapes of gadgets and can thus provide reliable data on price sensitivity. Based on these, we can assume a normal distribution for price responses among this group. I have done a research, and this distribution is common in consumer surveys where a central tendency reflects an average view in a somewhat homogenous group, so it is often a natural pattern in real-world data on consumer surveys.
- Thus, the synthetic data of price responses that I will generate will follow a normal distribution with some variation.
- Let's assume that the sample size is 300 respondents.

**Questions:**
Participants are asked the following four questions:

- **Too Expensive:** At what price would you consider the product to be too expensive and would not consider buying it?
- **Too Cheap:** At what price would you consider the product to be so cheap that you would question its quality and not buy it?
- **Expensive:** At what price would you consider the product to be expensive but still buy it?
- **Cheap:** At what price would you consider the product to be a bargain, getting a good deal for the price?

**Implementation:**
You can find the full python implementation of the **Van Westendorp Price Sensitivity Meter (PSM) method** in `Van-Westendorp.ipynb` notebook.
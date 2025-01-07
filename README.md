# Understanding Product Relationships Using Association Rule Learning

## Project Overview

### Context
Our client is looking to re-jig the alcohol section within their store. Customers are often complaining that they can’t find the products they want, and are also wanting recommendations about which other products to try. On top of this, their marketing team would like to start running “bundled” promotions as this has worked well in other areas of the store - but need guidance with selecting which products to put together.

They have provided us a sample of 3,500 alcohol transactions - our task is fairly open - to see if we can find solutions or insights that might help the business address the aforementioned problems!

### Actions
Based upon the tasks at hand - we apply Association Rule Learning, specifically Apriori to examine & analyse the strength of relationship between different products within the transactional data.

We firstly installed the apyori package, which contains all of the required functionality for this task.

We then needed to bring in the sample data, and get it into the right format for the Apriori algorithm to deal with.

From there we apply the Apriori algorithm to provide us with several different relationship metrics, namely:

- Support
- Confidence
- Expected Confidence
-Lift
These metrics examine product relationships in different ways, so we utilise each to put forward ideas that address each of the tasks at hand. You can read more about these metrics, and the Apriori algorithm in the relevant section below.

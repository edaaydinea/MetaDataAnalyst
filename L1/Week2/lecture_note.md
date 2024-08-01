# Obtaining and Scrubbing Data

## Introduction: Obtaining and Scrubbing Data

### Focus of the Week:

- **Steps in the OSEMN Model:**
    - Obtaining Data
    - Scrubbing Data

### Key Points:

1. **Data Analytics Project Initiation:**
    - Sometimes data is provided.
    - Other times, data is needed to prove a hypothesis, assumption, or expectation.
2. **Data Sources:**
    - Various data sources available, often free.
    - Importance of knowing which sources to focus on.
3. **Lesson 1: Obtaining Data:**
    - Exploration of where data analysts find data.
    - Overview of available data sources.
4. **Lesson 2: Scrubbing Data:**
    - Methods for cleaning data.
    - Preparing data for analysis.
5. **Lesson 3: Practical Example:**
    - Illustration of obtaining and scrubbing data using an example.

### Objective:

- Learn how to find and clean data for analysis.
- Understand the initial steps in the OSEMN model.

### Action:

- Dive into the world of data, starting with obtaining and scrubbing data.

## It’s a Data World

### Importance of Data:

- Constantly surrounded by vast amounts of data.
- Types of data include:
    - Purchases
    - Online browsing behavior
    - Financial transactions
    - Demographics
- Data can answer questions and solve problems with the right tools and techniques.
- Data is a valuable resource for businesses and individuals.
- Data analysts play a crucial role in transforming data into valuable resources.

### Framework for Data Questions:

- **Framework:** Awesome (Obtain, Scrub, Explore, Model, Interpret)

### Focus of the Lesson:

- **First Step:** Obtaining data
- **Topics Covered:**
    - Different sources of data:
        - First-party data
        - Third-party data
        - Sampled data
        - Nonsampled data
    - Data formats
    - Where to look for data
    - Evaluating and weighing the validity of data sources

### Lesson Objective:

- Understand how to obtain the right data for analytics objectives and business goals.

## Where to Look for Data

### Obtaining Data for Data Analytics

### Overview of Data Sources:

- **Three Buckets of Data Sources:**
    1. Freely accessible, open-source databases
    2. Company-specific data (not freely accessible)
    3. Data intentionally collected to solve a problem

### Freely Accessible, Open-Source Databases:

- Examples of sources:
    - Government websites
    - Open-source repositories
    - Databases providing socioeconomic data (population demographics, household income, education, etc.)
- **Example:** Eurostat
    - Provides access to official statistics from the European Union.
    - Offers economic and social data for different countries over many years.
    - Features a data browser for easier filtering and analysis.
- **Example:** OECD (Organization for Economic Cooperation and Development)
    - Offers up-to-date data on socioeconomic topics.
    - Data can be browsed, filtered, and downloaded for analysis.
- **Other Examples:**
    - World Bank
    - United Nations
    - US Census Bureau
- **Action:** Check available data and explore the different graphs and analyses these organizations offer.

### Company-Specific Data:

- **Types:**
    - Data collected and stored by the company.
    - Data from subscribed databases.
- **Example:** Google Analytics
    - Monitors website usage (pages visited, visit frequency, products added to shopping cart, etc.)
    - Specific to the company and not accessible by others.
- **Example:** Proprietary data systems (e.g., telephone company data on customer usage).
- **Example:** Subscribed databases (e.g., Nielsen data, Bloomberg terminal).
- **Action:** Explore the databases your company has access to for answering analytics questions.

### Intentionally Collected Data:

- **Methods:**
    - Creating questionnaires or surveys.
    - Organizing interviews with customers.
    - Observing and recording customer behavior.
- **Tools for Data Collection:**
    - SurveyMonkey: Provides templates for creating questionnaires.
    - Google Forms: Allows quick data collection with online questionnaires.
- **Action:** Plan and collect the data you need if it is not already available.

### Summary:

- **Steps to Obtain Data:**
    1. Research free data sources.
    2. Check company-specific data access.
    3. Create a plan to collect the required data if necessary.

### Conclusion:

- Reflect on how to obtain data for your analytics project.
- Explore all available resources and plan accordingly to ensure you have the right data to answer your questions and meet business goals.

## Common Data Formats

### Overview:

- Data comes in various formats beyond just numbers.
- Different formats are useful depending on the analysis goal.

### Numeric Data:

- **Definition:** Also known as quantitative data, expressed in numerical form, measurable or countable.
- **Examples:**
    - Age (e.g., 25, 52)
    - Income (monetary amounts)
    - Sales figures (units sold, revenue generated)
    - Stock prices (currencies such as dollars)
- **Storage:** Typically stored in tabular or spreadsheet format, often saved as .CSV files.
- **Features:**
    - Cells arranged in rows and columns
    - Easy access to specific information
    - Efficient sorting and filtering

### Text Data:

- **Definition:** Also known as unstructured data, in written or textual form.
- **Examples:**
    - Social media posts
    - Emails
    - Tweets
    - Blog posts
    - Customer reviews
- **Analysis:** Often analyzed using natural language processing (NLP) techniques.
- **Applications:**
    - Sentiment analysis to determine customer feelings about products or services.
    - Tools to understand customer preferences and behaviors.

### Visual Data:

- **Definition:** Data presented in a visual format, such as images and videos.
- **Examples:**
    - Photos
    - Drawings
    - Videos
    - Geographical maps
- **Applications:**
    - Quality control in manufacturing: analyzing images for defects or variations.
    - Self-driving vehicles: cameras capture images to train machine learning algorithms.
    - Medical imaging: informs about the human body, aiding in disease research and treatment.

### Key Takeaway:

- **Data Variety:** Data comes in many forms (numeric, text, visual).
- **Utility:** All data formats can be useful depending on the analytics question being addressed.

## Sampled Data

### Definition:

- **Sampled Data:** A subset of a larger population or data set used to represent the entire group.
- **Purpose:** Allows conclusions about the population while analyzing a fraction of it, saving cost and time.

### Situations Necessitating Sampled Data:

1. **Large Population:**
    - Analyzing the entire data set is impractical or impossible.
    - Example: A market researcher for an auto manufacturer surveys a sample of customers to gauge satisfaction due to the impracticality of surveying hundreds of thousands of car owners.
2. **Cost Constraints:**
    - Collecting data from the entire population is expensive.
    - Example: Sending surveys to a smaller group of customers to save money on distribution and incentivization.
3. **Time Constraints:**
    - Collecting and analyzing data from the entire population is time-consuming.
    - Example: Surveying a smaller group allows quicker data collection and analysis for the auto manufacturer.
4. **Destructive Sampling:**
    - Analyzing the entire population results in its destruction.
    - Example: Testing every product in a candy factory would destroy the inventory.

### Considerations When Using Sampled Data:

1. **Sample Size:**
    - Larger sample sizes generally provide more accurate population estimates.
    - Small sample sizes may not accurately represent the population and limit analysis types.
2. **Representativeness:**
    - The sample should accurately reflect the population.
    - **Example of Bias:**
        - Surveying only finance department employees to determine a company's average salary biases results. A more random sample including different departments and positions ensures representativeness.
3. **Generalizability:**
    - Conclusions drawn from the sample might not apply to other populations.
    - **Example:**
        - Surveying students from one university to study eating habits may not generalize to all college students due to differences in demographics and socioeconomic statuses.

### Conclusion:

- **Utility:** Sampled data is effective for handling large populations or data sets.
- **Caution:** Ensure the sample size is adequate, representative, and generalizable to draw valid conclusions.

## First and Third Party Data

### First Party Data

- **Definition:** Data gathered directly by a business from its own customers, website visitors, or other internal sources.
- **Characteristics:**
    - Direct control over collection and source.
    - High reliability and validity since the company knows the data's origin.
- **Common Examples:**
    - **Website Usage Statistics:** Information on how users interact with a company's website (e.g., page visits, time spent on pages), typically collected using tools like Google Analytics.
    - **Point-of-Sale (POS) Purchase Information:** Data from physical retail stores during customer transactions.
    - **Customer Feedback Surveys:** Information collected via surveys through email or in-store questions.

### Third Party Data

- **Definition:** Data gathered by external parties that are not affiliated with the business.
- **Characteristics:**
    - Less control over the collection process and source.
    - Useful for broader market insights and competitive analysis.
- **Common Examples:**
    - **Government Census or Demographic Data:** Population characteristics (e.g., age, gender, race) by geographic region.
    - **Behavioral Patterns and Customer Habits:** Data on purchasing behavior and preferences over time, collected by market research firms.
    - **Economic Indicators:** Metrics such as GDP growth rates, unemployment rates, and inflation rates, provided by government agencies.

### Importance of Knowing Data Sources

- **Validity and Reliability:** Understanding whether data is first party or third party helps in assessing its quality.
- **Collection Methods:** Knowing the collector helps evaluate how the data was gathered, which influences its accuracy and relevance.

By understanding the distinctions between first party and third party data, data analysts can better evaluate the quality of the data they use and make informed decisions based on that data.

## Evaluating the Validity of Data Resources

### 1. Source Credibility

- **Authorship:** Verify if the data comes from a reputable author or organization with the right credentials.
- **Publication Date:** Ensure the data is current and up-to-date. Old data might not be relevant to today's context.

### 2. Methodology

- **Sample Size:** Check if the sample size is adequate to represent the larger population.
- **Sampling Method:** Ensure the sampling method is unbiased and representative.
- **Data Collection Method:** The data collection process should be clearly described and appropriate for the study.
- **Objectivity:** Data should be collected objectively without any obvious biases. Avoid data collected to confirm a hypothesis rather than evaluate it.
- **Conflict of Interest:** Be aware of any potential conflicts of interest. Data from biased sources (e.g., a pharmaceutical company evaluating its own drug) might not be reliable.

### 3. Accuracy

- **Consistency:** Check if the data is consistent with data from other reputable sources.
- **Obvious Errors:** Look for errors or anomalies, such as impossible values (e.g., negative weights) or implausible data points (e.g., extreme temperatures in unlikely locations).

### 4. Relevance

- **Scope:** Ensure the data is relevant to the question at hand.
- **Context:** The data should come with background information, explanations on how it was collected, and any relevant details to help understand and interpret it.

### Example Evaluation: Climate Change Data

- **Credibility:** If the source is a blog with no credentials or affiliations to reputable organizations and the data is outdated (e.g., from 2015), it's not a credible source.
- **Methodology:** If the sample size and sampling technique are not mentioned and the data collection methods are unclear, the methodology is unreliable.
- **Objectivity:** If the source shows clear bias and lacks transparency regarding conflicts of interest, the data is likely biased.
- **Accuracy:** If the data contradicts reputable sources like NASA, it's inaccurate.
- **Relevance:** If the data fits the research topic but lacks meaningful context or explanation, it's not fully reliable.

Based on the checklist, you would likely discard such a data set and look for more reputable sources. This process helps ensure that the data you use is valid and reliable, reducing the chances of issues during your analysis.

# Scrubbing Data

## Scrubbing Your Data Clean

### The Importance of Data Scrubbing

Data scrubbing, or cleaning, is the process of transforming raw, dirty data into clean, usable data. It is essential for ensuring the accuracy and reliability of your analysis and modeling. Without this step, errors in your data can lead to incorrect conclusions or impede your analysis.

### Key Tasks in Data Scrubbing

### 1. Removing Duplicates

Duplicate records can skew your analysis by giving certain data points more weight than they should have. Removing these duplicates ensures each data point is represented only once.

**Example:** In a customer database, if a customer has multiple entries with the same name and email, these should be merged into a single record.

### 2. Formatting Records

Consistent formatting is crucial for efficient data processing and analysis. This includes standardizing date formats, ensuring numerical values are consistent, and correcting text case issues.

**Example:** Dates might appear as "MM/DD/YYYY" in some records and "DD-MM-YYYY" in others. Standardizing all dates to a single format is necessary for accurate analysis.

### 3. Solving for Missing Values

Missing values can disrupt analysis and modeling processes. Handling these appropriately, whether by imputing values, using placeholders, or removing incomplete records, is necessary.

**Example:** If a dataset contains missing age values for some entries, you might fill these gaps using the average age or median age of the dataset, depending on the context.

### 4. Checking Records for Mistakes or Wrong Values

Detecting and correcting errors in your data is vital for maintaining data integrity. This includes identifying outliers, impossible values, or inconsistencies.

**Example:** If you find a temperature value recorded as "500°C" in a weather dataset, it's likely an error since such a value is unrealistic for the given context.

### The Scrubbing Process: An Example

### Scenario: Cleaning a Customer Survey Dataset

1. **Removing Duplicates:** You identify and remove multiple entries for the same customer.
2. **Formatting Records:** Standardize date entries to "YYYY-MM-DD", ensure all email addresses are in lowercase, and format phone numbers consistently.
3. **Solving for Missing Values:** Impute missing income data using the median income of the survey respondents.
4. **Checking for Mistakes:** Correct any obvious errors such as negative ages or implausible income values.

By following these steps, you ensure that your data is ready for the subsequent phases of the OSEMN framework: exploring, modeling, and interpreting. Clean data is foundational for reliable analysis and accurate insights.

## Remove Duplicate Records

- **Problem with Duplicates:**
    - Distort analysis by giving certain data points undue weight.
- **Reasons for Duplicates:**
    - **Human Error:**
        - Entering the same information multiple times.
        - Accidentally copying data while saving or moving files.
    - **Machine Error:**
        - Errors from human error in designing the machine.
        - Machine malfunction.
- **Example of Duplicate Entry:**
    - Supermarket checkout: Duplicate barcode scans at self-checkout.
        - Correctable by users at checkout.
        - Unnoticed duplicates can affect inventory count and sales alignment.
- **Importance of Removing Duplicates:**
    - Ensures repeats aren't counted multiple times during data exploration and modeling.
- **Example of Duplicate Record:**
    - Two entries with the same user and purchase ID (should be unique for each purchase).
- **Steps to Remove Duplicates:**
    1. **Identify Duplicate Records:**
        - Manual inspection.
        - Automatic detection using tools like Excel.
    2. **Remove Duplicate Entries:**
        - Manually by deleting.
        - Programmatically by writing a script.
- **Considerations Before Removing Duplicates:**
    - Verify if repeated records are truly duplicates.
    - Understand if repeated data is due to missing information (e.g., same first and last name but different middle names).
- **Next Steps:**
    - Once duplicates are removed, proceed to the next task in data scrubbing.

## Format Your Records

- **Importance of Consistent Formatting:**
    - Inconsistent data format can hinder accurate summarization.
    - Differences in format confuse data analytics tools, leading to incorrect outcomes.
- **Example 1: Location Data:**
    - Variations in recording the same location (e.g., New York City, NYC, New York, NY, Manhattan NY).
    - Need to standardize names to group data correctly (e.g., all recorded as "New York City").
- **Example 2: Currency Data:**
    - Prices recorded in different currencies (e.g., US dollars, euros, yen, pounds).
    - Convert all prices to a single currency (e.g., dollars) for accurate summary statistics (average price, maximum price).
- **Data Types and Formatting:**
    - Ensure data is associated with the correct data type (text, numbers, dates).
    - Specific formatting rules are necessary for correct interpretation by software programs and databases.
- **Example: Date Formatting:**
    - Dates recorded in an unclear format.
    - Update formatting to a conventional date format for accurate summarization and analysis.
- **Steps to Format Data Consistently:**
    1. **Identify Inconsistencies:**
        - Check for different formats of the same data type (locations, currencies).
    2. **Standardize Formats:**
        - Convert all entries to a single, consistent format.
    3. **Verify Data Types:**
        - Ensure each data field follows the correct formatting rules for its type (dates as dates, numbers as numbers).
    4. **Use Tools:**
        - Tools like Excel can help update and standardize data formatting.
- **Outcome:**
    - Properly formatted data allows for accurate summarization, exploration, and analysis.

### Next Step

- Address missing values in the dataset.

## Handle Missing Values

- **Importance of Addressing Missing Values:**
    - Missing values are common and can disrupt analysis.
    - Occur due to various reasons (e.g., users not sharing information, machine errors).
- **Two Options to Handle Missing Values:**
    1. **Fill in Missing Values:**
        - Preferred method.
        - Indicate missing values without inventing data.
        - Use consistent indicators like "unknown" or "N/A".
        - Retain valuable data while clearly marking missing information.
        - Allows continued analysis even with some missing data points.
        - Example: Filling missing locations in a product purchase dataset with "unknown".
    2. **Remove Records with Missing Values:**
        - Delete records entirely.
        - Lose valuable information.
        - Risk of introducing bias in the data.
        - Example: Deleting records with missing location data in a product purchase dataset, potentially leading to biased conclusions about product preferences.
- **Advantages of Filling Missing Values:**
    - Retain other useful data in records.
    - Avoid bias that might be introduced by removing records.
    - Clear indication that a value is missing without distorting data.
- **Disadvantages of Removing Records:**
    - Loss of valuable data.
    - Potential introduction of bias.
    - Example: Missing location data for a store in a warmer area affecting conclusions about dress stock.
- **Best Practice:**
    - Fill missing values with a clear, consistent indicator.
    - Use tools like spreadsheets to detect and fill missing values.

### Next Step

- Address values that are obviously wrong in the dataset.

## Check for Wrong Values

- **Importance of Context:**
    - Understand the context in which data was collected.
    - Recognize the expected range of values.
- **Identifying Obviously Wrong Values:**
    - **Examples of Wrong Values:**
        - Unrealistic values (e.g., age over 150).
        - Negative values in contexts where they don't make sense (e.g., negative prices in sales data).
    - **Contextual Considerations:**
        - Context helps avoid flagging correct data as wrong.
        - Example: Negative prices might be valid for returns in a sales dataset.
- **Steps to Handle Obviously Wrong Values:**
    1. **Replace Incorrect Data Points:**
        - Indicate an error or unavailability.
        - Preserve other valuable data in the record.
    2. **Delete the Entire Record:**
        - Remove all values in the record.
        - Often not preferred due to loss of valuable data.
- **Example:**
    - **Sales Dataset:**
        - Negative values for price initially seem wrong.
        - Context reveals they represent returns, so they are valid.

### Conclusion of Data Scrubbing Process

- **Key Steps:**
    1. Remove duplicates.
    2. Ensure consistent formatting.
    3. Solve for missing values.
    4. Check for wrong values.
- **Outcome:**
    - Achieve a clean data set.
    - Prepare for the next phase: exploring the data.
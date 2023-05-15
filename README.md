# Gitcoin-GR15-Beta-Grant-Analysis
This is an analysis for of the Gitcoin GR15 Beta round.  





<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
      </ul>
    </li>
    <li>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#findings">Findings</a></li>
 
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
The projects is an anlaysis of the Gitcoin GR15 Beta round. The aim of this analysis is to validate useful methods used to spot Fraudulent Grants/ projects. For this project I made use of two different python packages which are novel to analyzing Grants. They are:
  
  1. HTML Date 
  2. TextBlob
  
  * HTML Date: 
  The htmldate package is primarily designed to parse and extract the date from HTML content, specifically focusing on the <meta> tags and other relevant HTML elements where the creation or modification  date of a webpage might be specified. The package can be useful in extracting certain date-related information from HTML content, it's important to note that it relies on the presence and accuracy of such information within the HTML structure of a webpage. Using this package would give a near accurate estimate of when the website was created or last or last modified.
  
 * TextBlob
  TextBlob is a Python library that provides a simple API for common natural language processing tasks such as part-of-speech tagging, noun phrase extraction, sentiment analysis, and more. One of the features TextBlob offers is the ability to analyze the subjectivity of a given text.

Subjectivity is a measure of how subjective or opinion-based a piece of text is, as opposed to being objective and fact-based. Subjectivity scores range from 0 (completely objective) to 1 (completely subjective).

### Installation


1.  html date package.
   ```sh
   pip install htmldate
   ```

2.  html date package.
   ```sh
   pip install validators
   ```

3.  html date package.
   ```sh
   pip install request
   ```


## Findings
  
  * The DateTime function returned a list of most web page creation date, although some are not 100% accurate because of the site update. 
  
  * The DateTime packkage can be used as an alternative to the Website validation Lego curated in the ODC Sandbox project since it returns both creation date and validity of the website with some other functionalities. 
  
  * After checking the validity of sites with creation less than 2017, I uncovered about 30% of them as flagged suspects.
  
  *
  














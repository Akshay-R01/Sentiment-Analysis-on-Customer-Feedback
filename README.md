# Sentiment-Analysis-on-Customer-Feedback
A program to analyze the sentiment of text in a given review for a product and generates a corresponding report.
---

## Introduction 

### Website
* We made a product website (for lack of a better product, we used Apple Watch), made a showcase page for it. 
    ![Website](https://user-images.githubusercontent.com/72353918/169774533-d5097277-78bd-4078-8eb7-ab422996ab00.png)

* We made another webpage for the review section of the product where previously written reviews are displayed. An option to give a review is also provided.
    ![Review](https://user-images.githubusercontent.com/72353918/169775447-aebb08e9-c1ed-4adc-af71-b3dabd1c483e.png)



### Program for Analysis
* We developed a [Python program](/Analysis/SentimentAnalysis.py) to import the freshly posted review from the website database. We then use the API provided by Google Cloud's Natural Language AI to clean the text and then analyze it for the sentiment in the text. The API gives output in the form of a sentiment score and the magnitude of emotion present in the text.
<p align="center">
  <img src="https://user-images.githubusercontent.com/72353918/169775646-31f284ba-d64c-4a03-92ae-03181b13da71.png" />
</p>

* We then classify the score accordingly to Positve, Negative or Neutral and then we make a report of our findings and send an email to be sent to the person who is concerned with the product.
<p align="center">
  <img src="https://user-images.githubusercontent.com/72353918/169776433-3e600a53-056d-4e52-9452-f098c3c826d8.png" />
</p>




### Technologies Used
* Python
* HTML & CSS
* Java
* mySQL

---
## Next for the Project
We would like to improve this project in different areas, for example:
* To analyze the review better than just giving it a category. We would like the program to specify what aspects of the product were praised and what were criticised.
* Include a way to reply to the reviewer as the owner of the product and add many other features.
* To make the program give a few suggestions of its own in the report, for the product owner to reply to the reviewer.

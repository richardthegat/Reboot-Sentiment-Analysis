This project investigates public sentiment around nostalgic TV show reboots using YouTube comment data. Shows analyzed include Velma, Teen Titans, Ben 10, Adventure Time: Fionna and Cake, Powerpuff Girls, Rugrats, Animaniacs, Cobra Kai, iCarly, Dexter's Laboratory, and Bel-Air. The goal is to help Cooledtured assess whether investing in reboot-related content aligns with audience interest and sentiment.


<br>

### **Methodology**

To get this project done, I:

* Scraped comments off YouTube, using the Google API client
* Cleaned and preprocessed text data (lowercasing, stopword removal, lemmatization).
* Conducted sentiment analysis using VADER from NLTK to classify posts as positive, neutral, or negative.
* Visualized sentiment distributions and key trends across each show
* Fitted a Linear Regression model to find the relationship between Sentiment Scores and IMDB ratings

<br>

### **Key Findings**
* Most rebooted shows were positively received, contrary to the expectation that reboots are viewed as cash grabs.

* Positive sentiment (compound score ≥ 0.05) dominated across the board for most shows.

* Velma was a clear outlier. The show had the lowest sentiment score, lowest IMDb rating, and overall negative reception.

* Velma’s backlash seems tied to show quality and sociopolitical themes, not reboots in general.

* Linear regression showed aweak but positive relationship between sentiment and IMDB ratings.

* Overall, reboots are (mostly) recieved quite well across the board. With how commonplace reboots are becoming, investing in them whether through merch, social media, or overall advertisement is recommended.

<br>

### **What does this mean for Cooledtured?**
* **Reboots aren't a dead end:** Remember, most shows analyzed had overall positive sentiment
* **Lean into advertising:** Reboots and live action remakes of movies and shows are a big trend. As the data shows, it would be unwise to ignore them.
* **Avoid controversy traps:** shows like Velma show how sociopolitical misalignment can spark backlash, even before release.
* **Be ready:** So many have come out in the recent past and are coming out in the near future. Be ready for their release and the comapny's social and economic revenue could increase quite noticeabely

<br>

### **Other**
 * **Report:** Breaks down process and findings in detail: <https://docs.google.com/document/d/1JvdJhY2LGQyiEp5yvx88DbADBHTARvPNvMrTcNewYh4/edit?tab=t.0></a>
 * **Presentation:** Quick breakdown of results: <https://docs.google.com/presentation/d/1fAXTZheUADhk9vTbjMzn-PchMjjiCAflS6e51MtBTBk/edit?slide=id.p#slide=id.p></a>
 * **Notebook:**  Includes visualizations, code, and overall, a deep dive into the methodology: <https://colab.research.google.com/drive/1tnPBN3DRNwh8SZEYpBjQ1oTug02CBbZ8#scrollTo=Db22wou8Z6Ng></a>

<br>

## Author(s):

[Oluwanifemi Olufela Richard Yesufu](https://www.linkedin.com/in/oluwanifemi-olufela-yesufu-925b34246/)



For this project I chose to do it on a whole album rather than 1 song, that album being MGMT's "Little Dark Age".

The visualization image used was a modified version of the album's cover art. It was changed up to allow for the words to fill up the space in a way that formed a more readable shape.

Original cover art: https://github.com/tomawash/assignment_3/blob/master/maven-example/cover_art/MGMT%20LDA%20Cover%20Art.png

Modified version: https://github.com/tomawash/assignment_3/blob/master/maven-example/cover_art/MGMT%20LDA%20Cover%20Art%20Transparent%20Fix%203.png

The data structures used to count word frequencies were a hashtable + an array. The hastable was used to keep track of how many times a word appeared. The array was used to keep a list of the each unique word that appeared in the song, so that later when we want to read from the hastable we have a list of all the keys contained within it. To allow for both of them to be passed and recieved from a method, a class called "Song" was created that contained both a hastable and an array. The benefits of this implementation are that aside from having a frequency count, we also get a list of all unique words, which if needed could be used for something else, such as counting how many unique words appear or analyzing average length or number of vowels or something in a word.

If I had more time to work on the project I would've implemented something that would create one word cloud of all of the most common words found throughout the whole album. This I don't think would be had to do (it would probably just be a few for loops that add up together the word counts from all of the .txt files created), however since I'm already a little late with this project I didn't go through with it. Additionally, I'd want to theme the webpage to maybe better match the album's aesthetic, if I had the time to do it.

The reason I chose this particular album was simpy because around the time that the project was assigned I was listening to it a lot, and aside from liking the music I thought the album's cover art would make for a nice image for this project. The top words found in each song were usually words that were in the song's title, along with some common words like "the" and "and". I guess it was kinda interesting to realize the band uses their song's title within their songs just that much.

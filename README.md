Download Link: https://assignmentchef.com/product/solved-cecs-451-assignment-8
<br>
General Instruction

<ul>

 <li>Submit your work in the Dropbox folder via BeachBoard. (Not email or in class)</li>

 <li>Submit the separate files as they are. (no zip file)</li>

</ul>

<ol>

 <li>Evaluate the performance of Google Web Speech API.</li>

</ol>

<ul>

 <li>Read <a href="https://www.google.com/intl/en/chrome/demos/speech.html">How Speech Recognition Works.txt</a> which includes 24 sentences, and record your speech as separate WAV(PCM) files using the nomenclature ‘Group ID-Native</li>

</ul>

Language-gender-Sent#.wav’. For instance, 01-English-female-Sent01.wav. I recommend you to use <a href="https://www.audacityteam.org/">Audacity</a> to record and edit your speech.

<ul>

 <li>(10 points) Upload all audio files to ‘BeachBoard – Discussions – Lab – How SpeechRecognition Works’ by clicking ‘Start a New Thread’. Write your <strong>Group ID </strong>at the subject line and attach the audio files.</li>

 <li>(5 points) Complete the read original method that imports a text file into a list of strings, original, in the order of the sentence number.</li>

 <li>(20 points) Refer this <a href="https://realpython.com/python-speech-recognition/"><em>site</em></a><a href="https://realpython.com/python-speech-recognition/">,</a> and complete the conv audio method that converts audio files into a list of strings, recognized. The method should convert all audio files (.wav) in the folder, inDir, in the order of Sent#.</li>

 <li>(10 points) Complete the comp string method that compares two lists of strings, original and self.recognized, and calculates the similarities of two strings by using <em>Levenshtein Distance</em>. (You need to convert the strings into the lists of words. For instance, ‘I love AI’ to [‘I’, ‘love’, ‘AI’]. Please refer this <a href="https://pypi.org/project/Distance/"><em>site</em></a><a href="https://pypi.org/project/Distance/">.</a>) This method should store the separate similarity scores in self.similarity in the order of Sent#.</li>

 <li>Visit ‘BeachBoard – Discussions – Lab – How Speech Recognition Works’ again, andselect two other threads than yours which include;

  <ul>

   <li>the same native language but distinct gender of yours</li>

   <li>distinct native language but same gender of yours</li>

  </ul></li>

 <li>(15 points) Write a report which includes comparison results using <a href="https://en.wikipedia.org/wiki/Box_plot"><em>box-and-whisker </em></a><a href="https://en.wikipedia.org/wiki/Box_plot"><em>plots</em></a> by native languages and genders as shown in Figure 1 and Figure 2. You may use Seaborn, Pandas, or Matplotlib to draw the plots.</li>

 <li>Submit py and your report.</li>

</ul>

CECS 451                                       Assignment 8 – Page 2 of 2

Figure 1: An example of the comparison by native languages

Figure 2: An example of the comparison by genders
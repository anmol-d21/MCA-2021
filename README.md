# MCA

## Week 1 
The theme for my dataset is the French composer Paul Dukas. Paul Dukas was known for his orchestral piece 'L'apprenti sorcier', with other works including 'Sonata in E-flat minor', 'Symphony in C' etc. His compositions were influenced by composers such as Beethoven, Berlioz, Franck, d'Indy and Debussy.
He was very critical of his work and destroyed many of his projects. This in particular interested me to choose him as my theme since I wanted to learn more about the pieces he decided to keep.

Descriptive data: On IMSLP, descriptive data about each piece of music is shown at the bottom of the screen. For example it describes when the piece was composed, how many movements there are within it, the average duration of the piece and so on. The individual sections also have more data relating to who created the score/who performed the track. An exmaple can be seen below. I think there should be more though.

Notated data: Almost all of his pieces are available via manuscript or computerised form. Websites such as IMSLP however it is also available to purchase from 

Acoustic Data: Paul Dukas' works are easily accessible to listen to via streaming sites such as Spotify, as well as websites like IMSLP.

I uploaded the pdf to musescore, unfortunetely the score was unsuccessful and corrupted so i edited the piece myself to match the PDF

## Week 2

The piece of music I decided to transcribe was Paul Dukas' Piano Sonata in E-flat Minor. I was able to successfully download the pdf of the score, however when trying to convert it into Musescore file it was unsuccessful as it said my file had been corrupted. So, I manually inputed the piece into musescore. 

Accesss the Musescore file [here](sonata-pauldukas-legit.mscz)

## Week 3

<div id="app">Verovio is loading...</div>
<script type="module">
import 'https://www.verovio.org/javascript/app/verovio-app.js';
const options = {
defaultView: 'responsive', // default is 'responsive', alternative is 'document'
defaultZoom: 3, // 0-7, default is 4
enableResponsive: true, // default is true
enableDocument: true // default is true}
// A MusicXML file
var file = 'data/sonata-pauldukas-legit.mei';
// A MEI file
//var file = 'https://www.verovio.org/editor/brahms.mei';
const app = new Verovio.App(document.getElementById("app"), options);
fetch(file)
.then(function(response) {
return response.text(); })
.then(function(text) {
app.loadData(text); });
</script>

Upload MEI file [here](https://anmol-d21.github.io/MCA-2021/verovio.html)

## Week 4
The features I believe are interesting for my piece after generating a jSymbolic analysis are:

upload excel file onto here and the image files
![Histogram](histogram.png)
![Scatter-plot](scatter-plot.png)
![Note Quarter Length Graph](note-quarter-length-graph.png)

Access the excel file [here](sonata-pauldukas-legit-features.csv)

## Week 5
To describe the 1000-song dataset in a meaningful way, I would use these metadata elements:

Song title

artist

composer

source

publisher

data of publication

copyright restrictions (if any)

duration

Access the modified MEI file [here]

## Week 7

## Week 8

![spectogram of track one](track-one-sorcerers-apprentice.png)
Time-frequency analysis allows for a better tool to extract information of the piece of music. From the spectogram, we can see and understand approxiamately what notes are being played as it relates to the frequency. 
However the waveform analysis

Looking at the spectogram, it is more clear where the 

## Week 9 

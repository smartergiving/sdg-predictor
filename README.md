# SDG Predictor  

Classifies a string of text according to the most relevant [U.N. Sustainable Development Goal (SDG)](https://sustainabledevelopment.un.org/) (e.g. grant purposes / nonprofit mission statements). Built on a rainy spring day in Chicago, leveraging [Google Cloud Prediction API](https://cloud.google.com/prediction/docs/) for the heavy lifting.

Inspired by the U.N.'s [LinksSDGs contest](https://unite.un.org/ideas/content/linkssdgs-natural-language-processing-and-data-visualization-challenge), particularly [this entry](https://unite.un.org/ideas/content/linkssdgs-parc-solution) ([demo](http://linkssdgs.herokuapp.com/index.jsp#demo_classifier), [code](https://github.com/UniteIdeas/A-PARC-Solution)).

See also SDGfunders.org's [Indicator Wizard](http://sdgfunders.org/wizard/). Great tool, but closed source. :disappointed:

### Data  
The training set was pulled directly from the text of ['Revised list of global Sustainable Development Goal indicators'](https://unstats.un.org/sdgs/indicators/indicators-list/). Stop words, numbers, and most punctuation were removed.  

### Get Started  

If you haven't already, sign up for a free Google Cloud account.

Follow the [Quickstart guide](https://cloud.google.com/prediction/docs/quickstart).

In step 2, upload `training_data_cleaned.txt`.

### TODOs  
- [ ] Continue training the model with pre-classified grants    
- [ ] Improve `clean.js`

### License  

Copyright 2017 Chad Kruse, SmarterGiving

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

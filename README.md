# The Stem Soul Compatibility Test

This code provides the "Stem Soul Compatibility Test" from the _Wasted Space on the 13th Floor_ as a (Streamlit)[http://streamlit.io] app.

This app is deployed at http://text2gene.com:8501 with zero guarantees of workingness or uptime.  :) 

## What It Do

The Stem Soul Compatibility Test asks for your name, whether you are answering as an individual or as a group, and then four super basic questions that essentially boil down to a 4-factor version of the Big 5.

The questions result in a 4-digit "alchemical code" that is then applied to a flat-file database of creatures with personality codes of their own.  If there's a perfect match, that one result will show on the side panel.  If it's not a perfect match, you'll see two "nearest neighbors" to your code to choose from as your Stem Soul match.

(This app relates to an art installation from a secret art event held in a hotel in November, 2019. So if none of this makes any sense, that's OK!)

## Installation

First, clone this repo.  Then make a python virtual environment and activate it.  For example:

    python3.7 -m venv ~/.streamlitve
    source ~/.streamlitve/bin/activate

Note that _you cannot put the virtualenv in the same directory as this repo._ (It breaks `streamlit`.)

Now install streamlit:

    pip install streamlit
    
Finally, run the app!

    streamlit run 13thfloor.py
    
This command should pop up a browser window already connecting to the app.  If not -- or if you're trying to deploy this on a remote server -- look for a line after you run this that contains the IP address and port number as in the following screenshot.

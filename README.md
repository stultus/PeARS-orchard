# Orchard PeARS

## What and why

PeARS (version Orchard) is a search engine that you can install and run locally from your browser. It allows you to 'index' pages (i.e. to produce a computer-readable representation of the pages' content, essential to the search process), and to search pages that you or your friends have indexed. Search happens entirely on your machine, meaning that no one knows what you are searching and when.

The main feature of PeARS ORchard is the ability to convert a small index into a greyish, unassuming picture, called a 'snow pod'. Snow pods are the mini-weapons of the indexing revolution. They can easily be shared with others by email, on social media, or through any other mean, so you can be your very own search engine, for yourself and for your friends.


### How does it fit with peer-to-peer PeARS?

The fully-fledged PeARS system (Peer-to-peer Agent for Reciprocated Search) is supposed to be completely distributed. You can imagine it as an 'automated' version of Phase 1, where you don't have to go and hunt for pods yourself. Your PeARS install will automatically find them on other users' systems and connect to them. We are still working on this phase of the project.


## Usage

1. Clone this repo on your machine:

    git clone https://github.com/PeARSearch/PeARS-orchard.git


2. **Optional step** Setup a virtualenv in your directory. If you haven't yet set up virtualenv on your machine, please install it via pip:


    sudo apt-get install python3-setuptools

    sudo easy_install3 pip    

    sudo pip3 install virtualenv

    Then run:

    virtualenv -p python3 env && source env/bin/activate

3. Install the build dependencies:

    pip3 install -r requirements.txt

4. Head over to the app/static/spaces directory and unzip english.dm.zip.

5. In the root of the repo, run:

    python3 run.py

Now, go to your browser at localhost:8080. You should see the search page for PeARS. You don't have any pages indexed yet, so go to the F.A.Q. page (link at the top of the page) and follow the short instructions to get you going!



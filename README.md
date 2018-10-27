# Finding your target in the money laundering capital of the world 

## Before the class!

**1. Please ensure you have downloaded XSV [here](https://github.com/BurntSushi/xsv).**

For **Mac** users with homebrew installed, the easiest way is to use `brew install xsv` via the terminal.

For **Windows** users, please download and unzip the binary files into a folder it is easy to navigate to during the class

**2. Please click the green 'Clone or Download' button to download the datasets into a folder you can navigate to during the class. We will be using the sample datasets `pscs-skup.csv` and `CCOD-skup.csv`**

## Key xsv commands

**Windows users** please note you will need to run xsv.exe to run the commands in the directory.**

`xsv count pscs-skup.csv` Counts the number of rows in our file

`xsv search -s data.name 'Trump' pscs-skup.csv > trump.csv` To search a specific column in the dataset for a keyword, in this case Trump and produces a file with the results.

`xsv join company_number norway-pscs.csv Company Registration No. (1)' CCOD-skup.csv > norway-land.csv` joins the data together via the company number which is common to both files and produces a csv file of the results. 

## After the class!

[Link to session presentation](https://docs.google.com/presentation/d/1MYxH9zVaIJADZdjlQUmp5W1Tt8FErCYTVNTpqxEFY08) if you would like to review it after the class.

The full PSC register can be downloaded here: [http://download.companieshouse.gov.uk/en_pscdata.html](http://download.companieshouse.gov.uk/en_pscdata.html)

To gain access to the land registry data for sites owned by overseas and UK companies, you can access both via this article: [https://www.gov.uk/government/news/hm-land-registry-makes-commercial-ownership-data-free](https://www.gov.uk/government/news/hm-land-registry-makes-commercial-ownership-data-free)

# Stay in touch!

If you have any questions about the datasets or would like to collaborate on a project, please contact me on **leila.haddou@thetimes.co.uk**

# International Biometric Society - Australasian Region 

This is a work-in-progress!

The aim is to replace the existing society website (https://biometrics.org.au/) to a modern style by June 2024 (before we have to pay for renewal of the website).


## How to update the website

The website is built using Quarto. You will need to download Quarto to make updates to the website.

1. Clone this repo

```
git clone https://github.com/IBS-AR/IBS-AR.github.io.git
```

2. Navigate to the folder.

3. Make your changes. To check your changes render the website and then preview using the following commands from the terminal. If you are using the RStudio IDE, you can also just click on the tab Build then Render Website. 

```
quarto render 
quarto preview
```

4. To update the website, run the following command from the terminal.

```
quarto publish gh-pages --no-browser
```

## How to update the news page

When a newsletter is published, a PDF copy needs to be generated and saved in the `newsletter` folder. The naming convention is `IBS-AR-Newsletter-MMM-YYYY.pdf` (see examples in the folder). Then the page can be rendered in RStudio and the table will be automatically updated. The code identifies the files in the `newsletter` folder, extracts the month and year and adds a link to the file in the reactable.

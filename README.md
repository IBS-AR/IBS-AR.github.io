# International Biometrics Society - Australasian Region 

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

Garth!

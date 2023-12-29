# International Biometrics Society - Australasian Region 

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

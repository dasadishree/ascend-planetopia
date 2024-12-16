project made for ascend 2024, first all-girls summit and hackathon in los angeles run by hackclub, 1 of 50 participnts internationally.

<h1>Planetopia</h1>
During Hack Club Ascend, we were tasked with designing a planet and asked, "What would be a planet you would want to visit?" Through brainstorming, we realized that there's no single right answer to this question. Everyone has their own vision of utopia, and our project reflects that diversity. Despite facing challenges such as coding errors and occasional confusion about our direction, we achieved what we call a "mission success." Start your own journey by clicking "blast off," create your own planet, and explore its background with a personal tour guide!

<h2>Setup</h2>
<h2>Prerequisites</h2>
<ul>
  <li>A web browser</li>
  <li>An Internet connection</li>
  <li>A Mac with at least 8GB of RAM and macOS 10.15 or later</li>
  <li>An installation of Homebrew</li>

```
[!IMPORTANT] If you don't have Homebrew installed, you can install it by running the following command in your terminal:
  /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

<li>A functional VSCode installation</li>
</ul> 
Installation
Install Ollama by running the following command in your terminal:

brew install ollama
Set Ollama's environment variable, then restart the app.

launchctl setenv OLLAMA_HOST "0.0.0.0"
brew services restart ollama
Install the latest version of Meta's llama3.2 model, then start the server.

ollama pull llama3.2
ollama serve
Clone this repository and navigate to the project directory.

git clone https://github.com/lubabanawla/Planetopia.git
cd Planetopia
Open VSCode and install the Live Server extension.

Right-click on index.html and select "Open with Live Server." On Mac, hold Command while clicking to bring up the context menu.

Click "Blast Off" to start your journey!

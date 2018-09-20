
<h1 align="center">
  <br>
  <img src="https://raw.githubusercontent.com/corollari/speech2latex/master/webExtension/promo/logo.png" width="200"></a>
  <br>
  Speech2Latex
  <br>
</h1>

<h4 align="center">Web browser extension that let's you dictate math formulas by converting spoken math into latex</h4>

<h5 align="center">It's back end is based on <a href="https://github.com/ArVID220u/latexdictation" target="_blank">Latex Dictation</a>, a project built by <a href="https://github.com/ArVID220u">@ArVID220u</a>, <a href="https://github.com/corollari">@corollari</a> and <a href="https://github.com/sualehasif996">@sualehasif996</a> for HackMIT 2018</h5>

<p align="center">
  <a href="#install">Install</a> •Change author order to alphabetical and add links
  <a href="#build">Build</a> •
  <a href="#credits">Credits</a> •
  <a href="#to-do">TO-DO</a> •
  <a href="#license">License</a>
</p>

<!--![screenshot](https://raw.githubusercontent.com/corollari/speech2latex/master/webExtension/promo/screenshot.png)-->

## Install
The extension will be released for Chrome and Firefox

## Build
##### Setup:
```bash
git clone https://github.com/corollari/speech2latex.git
cd speech2latex
```
##### Run server:
```bash
cd server
bash run.sh
```
##### Build web extension:
```bash
cd webExtension
bash build.sh
```

## Credits
The following external resources have been included as part of the project:
- The microphone icon which is part of the extension's logo was designed by Dave Gandy and comes from [flaticon](https://www.flaticon.com)

## TO-DO
- [ ] Add specialized grammar for math expressions to the speech recognition API
- [ ] Remove dependencies on wolfram alpha and mathematica (and the associated delays) by building an AI to do the speech-\>latex conversion using speech data scraped from lectures
- [ ] Put all the server code on the client side, eventually removing the server (and its associated costs) 

## License
MIT

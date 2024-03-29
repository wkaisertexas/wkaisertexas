# William Kaiser

[![personal social website](https://wkaisertexas.github.io/social.jpg)](https://wkaisertexas.github.io/)

I have a **personal portfolio** and **blog** which I built with **AstroJS**, **TailwindCSS** and **ThreeJS**. The site is statically generated with **Astro** and deployed onto **GitHub pages**. [Check out the site!](https://wkaisertexas.github.io)

## General
```toml
[personal]
first_name = 'William'
last_name = 'Kaiser'
preferred_language = 'python'
pronouns = ['he', 'him']
favorite_book = 'Don Quixote'

[education]
major = 'Computer Science (BS)'
minor = 'Data Science'

[extra]
hobbies = ['woodworking', 'electronics', 'cooking', 'coding']
```

## Featured Projects

<h3><a href="https://github.com/wkaisertexas/tranzlate">tranzlate</a></h3>

- Open-Source Translation Utility for string catalogs
- Utilized OpenAI's Chat APIs to conduct semantic text completition.

<h3><a href="https://github.com/wkaisertexas/ScreenTimeLapse">🎥 ScreenTimeLapse</a></h3>

- Successor to [Time lapse](#-timelapse)
- Create color-accurate screenshots in a compact MacOS menu bar application.
- Record both webcams and screens
- Enjoy performant, GPU accelerated accelerated with leading color and video formats
- Fully open source [@ wkaisertexas/ScreenTimeLapse](https://github.com/wkaisertexas/ScreenTimeLapse)
- Available now through HomeBrew `brew install --cask https://raw.githubusercontent.com/wkaisertexas/ScreenTimeLapse/main/screentimelapse.rb`

### 🔬 International Science and Engineering Fair (ISEF) Analysis

Diving deep into ISEF, the world's top science fair with competition data. Examining both historical trends and creating visualizations to help newcomers demystify this competition.

Four main components are present in this project:

- [Article](https://www.linkedin.com/pulse/behind-innovation-insights-from-international-science-william-kaiser) written to explain key findings and methodologies in an accessible manner.
- [Kaggle Notebook](https://www.kaggle.com/code/wkaisertexas/international-science-fair-analysis) which provides the source for figures and findings
- [Kaggle Dataset](https://www.kaggle.com/datasets/wkaisertexas/all-international-science-fair-projects) allows anyone to access ISEF data to complete their own findings
- [Interactive t-SNE Visualization](https://wkaisertexas.github.io/all-isef-projects/) to explore project categories

<h3><a href="https://github.com/wkaisertexas/chatgpt">ChatGPT in Terminal</a></h3>

- Make a terminal version of ChatGPT using the [OpenAI API](https://platform.openai.com/docs/guides/gpt)
- Styled using [clack](https://github.com/natemoo-re/clack) textual user interface
- Published on [npm](https://www.npmjs.com/package/clack-chat-gpt)

### 🎥 Time Lapse

- Easily create time lapses of your screen and webcams
- Intended for programmers, hobbyists and artists to showcase their creations
- Saves wasteful frames which would have been discarded when edited into a time lapse (a hour long screen recording can easily be several gigabytes)

[Click here to learn more](https://github.com/wkaisertexas/timelapse)

### ⬆️ TikTok Uploader

A python module which uses Selenium to automatically upload videos to TikTok. Supports both module calls and a command-line interface.

- [Repo](https://github.com/wkaisertexas/tiktok-uploader)
- [PyPI](https://pypi.org/project/tiktok_uploader/)

### 📍 Textual and Impact-Based CORD19 Clustering 

Created an interactive t-SNE plot of papers from the COVID Open Research Dataset (CORD19). Used data from [Altmetric](https://www.altmetric.com) to create clusters based on impact (citations from various sources). Found very strong statistical correlation between cluster location and impact.

- [Kaggle](https://www.kaggle.com/code/williamkaiser/textual-and-impact-based-cord19-clustering)

### 📝 Society for Science - Science Fair Project Scraper
[Here](https://github.com/wkaisertexas/all-isef-projects) is a project that helps people scrape [Society for Science](https://abstracts.societyforscience.org/) to download their database of science fair projects. 

### ♺ Random URL Generator [^1]
[Random URL Generator](https://github.com/wkaisertexas/randomurl) makes shortened URLs with random destinations. One link has a set of predefined destinations with respective probabilities. Then, when the user clicks on the link, one of the destinations is picked at random.

**Example**: Site that randomly takes you to technology companies' websites
- 25% - facebook.com
- 25% - google.com
- 25% - apple.com
- 25% - microsoft.com

> Note: this project was a victim of the recent changes to Heroku deployments and is no longer publicly available. 

> Built-in link tracking of link destinations makes **A / B testing** more accessible


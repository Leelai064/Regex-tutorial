# Regex Tutorial

## Table of Contents

* [Description](#description)
* [GithubGist](#github-gist-link)
* [TestString](#regex-test-topic)
* [ExampleRegexString](#example-regex-string)
* [RegexURLExplination](#brief-walkthrough)
* [License](#license)

## Description

GIVEN a regex tutorial
WHEN I open the tutorial
THEN I see a descriptive title and introductory paragraph explaining the purpose of the tutorial, a summary describing the regex featured in the tutorial, a table of contents linking to different sections that break down each component of the regex and explain what it does, and a section about the author with a link to the author’s GitHub profile
WHEN I click on the links in the table of contents
THEN I am taken to the corresponding sections of the tutorial
WHEN I read through each section of the tutorial
THEN I find a detailed explanation of what a specific component of the regex does
WHEN I reach the end of the tutorial
THEN I find a section about the author and a link to the author’s GitHub profile

## Github Gist Link

https://gist.github.com/Leelai064/996eb51d1de3d7498c34a161d3413692

## Regex String Topic

(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$

## Example Regex String

https://www.thetoughtackle.com/entertainment-sword-art-online-season-5-8081/

## Brief Walkthrough

To understand the string stated above lets break it down into groups to understand the URL as a whole. There are three character groups that makeup this url expression provided above.

Group 1: searches for the "https://" section of the URL before proceeding to the latter of the URL

Group 2: identifies the title of the URL. In this example "thetoughttackle" contain characters from a-z in no particular order.

Group 3: lastly, this group targets the ".com/" aspect of the URL expression and every string afterwords. In our example that would be: ".com/entertainment-sword-art-online-season-5-8081/"


## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Gitpod Ready-to-Code](https://img.shields.io/badge/Gitpod-Ready--to--Code-blue?logo=gitpod)](https://gitpod.io/from-referrer/)

> ℹ️ Before you use this, try if the online [rule editor](https://community.languagetool.org/ruleEditor2/) works for you.
> It has some limitations, but it's more user-friendly.

## What is this?
This repo serves as the starting point for a Gitpod container in which you can edit rules and test them against a user-provided [`text.txt`](text.txt) file.

This *will* break for newer LanguageTool releases because of hard-coded version numbers (5.6-stable).
I do not intend to maintain this, but PRs are welcome.

## Getting started
Just click the button below to start a Gitpod container.
LanguageTool will be set up automatically.
You can begin your work and re-execute LanguageTool automatically by saving the [`text.txt`](text.txt) file.

## Files of interest
- [German `grammar.xml`](LanguageTool-5.6-stable/org/languagetool/rules/de/grammar.xml)

## See also
- [LanguageTool on GitHub](https://github.com/languagetool-org/languagetool)
- [dev.languagetool.org](https://dev.languagetool.org/)
- [Online text analyzer](https://community.languagetool.org/analysis/analyzeText), displaying the results of LanguageTool's analysis
- [tagset (de)](https://github.com/languagetool-org/languagetool/blob/master/languagetool-language-modules/de/src/main/resources/org/languagetool/resource/de/tagset.txt), explaining strings like `SUB:NOM:SIN:MAS`

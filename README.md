# Repo for the MIT ESI RRG Website

This branch is meant for sync only, the live website
repo is on the branch **live**. The dev repo is on
the master branch of [**tareqdandachi/mit-rrg**](https://github.com/tareqdandachi/mit-rrg).

The website should be on the following sites:

 - rrg.mit.edu (Actual Live Version, Static)
 - esiresponse.scripts.mit.edu (Actual Live Version, Static)
 - esiresponse.github.io (Actual Live Version, Jekyll+Liquid)
 - tareqdandachi.github.io (Dev)

### Why this branch?

The github action in this branch ensures that pushing to tareqdandachi/mit-rrg:master
causes the live version of the website on esiresponse/esiresponse.github.io:live to update
accordingly. It will also run a command that should update the *.mit.edu websites.

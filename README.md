# EngineeringToolbox

In the 2021 summer we decided to start an "engineering toolbox", a github repo bringing together particularly useful scripts and tools.

For deploying these scripts, I believe [streamlit](https://streamlit.io/) provides a great option. It allows you to turn your tool into something highly accessible and interactive with very little effort. For now at least, they also provide free cloud hosting allowing for effortless deployment allowing access for anyone from anywhere. Other ways of making things highly accessible with little effort could include matlab's live scripts and jupyter notebooks, however I don't think interactivity in that way should be a requirement.


This does not mean that all scripts have to be python - this can be completely language agnostic, though it makes sense to me to restrict to perhaps python and matlab given those are what people are likely to be most familiar with and are most accessible to those who aren't.

I would love to encourage using this one github repo to share any scripts that have provable use to the team. It would be brilliant to use this for any small scripts being used to make design decisions. However, we should take care that any scripts uploaded here are both useful and relatively neatly coded.

The 

Examples of orphaned scripts written by ICLR members include this [shearpin calculator](https://github.com/icl-rocketry/Shearpin-BP-calculator) (which is [documented](https://wiki.imperial.ac.uk/display/IRW/Shear+pin+calculations) but would probably make a good addition to here), Eddie's extensive collection of [nitrous scripts](https://github.com/icl-rocketry/NitrousModelling) and a small properties calculator I used to determine the viscosity of N2O. The last one I made a mistake in, reporting the viscosity 100x out from what it should be. It took Piotr a week or so to notice my mistake, and perhaps if that had been shared it could have been picked up on sooner.

# Structure

I've included a Propulsion folder here so we start with good compartmentalisation & categorization of scripts. This should give us flexibility and help with what this is meant to do: make sharing scripts easier, whether people were involved in the scripts development or not. I think a README within each team subfolder containing a sentence or two about each program there would be great.

If any file/script requires additional data, please provide that with the file and nest both in their own folder.

# Points for discussion
- How granular should the file structure be? Should we only worry about splitting scripts up more if we find we have a significant amount of them? As it is now
- Should we encourage using any language? It's possible that could become quite inconvenient for working with the repo given Matlab having to be used within it's own exclusive IDE
    - I think yes, but I'd be happy to hear what others say
- How should import of previous scripts be handled?
- Should this be limited to just scripts? We could also allow people to include markdown files describing/documenting e.g. how they got data from propep
    - This has a serious disadvantage of beginning to overlap with the purpose of the wiki, especially the "How To" section
    - I think I'm against that for this reason, and perhaps it would be best to attempt to keep this repo for reference from the wiki


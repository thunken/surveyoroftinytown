# 📍surveyoroftinytown

`surveyoroftinytown` provides machine-readable data to help work with the BEACON dumps produced by [terroroftinytown](https://github.com/ArchiveTeam/terroroftinytown), [URLTeam](http://urlte.am)'s second generation of URL shortener archiving tools. For more more information about URLTeam and `terroroftinytown`, please see their [wiki page](http://archiveteam.org/index.php?title=URLTeam).

`surveyoroftinytown` currently includes a single dataset, `projects.json`, that provides a machine-readable view of (some columns of) the table describing Warrior projects on https://www.archiveteam.org/index.php?title=URLTeam#Warrior_projects and the bit.ly aliases listed on https://www.archiveteam.org/index.php?title=URLTeam#bit.ly_aliases.

For each project, we include:
* `aliases`: a non-null array of alias hostnames
* `host`: the main hostname for this project
* `warrior_project_name`: Warrior project name (null for non-Warrior projects)

All credit for the original research goes to URLTeam.
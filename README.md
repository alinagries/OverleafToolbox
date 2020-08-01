# RPA2020

This projects aims to automize common workflows when working with overleaf by using Robotic Process Automation (RPA). 
These include:

1. Saving an Overleaf project to GitHub.
2. Sending an Overleaf project via e-mail (Thunderbird and Windows mail).
3. Adding BibTeX from dblp or citavi. When importing them from dblp, they can also be added to an open citavi project.
4. Credential management, GitHub and Overleaf logins are saved to the local [Windows Credential Manager](https://support.microsoft.com/en-gb/help/4026814/windows-accessing-credential-manager)
)
# Installation

To run the project, you should:

1. install [UiPath](https://www.uipath.com) (any up-to-date version is sufficient). 
2. open the project in UiPath.

# Usage

To choose between our features, execute src/ChooseFeature.xaml. The rest should be explained within the programm.

_Be sure to only have one Chrome window open, else UiPath could fail the execution!_

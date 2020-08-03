# Overleaf Toolbox

This projects aims to automize common workflows when working with overleaf by using Robotic Process Automation (RPA). 
These include:

1. Saving an Overleaf project to GitHub.
2. Sending an Overleaf project via e-mail (Thunderbird and Windows mail).
3. Adding BibTeX from dblp or citavi. When imported and downloaded from dblp, they can also be added to an open citavi project.
4. Credential management, GitHub and Overleaf logins are saved to the local [Windows Credential Manager](https://support.microsoft.com/en-gb/help/4026814/windows-accessing-credential-manager)
)
# Requirements

To run the project, you should have [UiPath](https://www.uipath.com) (any up-to-date version is sufficient) and [Chrome](https://www.google.com/intl/en/chrome/) installed. Since UiPath only supports Windows, you should have that too :D

# Usage

To choose between our features, execute src/ChooseFeature.xaml. The rest should be explained within the programm.

Be sure to close your Chrome windows before execution. In Chrome, the default download folder is set to "Downloads". If you changed this Chrome setting, please reset to default or adjust it in the code.

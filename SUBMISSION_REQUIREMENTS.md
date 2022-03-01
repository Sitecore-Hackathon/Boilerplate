## 💡Ideas for Hackathon 2022:
1. Build an e-commerce Minimum Viable Product to sell community t-shirts  
   *  The submission must include the following technologies:
      *  Sitecore XM - Rendering host (.net or jss)
      *  Sitecore Send
      *  Sitecore Order Cloud
   *  Authentication is _not_ required
   *  Payment processing _not_ required
2. Sitecore Command Line Interface (CLI) plugin
   *  https://doc.sitecore.com/xp/en/developers/102/developer-tools/sitecore-command-line-interface.html
3. Best addition to the Sitecore MVP site
   *  https://github.com/Sitecore/MVP-Site

## 📜Entry Submission Requirements 
All teams are required to submit the following as part of their entry submission no later than the end of the Hackathon on Saturday March 5th 2022 at 8PM EST. The submitted entries shall be based on [**Sitecore 10.2 XM**](https://dev.sitecore.net/Downloads/Sitecore_Experience_Platform/102/Sitecore_Experience_Platform_102.aspx).

### IMPORTANT  👀
> You have to fill in the README.md file found in this repository. Copy in the content of 
> ENTRYFORM.md as template.

## 🔧Sitecore Setup

   > You **must** use an elevated/Administrator PowerShell terminal to run the `.\Start-Hackathon script.`  
   > [Windows Terminal](https://github.com/microsoft/terminal/releases) looks best but the built-in Windows Powershell 5.1 terminal works too.

### Idea 1 and 2
The choice is yours as to how you install Sitecore locally for the Hackathon. There is no requirement on whether you setup with Docker, SIF/SIA, Sifon, SIFless, SIM, or [insert creative approach]. We do however require that the installation steps are simple, few, and require no magic to get your submission working. We encourage you to perform a fresh install and follow your own documentation to ensure that no steps are missed. It would be unwise to try any of these installation methods for the first time the day of the Hackathon because so much can go wrong; do what you know well and invest as much time as you can being creative working on your solution.

For those with prior experience working with Docker, we have provided a ["starter kit"](STARTERKIT_INSTRUCTIONS.md) in this GitHub repository (thanks Anders) with a variety of options to speed things up. 🚀 

### Idea 3

1. Run the Start-Hackathon script from an _elevated_ PowerShell terminal with the switch `-MvpSite`

    ```ps1
    .\Start-Hackathon -MvpSite
    ```

This will download and extract a full copy of the MVP-site repository. This cannot be undone locally.

This should of course only be done on 1 machine and then commit this to share the mvp-site setup with the rest of the team.

For local environment setup follow the instructions found in the updated README.md file or simply run 

    ```ps1
    .\Start-Environment -LicenseXmlPath "C:\path\to\license.xml"
    ```

and follow the on-screen instructions.

_Note; the Hackathon README.md file is renamed to README-HACKATHON.md. Please use this for your ENTRYFORM.md._

## 📦Deliverables
Please read carefully — and thoroughly — to ensure you have not missed any of the requirements.

## 🍝Code
Notwithstanding the fact that value full creativity in your submission, we are going to be judgy here — we are judges, after all. Once your code is pushed to GitHub, we will look for the following with no exceptions:
- Cleanliness of code
- Clear documentation
- Adherence to Sitecore best practices (Helix)

## 📼Documentation
The documentation requirements are extremely important. If the judges are unable to get your Hackathon project running then we can’t count it as complete. Here are items we expect to be included which must be pushed to the GitHub repo in the readme:
- Short YouTube video (2-3 minutes) describing your project submission purpose, setup instructions, and how to use it.
- One to two pages of documentation describing your project submission purpose with screenshots of the finished product and installation steps with screenshots where appropriate.

__Read and follow the instructions in__ [ENTRYFORM](ENTRYFORM.md)
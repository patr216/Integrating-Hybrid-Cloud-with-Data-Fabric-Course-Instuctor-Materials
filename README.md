What are we doing?

    To support course Integrating Hybrid Cloud with Data Fabric, we will need to make frequent updates to the course content to keep it current with AWS and Azure services used in the course. We are publishing the lab instructions and lab files on GitHub to allow for open contributions between the course authors and authorized instructors to keep the content current with changes with this NetApp Hybrid Cloud Solution
    We hope that this brings a sense of collaboration to the labs like we've never had before - when the provider platforms changes you'll change it during a live delivery, go ahead and make an enhancement right in the lab source. Help your colleagues.

How should I use these files relative to the released MOC files?

    The instructor PowerPoints are still going to be your primary source for teaching the course content.
    These files on GitHub are designed to be used in conjunction with the student guide, but are in GitHub as a central repository so instructors and course authors can have a shared source for the latest lab files.
    It is recommended that for every course delivery, trainers check GitHub for any changes that may have been made to support the latest NetApp content, and get the latest files for their delivery.
        You can make the lab files available to students by downloading the .md files, using Pandoc to create the Word docs from the .md files, and then printing and distributing the files to students. The lab instructions are also available as a Web page at http://microsoftlearning.github.io/20533-ImplementingMicrosoftAzureInfrastructureSolutions.

Note: It is strongly recommended that instructors access these materials and in turn, provide them separately to students. Pointing students directly to GitHub to access Lab steps as part of an ongoing class will require them to access yet another UI as part of the course, contributing to a confusing experience for the student. An explanation to the student regarding why they are receiving separate Lab instructions can highlight the nature of an always-changing cloud-based interface and platform. Learning support for accessing files on GitHub and support for navigation of the GitHub site is limited to instructors teaching this course only. GitHub should not be used to discuss technical content in the course, or how to prep. It is specifically to address changes in the labs. -To address general comments about the course & demos or how to prepare for 20533, please use the MCT forums at https://borntolearn.mslearn.net/mct/general/f/225. This is the MCT Readiness forum for discussions, news, etc. to help you prepare to teach courses and let you collaborate with other instructors.

Notes about the Demos in the course

    In order to avoid discrepancies due to interface changes (since we cannot update demos the same way we update labs,) the demos intentionally do not provide step by step instructions. To fully prepare, we encourage the Instructor to familiarize themselves completely with the demos and content prior to teaching the course, and reach out to the MCT forums for guidance and to online Azure technical resources such as the Microsoft Azure forum on MSDN https://social.msdn.microsoft.com/forums/azure for technical questions.

What about changes to the student handbook?

    We will review the student handbook (including demos) on a quarterly basis and update through the normal MOC release channels as needed.



Note: After you download the latest lab files from GitHub and copy them to the student computers, ensure that the student computer is restarted before students start the labs. This ensures that any PowerShell modules that have previously been run will be replaced in memory by the latest versions. In addition, since the scripts on GitHub are not codesigned, students need to run the following command to ensure that the scripts will run: Set-ExecutionPolicy –ExecutionPolicy Bypass –Force This command should be run at the beginning of the class, and applied to the VM image if possible. Read more about Set-ExecutionPolicy

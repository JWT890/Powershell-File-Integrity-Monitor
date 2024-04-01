# Powershell-File-Integrity-Monitor
Home lab done via a video from Josh Madakor's YouTube channel

When it comes to sharing files across an organization, integrity is a vital part of the CIA triad (Confidentiality, Integrity, and Availability), in which you want to maintain the vital components of the file together and not risk tampering or changing of the important information critical to the organization or project. 

This project takes the integrity portion of it and applies it through a PowerShell script that checks to see if a file has been moved or tampered with. As an example, if a file has been created it will send out a message saying that a new file.txt has been created and will show the path of the file. Another example would be if a file has been changed or deleted, it will send out a warning saying that the file has been deleted or a baseline has been deleted. In essence, how this works is that it takes the hash of one of the files, appends it to the baseline.txt file, and keeps up with for any changes that occur in the path for each file. 

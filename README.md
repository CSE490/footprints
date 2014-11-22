Footprints
==========

Your kids' memories, safe and private in the cloud.

Stack
====

Backend: Node.js + Express + MongoDB  
Storage: Kloudless  
Frontend: Jade + Bootstrap

Each user has an `Account` on Kloudless. Each `Account` has `Folder` for each kid. Each `Folder` has files in it.

For MongoDB:

- User gives files
- We store metadata of each file
- For each file, we create Kloudless link, and store it with metadata
- When user requests images, we serve everything sorted.

License
======

<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>.

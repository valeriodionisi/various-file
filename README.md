## HOW TO CREATE A STABLE URL FOR A .pdf FILE USING GitHub PAGES ##

#### Create a repository ####
To create a GitHub page URL to link a .pdf file, first create the ground following these steps:
  1. create a GitHub repository, and then go to its section called “Settings”, and then, on the left border, to “Pages”";
  2. in the section called "Build and deployment":
     - in _source_, select "deploy from a branch";
     - in _branch_, select the "main (or master)", "/(root)", and click on “save”;
  3. now, wait till the setup is done. You can check the status under _https://<your_username>.github.io/<repository_name>_. After the 404 error is gone, it is online.

Note that the repoisotry must be public; check the status in “Settings”, “General”, and at the bottom, in “Danger zone” section, “Change repository visibility” cell, there must be written “This repository is currently public”. Otherwise, simply click on the “Change visibility” button and turn the repository to public.

#### Create a URL ####
Then, to create a URL that directly links to a _<document_name>.pdf_ file, one should: 
  1. go to the repositories by clicking the profile image at top-right, and select "your repositories";
  2. open the desired repository where the file should be stored;
  3. in the "main" section, click "add file", and select the given file to upload. Then:
     - note that a file cannot be deleted unless you delete the repository;
     - to substitute a file, simply upload a file with the same name, and this will take the place of the old file;
  4. this will automatically create an URL as the following _https://<your_username>.github.io/<repository_name>/<path/to/file.pdf>_;
  5. then, write the correct URL in a search tab on your preferred broswer to check that everything is fine!
     
see also: https://www.programonaut.com/how-to-link-to-a-github-pdf-without-downloading-it/

# Hardcore
4. “HARDCORE” Task: This task is based on the previous one (“Hurt Me Plenty”).

    4.1 Push your repository and make sure all commits appeared in github.
	
	**cd ..**
	
	**git clone git@github.com:ViktarKimpel/Hardcore.git**
	
	**cd Hardcore/**

	**git checkout master**

	**git commit -m "add HometaskM2"**

	**git push**

    4.2 Create a new repository in github.

    4.3 Set up remote in local repository in the way that allows:- pull from the first (initial) remote repository, - push to the second (new) remote repository.

	**git remote -v**

	**git remote remove origin**

	**git remote -v**

	**git remote add origin git@git.epam.com:Viktar_Kimpel/hometask-backup.git**

	**git remote -v**

    4.4 Make push and make sure the second repository in github is identical to the first one.

	**git push**

	**git push --set-upstream origin master**

    4.5 Get initial settings back for remote: pull and push of local repository hit the same remote repository in github.

	**git remote -v**

	**git remote remove origin**

	**git remote -v**

	**git remote add origin git@git.epam.com:Viktar_Kimpel/hometask.git**

	**git remote -v**

	**git push**

	**git pull**
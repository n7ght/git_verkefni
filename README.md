#Fyrsta Git verkefnið

1. Hvað gera eftirfarandi Linux skipanir?

	cd    				change directory (skiptir um directory)
	cd ~  				direct to home directory (beint í home directory
	ls    				shows list of directory	 (sýnir lista úr directory)
	pwd   				print working directory  (prentar út vinnandi directory, directory sem þú ert í)
	mkdir 				make directory		 (býrð til directory(möppu))

2. Hvað gera eftirfarandi git skipanir og hvers vegna eru þær gagnlegar?

	git clone     			Copys to a new repository   					(Copyar í nýtt repository)
	git log       			Show commit logs	    					(Sýnir commit logg-ana)
	git status    			Show the working tree status					(Sýnir Working tree status)
	git diff      			Show changes between commits, commit and working tree, etc	(Sýnir breytingar á milli commits, working tree osfr)
	git checkout  			Switch branches or restore working tree files			(Skiptir milli greina eða endurkallar working tree fæla)

3. Hver er munurinn á eftirfarandi git skipunum:

	a) git diff 			Show changes between commits, commit and working tree, etc      (Sýnir breytingar á milli commits, working tree osfr)
	b) git diff --staged 		Can also be "--cached" shows changes to next commitment         (Getur líka verið kallað "--cached", sýnir breytingar á næsta commitment)
	c) git diff commit1 commit2	Saves the file so later it can be loaded			(Vistar fæl svo hann geti verið loadað seinna)
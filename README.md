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

4. 	Hvað er útgáfustýring (e.version control)? 
	
	Version control er kerfi sem skráir breytingar á file eða file-um yfir tíma svo þú getir aftur kallað sérstakar útgáfur seinna.

5.	Hverjir eru helstu kostir við að nota GIT?
	
	Helstu kostir breytast með umhverfum og það er ekki eitt satt svar, enn á sama tíma, það er hratt og skilvirkt, getur stokkið framm og aftur í tíman og þar með ekki brennt þig og tapað allri vinnuni þinni.

6.	Hversu oft telur þú að eigi að gera commit í verkefni, rökstuddu

	Hvenar sem ég hef eitthvað sem virkar (meinandi, eitthvað sem bilar ekki fyrir aðra) þá geri ég check-in. Ég skrifa mest af mínu stuff-i og testa fyrst, svo eftir hverja keyrslu sem gengur á t.d. C++ verkefni, þá check-a ég inn.
	(vanarlega nokkrum sinnum á hverjum klukkutíma)

7.	Hvað er "Working directory"?" "Staging area"?" og "Repository" í GIT?

	a) Working directroy er directoryið með "source" fælonum þínum undir git stjórn (í rót allra directoryiana þar sem .git file er til staðar). Git er að tracka breytingar á milli "your working directory" og þinni "local repository, og á milli þinni "local repository og (einni af) "remote repositories".
	b) Staging area er fæll, algent geymdur í Git directoryinu þínu, sem geimir upplýsingar um hvað mun fara í næsta commit, Það er stundum kallað "index-ið", enn er líka algengt að kalla það "staging area".
	c) Tilgangurinn með Git er að halda utan um verkefni, eða set af fælum, meðan þær breytast yfir tíma. Git geymir upplýsingar í gagnabyggingu kallað "repository".

8.	Hvenær er sniðugt að nota greinar (branches)? 

	segjum að þú sért að vinna á ritgerð. Þú ert búinn að skrifa fyrsta uppkast, til sýningar fyrir yfirferð. Svo færðu nýjar upplýsingar og þú ert að setja það inn í ritgerðina. Hálfa leiðina hinsvegar er hringt í þig og sagt við þig að þú verðir að breyta hlutum sem voru ekki alveg réttir hjá þér eða rétt uppbygðir, hvað geriru ?
	greinilega viltu ekki senda þeim hálf bökuðu revisioninu þínum sem er með réttri uppbygingu. Það sem þú vilt gera er að hoppa til baka í útgáfuna sem þú sendir út, breyta uppsetinguni, og senda burt afrit, á meðan þú heldur í núverandi vinnuna þýna sem var vel geymd annarstaðar.
	þetta er hugmyndinn um "branching", og Git gerir það auðvelt.
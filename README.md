Terminal, Git and GitHub assignment

1.
Svar: “ls” kommandot är en kommando som listar filer och mappar i vår aktuella mapp, om kommandot inte skriver ut något i terminalen kan det alltså bero på att mappen är tom alltså att den inte innehåller några filer, vilket då leder till att vår kommando inte kan visa något då denne är tom. 

5.
Svar: Genom att använda det första kommandot “cd newfolder” flyttas vi till mappen newfolder och genom att använda “ls” kommandot listas vi i vår aktuella mapp som är just newfolder. När vi gjort dessa kommandon så kommer innehållet i vår newfolder mapp att visas i terminalen.



6.
Svar: För att hitta vår nuvarande plats i terminalen så använder vi oss ut av "pwd", den skriver alltså ut den fullständiga sökvägen till vår aktuella plats i själva terminalen. 


9.
Svar: För att göra det kortfattat och enkelt så används Git för versionshantering av källkoder och filer. Git är ett distribuerat versionshanteringssystem som gör det lättare för oss  att spåra ändringar och hantera olika versioner av ett projekt till exempel. 

10. 
Svar. Working directory alltså arbetsområdet, är det första stadiet där filerna befinner sig. i arbetsområdet finns det olika versioner av ens arbete osv. Den andra så kallade området är Staging arena, och där så har du alla dina ändringar i filer och kan använda dig utav dessa ifall du känner dig nöjd med då, det är då du scannar/ stadgar dessa ändringar för att förbereda de för en så kallad commit vilket betyder att du sparar då ändringarna permanent. tredje och sista området är “arkivet” efter att du sparat alla dina ändringar på stagningen så sparas dessa i ditt git-arkiv så det är i arkivet du har alla dina besparingar.  


12.
Svar. Genom att använda mig av detta kommando så skapas mitt så kallade git-arkiv på så sätt kan jag lätt spåra ändringar och hantera olika versioner av mitt projekt. 

14:
Svar: Kommandon man ska använda här är, 
git add README.md. gitignore.

15. 
Svar:  (use "git add <file>..." to include in what will be committed)
        newFile.txt


16.
Svar:  inte gjort. 

17.
Svar: Git branches är en typ av funktion inom “git” Branch kan vara separata linjer av utveckling som tillåter dig att arbeta med olika versioner av ett projekt samtidigt varje gren eller branch om man så vill kalla det representerar en oberoende linje av ändringar. Vi säger att om två elever jobbar med ett projekt så kan de använda sig en “branch ", alltså att alla kan ändra saker och ting i samma fil.


18.
Svar:git branch newbranch, git switch newbranch. 
19. mkdir newBranch.txt git add newBranch.txt git commit-m"newfile to the new branch"
        
27.echo "# Github" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/KandeTouray/Github.git
git push -u origin main
        
28. git branch -m master main
git push -u origin main

29. git push origin <branch-name>
git push origin main

30. mkdir my-repo
cd my-repo
git clone https://github.com/username/repository.git

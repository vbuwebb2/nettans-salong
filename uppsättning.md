# Git

## Om du inte har installerat git
* Ladda ner Git.
* Dubbelklicka på filen som laddas ner (klicka bara ”next” överallt tills installationen är färdig).
* Starta om datorn. 

## Om du redan har en installatinon
* Gå till c:/users/ditt användarnamn 
* Gå till fliken "view/visa" och markera "Hidden items/Dolda objekt"
* Radera filen .gitconfig

## Om det krånglar 
* Ta bort ditt githubkonto (Bilden högst upp till höger -> settings -> account -> Delete your account


# Github
## Skapa konto
* Gå in på github.com och klicka på "Sign Up".
* Välj användarnamn (gärna något vettigt, du kan använda github som ett cv när du söker jobb framöver). 
* Använd din vbu-mejl.
* Fyll i resten av fälten och klicka dig vidare. 
* Välj vad du vill på kommande frågor. Jag skulle, i er situation, ha valt 
	1. "Student" 
	2. "A little"
	3. Host a project + Collaborating with my team + School work and student projects.
* Gå till din e-post och verifiera ditt konto. 

## Skapa repository
Om ni är två ska _en_ av er göra följande: 
* När ni klickat på Verify email address i mejlet kommer ni till en sida där ni får välja vad ni ska göra först, klicka på "Create a repository" i rutan "Start a new project".
* Döp repositoryt i enlighet med det projektet ni valde. T.ex. lernbo-taxi (endast lowercase och med bindestreck som mellanrum).
* Välj "Public"
* Lämna resten och klicka på "Create repository".

# Uppsättning av projekt (en av er)

## Konfigurering av git
* Skapa en mapp någonstans på datorn (som du enkelt hittar) och döp den till repos. 
* Skapa en till mapp i repos-mappen, som du döper som repositoryt, t.ex. lernbo-taxi. 
* I den mappen, högerklicka och välj "Git Bash Here".
* Skriv följande, med enter emellan varje steg: 
	1. git init
	2. git config --global user.name (ditt namn)
	3. git config --global user.email (din vbu-mejl)

## Visual Studio 
* Öppna VS Code, välj "File -> Open Folder" och leta på den mapp du just skapade (t.ex. lernob-taxi).
* Skapa en ny fil i VS Code:s filutforskare (Två papper överst i den vänstra menyn). (Den kan heta vad som helst, jag döper min till test). 
* Det kan vara vettigt att skriva något i den, vad som helst. Jag vet inte hur Git ser på tomma filer. 
* Klicka på grensymbolen (tredje ikonen i vänstra menyn). Den bör ha en liten etta intill sig. 
* I fönstret där ser du överst ett meddelande-fält, sedan din fil. 
* Skriv något i meddelande-fältet och sedan CTRL + ENTER. (Vi har nu gjort en "commit". Än så länge är våra förändringar bara lokala, vi har inte lagt upp dem på Github ännu).
* Filen bör försvinna efter en liten stund. 


## Sätt upp kopplingen mellan git och VS Code
* Längst ned i VS Code finns en rad av en annan färg (min är lite ljusare blå än resten av VS Code. 
* Längst till vänster i den raden finns grensymbolen, följt av texten "master" och sedan ett moln med en pil upp. 
* Klicka på molnet med pil upp (eller skriv följande i terminalen; 
* Du bör få ett meddelande: The extension 'GitHub' wants to sign in using GitHub. Klicka på "Allow". 
* Ett webbläsarfönster bör öppnas, med en sida som säger "Authorize Visual Studio Code to access GitHub". Klicka på "Continue".
* En annan vy kommer upp med texten "Authorise Github for VS Code". Välj "Authorize github".
* Om du får texten "Success" har allt gått bra. Du kanske ser en alert som säger "Vill du öppna Visual Studio Code?". Det spelar ingen roll vad du väljer här, bara du får bort rutan. 
* Gå tillbaka till webbläsaren och fönstret med "Success"-meddelandet och kopiera all text som står under rubriken "Didn't work?". Klistra in den texten i notepad eller något. 

## Add remote
* I Webbläsaren, gå till github och leta på det repository som du just skapade (den av er som skapade det). Om du inte hittar det finns det under bilden uppe till höger -> your repositories. Det ska vara listat där. 
* En bit ned finns en länk till ert repository (den slutar på .git). Kopiera den. 
* Gå till VS Code
* I VS Code, tryck tangentkombinationen ctrl+ö för att öppna terminalen. 
* Skriv följande i terminalen
	* git remote add origin [klistra in länken]
* Klicka på molnet, alternativt skriv git push --set-upstream origin master
* Du ska få skriva in användarnamn och lösenord nu. Ibland får du försöka flera gånger. Vi har haft problem här förut, men vi får kolla från fall till fall vad som är fel. 


## Bjud in din teammedlem
* Inne på ditt repository på github.com, klicka på kugghjulet i den grå menyn under ditt repos namn, men ovanför vyn med filer. 
* Klicka på "Invite a collaborator" och ange epost-adress eller användarnamn för din teammedlems github-konto. 

# Den andra av er
* Acceptera inbjudan från ägaren av repositoryt. Det bör finnas en liten notifikation bredvid din bild högst upp till höger på GitHub. 
* Gå till VS Code och öppna ett nytt repository (precis som vi har gjort med exempelfilerna hela tiden). Leta på repositoryt som den andra skapade och kopiera länken. 
* Spara repositoryt i din repos-mapp. 



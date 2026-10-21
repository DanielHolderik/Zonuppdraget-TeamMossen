## Vad hände

Den 20 oktober upptäcktes att TLS mellancert. från certf utfärdearen eMurdha hade komprometerats på grund av felkatigt genererade privata nycklar. Nycklar var svaga och lätta att gissa. Eftersom certifikaten ingick i en betrodd certifikatkedja kunde en potetntiellt angripare, utfärda falska certifikat. Den största potenteilla problemet är att en angripare kan utge sig for att vara ne legitijm webbplats och lura in användare. Detta skapar en möjlighet för attacker. Enlight rapporter fanns det inge kända belägg i "Certificate Transparency" loggarna att de felaktiga nyckalrana hade utnyttjats.

## Åtgärder 

Efter problemet upptäcktes spärrades de komprometterade cert. i flera stora webbläsare och platformar. Apple, Microfsoft och firefox har redan blockerat certs. Problemet är dock inte löst eftersom inte alle enhetetert kontorllerar återkallade certifikat på samma sätt som moderna webbläsare utan dem behöver updateringars ab sina certifikatarkiv. Detta gäller bl.a. Linux distros. Därför krävs fortsatt arbete från både programutvecklare och systemadministratörer för att säkerställa att de komprometterade certifikaten inte längre accepteras.

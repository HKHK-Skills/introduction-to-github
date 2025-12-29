<!--
  <<< Author notes: Step 2 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->

## Samm 2: Tee commit

_Sa lõid haru! :tada:_

Haru loomine võimaldab sul muuta oma projekti ilma `main` haru muutmata. Nüüd, kui sul on haru, on aeg luua fail ja teha oma esimene commit!

**Mis on commit?**: _[Commit](https://docs.github.com/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/about-commits)_ on muudatuste kogum sinu projekti failides ja kaustades. Commit eksisteerib harus. Lisainfot leiad artiklist "[Commit'ide kohta](https://docs.github.com/en/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/about-commits)".

### :keyboard: Tegevus: Sinu esimene commit

Järgmised sammud juhendavad sind läbi muudatuse commit'imise protsessi GitHubis. Commit salvestab muudatused nagu ümbernimetamine, sisu muutmine, uue faili loomine ja muud muudatused sinu projektis. Selles harjutuses nõuab muudatuse commit'imine esmalt uue faili lisamist sinu uude harusse.

> [!NOTE]
> `.md` on faililaiend, mis loob Markdown-faili. Markdown'i kohta saad rohkem teada artiklist "[Põhiline kirjutamise ja vormindamise süntaks](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)" meie dokumentatsioonis või läbides "[Suhtlemine Markdown'i abil](https://github.com/skills/communicate-using-markdown)" Skills kursuse.

1. Veendu vahekaardil **< > Code** oma repositooriumi päisemenüüs, et oled oma uuel harul `my-first-branch`.

2. Vali **Add file** rippmenüü ja kliki **Create new file**.

   ![create new file option](/images/create-new-file.png)

3. Sisesta väljale **Name your file...** tekst `PROFILE.md`.

4. Kopeeri alasse **Enter file contents here** järgmine sisu:

   ```
   Tere tulemast minu GitHubi profiilile!
   ```

   ![profile.md file screenshot](/images/my-profile-file.png)

5. Kliki **Commit changes...** üleval paremal sisukasti kohal. Commit'ide puhul saad sisestada lühikese commit-sõnumi, mis kirjeldab tehtud muudatusi. See sõnum aitab teistel mõista, mis on sinu commit'is. GitHub pakub lihtsa vaikesõnumi, kuid muudame seda harjutamiseks veidi. Esmalt sisesta esimesele tekstiväljale pealkirjaga "Commit message" tekst `Lisa PROFILE.md`.

   ![screenshot of adding a new file with a commit message](/images/commit-full-screen.png)

6. Selles tunnis ignoreerime teisi välju ja klikime **Commit changes**.
7. Oota umbes 20 sekundit ja seejärel värskenda seda lehte (seda, kus sa juhiseid loed). [GitHub Actions](https://docs.github.com/en/actions) uuendab automaatselt järgmise sammu juurde.

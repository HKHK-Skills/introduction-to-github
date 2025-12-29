<!--
  <<< Author notes: Step 3 >>>
  Just a historic note: the previous version of this step forced the learner
  to write a pull request description,
  checked that `main` was the receiving branch,
  and that the file was named correctly.
-->

## Samm 3: Ava pull request

_Suurepärane töö selle commit'iga! :sparkles:_

Nüüd, kui oled teinud muudatuse projektis ja loonud commit'i, on aeg jagada oma pakutud muudatust pull request'i kaudu!

**Mis on pull request?**: Koostöö toimub _[pull request](https://docs.github.com/en/get-started/quickstart/github-glossary#pull-request)_'il. Pull request näitab sinu haru muudatusi teistele inimestele ja võimaldab neil aktsepteerida, tagasi lükata või soovitada täiendavaid muudatusi sinu harule. Kõrvuti võrdluses hoiab see pull request muudatusi, mille just oma harus tegid, ja pakub nende rakendamist `main` projekti harule. Lisainfot pull request'ide kohta leiad artiklist "[Pull request'ide kohta](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)".

### :keyboard: Tegevus: Loo pull request

Võisid märgata pärast commit'i, et kuvati teade, mis näitas sinu hiljutist push'i harule ja pakkus nuppu **Compare & pull request**.

![screenshot of message and button](/images/compare-and-pull-request.png)

Pull request'i automaatseks loomiseks kliki **Compare & pull request** ja seejärel jätka allpool sammuga 6. Kui sa nuppu ei kliki, juhendavad alltoodud juhised sind pull request'i käsitsi seadistamisel.

1. Kliki oma repositooriumi päisemenüüs vahekaardil **Pull requests**.
2. Kliki **New pull request**.
3. Veendu rippmenüüs **base:**, et **main** on valitud.
4. Vali rippmenüü **compare:** ja kliki `my-first-branch`.

   ![screenshot showing both branch selections](/images/pull-request-branches.png)

5. Kliki **Create pull request**.
6. Sisesta oma pull request'ile pealkiri. Vaikimisi on pealkiri automaatselt sinu haru nimi. Selles harjutuses muudame välja tekstiks `Lisa minu esimene fail`.
7. Järgmine väli aitab sul kirjeldada tehtud muudatusi. Siin saad lisada kirjelduse selle kohta, mida oled siiani saavutanud. Meeldetuletuseks: sa lõid uue haru, lõid faili ja tegid commit'i.

   ![screenshot showing pull request](/images/Pull-request-description.png)

8. Kliki **Create pull request**. Sind suunatakse automaatselt sinu uuele pull request'ile.
9. Oota umbes 20 sekundit ja seejärel värskenda seda lehte (seda, kus sa juhiseid loed). [GitHub Actions](https://docs.github.com/en/actions) uuendab automaatselt järgmise sammu juurde.

> [!NOTE]
> Võid näha GitHub Actions'i tööd vahekaardil, kus pull request on avatud! Allolev pilt näitab rida, mida võid näha oma pull request'il pärast Action'i lõpetamist.
> 
> ![screenshot of an example of an actions line](/images/Actions-to-step-4.png)

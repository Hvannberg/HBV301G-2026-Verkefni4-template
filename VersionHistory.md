## Breytingasaga
<!--
Í stað þess að halda utan um alla commit-sögu er aðeins skráð formleg útgáfa (milestones) með Git tags (merkjum).  
Hver lína í töflunni samsvarar tag (merki) sem hefur verið sett í Git repositoryið.
> 🔖 Revision History er viðhaldið með **Git tags**.  
> Þegar ný útgáfa (t.d. drög eða baseline) er tilbúin, búið til tag í Git (`git tag -a vX.Y -m "message" && git push origin vX.Y`)  
> sem bætir einni línu við í töfluna hér að neðan.
-->
> 🔖 Taflan hér á eftir er búin til með því að keyra shell skrána `updatevisionhistory.sh` í bash terminal
>
>  `chmod +x updatevisionhistory.sh`
>
>  `./updatevisionhistory.sh`
>
>  Ef þú vilt skoða töfluna fyrst til að sjá hvernig hún kemur út geturðu gert eftirfarandi beint úr skelinni
> `git log -n 5 --pretty=format:"| %an | %ad | %s | %h |" --date=short -n 10 -- VersionHistory.md`


<!-- GIT_HISTORY_START -->
| Author | Date       | Message | Commit |
|--------|------------|---------|--------|
| _no commits found_ |  |  |  |

<!-- GIT_HISTORY_END -->

> Skoða allt: `git log -- "VISIONSCOPE.md" `

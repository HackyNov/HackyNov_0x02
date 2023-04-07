# Context

>__Alpha to Omega:__ As Yoda says !
>```
>       d77633d6
>    373        656
>  07f     ||     507
> 043      ||      4f5
> 141      ||      317
> f53              556
>  f50     ()     703
>    b72        303
>       6603a565
>```
>__Omega to Alpha:__ &#89&#101&#115&#32&#33

---
# Write-up

**Step by step:**
- Put all the hexa character together;

- Revert the chain;

- Convert the Hex to ACSII;

- Use the vigenere method with autokey, the context of the challenge should led you to try the greek letter 'omicron'.

- Change the sentance to speak like Yoda !

**TL;DR:**
>Use this [cyberchef recipe](https://cyberchef.org/#recipe=Find_/_Replace(%7B'option':'Regex','string':'%5C%5C%7C'%7D,'%20',true,false,true,false)Find_/_Replace(%7B'option':'Regex','string':'%5C%5C('%7D,'%20',true,false,true,false)Find_/_Replace(%7B'option':'Regex','string':'%5C%5C)'%7D,'%20',true,false,true,false)Remove_whitespace(true,true,true,true,true,false)Reverse('Character')From_Hex('Auto')) and paste the challenge then use to solve the first part. Then use this [tool](https://www.boxentriq.com/code-breaking/vigenere-cipher) from Boxentriq. Then put the verb at the beging like Yoda !


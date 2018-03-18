


## writing this because this took me way too long to learn it twice

-1. Request ssh access via namecheap chat/email support

0. git clone https://github.com/diafygi/acme-nosudo.git

1. Follow instructions of acme-no sudo because no fucking sudo here (don't bother trying the www. example because no sudo)

2. follow all instructions direct because we no rename user.key

3. when get to the web request check, get the long ass string look like 'tJfMTI_c3DFRe4pp2yW6IZdzs0MMybSYuO-_d3td9cQ.Vj-SO98owwl1LlgxrzlSOrVjXeZqhgtWQ_oaKPiEPiM'

4. go to public_html/domain/.well-known/acme-challenge/ and create file of first half of long ass string till the . as in tJfMTI_c3DFRe4pp2yW6IZdzs0MMybSYuO-_d3td9cQ

5. in the file paste the *WHOLE* LONG ASS STRING

6. verification done

7. Go to namecheap, manage ssl hosts

8. Upload/update certificate

9. Paste contents of signed.crt into certificate

10. Paste contents of domain.key into private key


DONE

11. figure out redirect www
# Aranäs VM-Tips

En mobilanpassad statisk anmälningssida för Aranäs VM-Tips.

## Så fungerar mailskick

Sidan kan publiceras på GitHub Pages, men GitHub Pages kan inte skicka mail själv eftersom det saknar backend. Formulären skickas därför via FormSubmit:

```html
https://formsubmit.co/tipsaranas@gmail.com
```

Första gången formuläret skickas kommer FormSubmit att skicka ett aktiveringsmail till `tipsaranas@gmail.com`. Efter att adressen har bekräftats skickas kommande anmälningar automatiskt dit.

## Publicera på GitHub Pages

1. Skapa ett nytt GitHub-repository.
2. Ladda upp `index.html`, `styles.css` och `README.md`.
3. Gå till repositoryts `Settings`.
4. Öppna `Pages`.
5. Välj branch `main` och folder `/root`.
6. Öppna GitHub Pages-länken när publiceringen är klar.

## Testa lokalt

Öppna `index.html` direkt i webbläsaren.

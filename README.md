from pathlib import Path

content = """# AMK-one Webshop

AMK-one is een moderne online webshop voor kleding, sneakers en accessoires.
Het project is gebouwd met HTML, CSS en JavaScript.

## Project beschrijving
Deze website is een demo webshop met:
- Trendy fashion layout
- Product secties (streetwear, sneakers, accessoires)
- Nieuwsbrief inschrijving
- Contactformulier
- Login pagina (simulatie)
- Redirect systeem (shop → login → terug naar pagina)

## Features
- Responsive webshop design
- Login pagina (demo)
- Shop sectie met producten
- Nieuwsbrief formulier
- Contact formulier
- Redirect systeem na login
- Moderne UI stijl

## Bestanden structuur
/project
├── index.html
├── login.html
├── style.css
├── script.js
└── assets/
    └── image1.png

## Hoe het werkt
1. Klik op Shop → je gaat naar login pagina  
2. Log in (demo)  
3. Je wordt doorgestuurd naar de shop sectie  
4. Nieuwsbrief en contact werken via redirect naar login  

## Technologieën
- HTML5
- CSS3
- JavaScript (basic)

## Disclaimer
Dit is een demo project en geen echte webshop.
Betalingen en accounts zijn niet actief.

## Auteur
AMK-one project gemaakt als oefen webshop design.
"""

file_path = Path("/mnt/data/README_AMK_one.md")
file_path.write_text(content, encoding="utf-8")

file_path

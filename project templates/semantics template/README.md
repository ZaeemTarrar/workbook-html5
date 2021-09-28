# Html5 - Semantics Template

**HTML** &nbsp; `index.html`

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Semantics</title>
    <!-- External Css -->
    <link rel="stylesheet" href="./style.css" />
  </head>
  <body>
    <div id="wrapper">
      <header>
        <header>Heading Heading</header>
        <main>
          <nav>Heading Main Navigation</nav>
        </main>
        <footer>Heading Footer</footer>
      </header>
      <main>
        <header>Main Heading</header>
        <main>
          Main Main
          <section>
            <header>Main Section 1 - Heading</header>
            <main>
              <article>
                <header>Main Section 1 - Article 1 - Heading</header>
                <main>
                  <hgroup>
                    <h1>
                      Main Section 1 - Article 1 - Main - Hgroup - Heading 1
                    </h1>
                    <h2>
                      Main Section 1 - Article 1 - Main - Hgroup - Heading 2
                    </h2>
                  </hgroup>
                </main>
                <footer>Main Section 1 - Article 1 - Footer</footer>
              </article>
              <article>
                <header>Main Section 1 - Article 2 - Heading</header>
                <main>Main Section 1 - Article 2 - Main</main>
                <footer>Main Section 1 - Article 2 - Foter</footer>
              </article>
            </main>
            <footer>Main Section 1 - Footer</footer>
          </section>
          <section>
            <header>Main Section 2 - Heading</header>
            <main>
              <aside>
                <header>Main Section 2 - Aside 1 - Heading</header>
                <main>Main Section 2 - Aside 1 - Main</main>
                <footer>Main Section 2 - Aside 1 - Footer</footer>
              </aside>
            </main>
            <footer>Main Section 2 - Footer</footer>
          </section>
        </main>
        <footer>Main Footer</footer>
      </main>
      <footer>
        <header>Footer Heading</header>
        <main>
          <address>Footer Main - Address</address>
        </main>
        <footer>Footer Footer</footer>
      </footer>
    </div>

    <!-- External JavaScript -->
    <script src="./script.js"></script>
  </body>
</html>
```

**CSS** &nbsp; `style.css`

```css
* {
  padding: 0;
  margin: 0;
  font-family: Comic Sans MS;
}
p {
  background-color: green;
  padding: 10px;
}
```

**JAVASCRIPT** &nbsp; `script.js`

```javascript
alert('JavaScript is Working .... ')
```

## DOWNLOAD

**LINUX/MAC** `workbook-html5 semantics template/*`

```cmd
git clone https://github.com/ZaeemTarrar/workbook-html5.git ; ; rm -rf workbook-html5/.git ; cp -r "workbook-html5/project templates/semantics template/" "./workbook-html5 semantics template" ; rm -rf "workbook-html5" ; cd "workbook-html5 semantics template" ;
```

**WINDOWS** `workbook-html5 semantics template/*`

```cmd
git clone https://github.com/ZaeemTarrar/workbook-html5.git && cd workbook-html5 && del /Q .git && mkdir "../zaeem-html5" && move ".\project templates\semantics template\*" "..\zaeem-html5" && cd ../ && rmdir /s /q "workbook-html5" && rename "zaeem-html5" "workbook-html5 semantics template" && cd "workbook-html5 semantics template"
```

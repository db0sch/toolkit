# TOOLKIT by db0sch

## Nav - Main - Footer

HTML:
```
<body>
    <nav>
      NAVBAR
    </nav>
    <main>
      MAIN
    </main>
    <footer>
      FOOTER
    </footer>
</body>
```

CSS:
```
nav {
  height: 100px; // => height can be changed
}

footer {
  height: 100px; // => height can be changed
}

main {
  min-height: calc(100vh - 200px);
  // compute the height of the main container with the height of the footer + navbar
  // I should do it with a scss variable.
  // this way, it sticks the footer at the bottom of the html view.
}

```

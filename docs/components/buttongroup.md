# Button Group

## Usage
The `<EsButtonGroup>` can be used to wrap multiple buttons (or other elements) and make sure their spacing is consistent and responsive.

The most simple example is with two buttons.
```handlebars
<EsButtonGroup>
<EsButton>
  click me <span>🐹</span>
</EsButton><EsButton>
  With a lot of text
</EsButton>
</EsButtonGroup>
```

It also works with links that look like buttons.
```handlebars
<EsButtonGroup>
  <a href="https://emberjs.com" class="es-button">Go to Ember homepage</a>
  <a href="https://guides.emberjs.com" class="es-button-secondary">Go to the Guides</a>
</EsButtonGroup>
```

You can also decide whether the buttons align left (default) or centered.
```handlebars
<EsButtonGroup @centered={{true}}>
<EsButton>
  click me <span>🐹</span>
</EsButton><EsButton>
  With a lot of text
</EsButton>
</EsButtonGroup>
```

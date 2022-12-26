# CachyOS-icons
Custom Icons Made for CachyOS

## How to Contribute

### How to Make Icons Inheritable


- Make Sure defs tag has this defenition

```svg
<defs>
 <style id="current-color-scheme" type="text/css">.ColorScheme-Text {
        color:#333333;
      }
      .ColorScheme-Background{
        color:#ffffff;
      }
      .ColorScheme-Highlight {
        color:#1dc7b5;
      }</style>
</defs>
```

- Each path that you need to inherit color from the OS, should have these Property
```svg
<path
class="ColorScheme-Highlight"
fill="currentColor"
/>
```
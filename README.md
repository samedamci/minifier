# minifier

## Description
Collection of scripts to [minify](https://en.wikipedia.org/wiki/Minification_(programming))
files like CSS and other. Scripts removes whitespaces, tabs,
comments and new line characters.

## Usage
```shell
$ minify_css input.css > output.css
```

### Example input file
```css
/* example CSS file to minify */

#container {
  color: rgba(13, 15, 73, 0.5);
  background: none;
  width: 100px;
  height: 100%;
}
```

### Example minified file
```css
#container{color:rgba(13,15,73,0.5);background:none;width:100px;height:100%;}
```

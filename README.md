# webstorm-live-templates
WebStorm live templates

## Usage
WebStorm has a shitty live template management system. Exporting settings and then importing them doesn't import live templates for some reason. I had my webstorm crash a couple of times and as a result I lost all of my live templates. 

I tried the settings repository too, but I had the same problem, I lose all of the live templates after the crash.

The only way I found to be working is [just copy pasting a raw XML](https://www.jetbrains.com/help/idea/15.0/sharing-live-templates.html). You can copy these templates and paste them right in the Live Templates screen under a custom folder.

## JavaScript
```xml
<template name="cl" value="console.log('$FILE$:$LINE$', $END$)" toReformat="false" toShortenFQNames="true">
  <variable name="FILE" expression="fileNameWithoutExtension()" defaultValue="" alwaysStopAt="false" />
  <variable name="LINE" expression="lineNumber()" defaultValue="" alwaysStopAt="false" />
  <context>
    <option name="JAVA_SCRIPT" value="true" />
    <option name="JS_EXPRESSION" value="true" />
    <option name="JSX_HTML" value="true" />
    <option name="JS_STATEMENT" value="true" />
  </context>
</template>
```

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
<template name="td" value="// TODO " toReformat="false" toShortenFQNames="true">
  <context>
    <option name="CSS_PROPERTY_VALUE" value="true" />
    <option name="CSS_DECLARATION_BLOCK" value="true" />
    <option name="CSS_RULESET_LIST" value="true" />
    <option name="CSS" value="true" />
    <option name="JAVA_SCRIPT" value="true" />
    <option name="JS_EXPRESSION" value="true" />
    <option name="JS_STATEMENT" value="true" />
  </context>
</template>
<template name="tdbd" value="// TODO:BEFORE_DEPLOY " toReformat="false" toShortenFQNames="true">
  <context>
    <option name="CSS_PROPERTY_VALUE" value="true" />
    <option name="CSS_DECLARATION_BLOCK" value="true" />
    <option name="CSS_RULESET_LIST" value="true" />
    <option name="CSS" value="true" />
    <option name="JAVA_SCRIPT" value="true" />
    <option name="JS_EXPRESSION" value="true" />
    <option name="JS_STATEMENT" value="true" />
  </context>
</template>
<template name="tdbg" value="// TODO:BUG " toReformat="false" toShortenFQNames="true">
  <context>
    <option name="CSS_PROPERTY_VALUE" value="true" />
    <option name="CSS_DECLARATION_BLOCK" value="true" />
    <option name="CSS_RULESET_LIST" value="true" />
    <option name="CSS" value="true" />
    <option name="JAVA_SCRIPT" value="true" />
    <option name="JS_EXPRESSION" value="true" />
    <option name="JS_STATEMENT" value="true" />
  </context>
</template>
<template name="tdper" value="// TODO:PERFORMANCE " toReformat="false" toShortenFQNames="true">
  <context>
    <option name="CSS_PROPERTY_VALUE" value="true" />
    <option name="CSS_DECLARATION_BLOCK" value="true" />
    <option name="CSS_RULESET_LIST" value="true" />
    <option name="CSS" value="true" />
    <option name="JAVA_SCRIPT" value="true" />
    <option name="JS_EXPRESSION" value="true" />
    <option name="JS_STATEMENT" value="true" />
  </context>
</template>
<template name="tdref" value="// TODO:REFACTOR " toReformat="false" toShortenFQNames="true">
  <context>
    <option name="CSS_PROPERTY_VALUE" value="true" />
    <option name="CSS_DECLARATION_BLOCK" value="true" />
    <option name="CSS_RULESET_LIST" value="true" />
    <option name="CSS" value="true" />
    <option name="JAVA_SCRIPT" value="true" />
    <option name="JS_EXPRESSION" value="true" />
    <option name="JSX_HTML" value="true" />
    <option name="JS_STATEMENT" value="true" />
  </context>
</template>
<template name="tdsec" value="// TODO:SECURITY " toReformat="false" toShortenFQNames="true">
  <context>
    <option name="CSS_PROPERTY_VALUE" value="true" />
    <option name="CSS_DECLARATION_BLOCK" value="true" />
    <option name="CSS_RULESET_LIST" value="true" />
    <option name="CSS" value="true" />
    <option name="JAVA_SCRIPT" value="true" />
    <option name="JS_EXPRESSION" value="true" />
    <option name="JS_STATEMENT" value="true" />
  </context>
</template>
<template name="tdui" value="// TODO:UI " toReformat="false" toShortenFQNames="true">
  <context>
    <option name="CSS_PROPERTY_VALUE" value="true" />
    <option name="CSS_DECLARATION_BLOCK" value="true" />
    <option name="CSS_RULESET_LIST" value="true" />
    <option name="CSS" value="true" />
    <option name="JAVA_SCRIPT" value="true" />
    <option name="JS_EXPRESSION" value="true" />
    <option name="JS_STATEMENT" value="true" />
  </context>
</template>
<template name="tdux" value="// TODO:UX " toReformat="false" toShortenFQNames="true">
  <context>
    <option name="CSS_PROPERTY_VALUE" value="true" />
    <option name="CSS_DECLARATION_BLOCK" value="true" />
    <option name="CSS_RULESET_LIST" value="true" />
    <option name="CSS" value="true" />
    <option name="JAVA_SCRIPT" value="true" />
    <option name="JS_EXPRESSION" value="true" />
    <option name="JS_STATEMENT" value="true" />
  </context>
</template>
```

## React
```xml
<template name="rsets" value="this.setState({&#10;  ...this.state,&#10;  $END$&#10;})" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JAVA_SCRIPT" value="true" />
    <option name="JS_EXPRESSION" value="true" />
    <option name="JSX_HTML" value="true" />
    <option name="JS_STATEMENT" value="true" />
  </context>
</template>
<template name="rcdm" value="componentDidMount() {&#10;  $END$&#10;}" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JAVA_SCRIPT" value="true" />
    <option name="JS_EXPRESSION" value="true" />
    <option name="JSX_HTML" value="true" />
    <option name="JS_STATEMENT" value="true" />
  </context>
</template>
<template name="rcdu" value="componentDidUpdate(prevProps, prevState) {&#10;  $END$&#10;}" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JAVA_SCRIPT" value="true" />
    <option name="JS_EXPRESSION" value="true" />
    <option name="JSX_HTML" value="true" />
    <option name="JS_STATEMENT" value="true" />
  </context>
</template>
<template name="rcwm" value="componentWillMount() {&#10;  $END$&#10;}" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JAVA_SCRIPT" value="true" />
    <option name="JS_EXPRESSION" value="true" />
    <option name="JSX_HTML" value="true" />
    <option name="JS_STATEMENT" value="true" />
  </context>
</template>
<template name="rcwrp" value="componentWillReceiveProps(nextProps) {&#10;  $END$&#10;}" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JAVA_SCRIPT" value="true" />
    <option name="JS_EXPRESSION" value="true" />
    <option name="JSX_HTML" value="true" />
    <option name="JS_STATEMENT" value="true" />
  </context>
</template>
<template name="rcwu" value="componentWillUpdate(nextProps, nextState) {&#10;  $END$&#10;}" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JAVA_SCRIPT" value="true" />
    <option name="JS_EXPRESSION" value="true" />
    <option name="JSX_HTML" value="true" />
    <option name="JS_STATEMENT" value="true" />
  </context>
</template>
<template name="rcwun" value="componentWillUnmount() {&#10;  $END$&#10;}" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JAVA_SCRIPT" value="true" />
    <option name="JS_EXPRESSION" value="true" />
    <option name="JSX_HTML" value="true" />
    <option name="JS_STATEMENT" value="true" />
  </context>
</template>
<template name="rscu" value="shouldComponentUpdate(nextProps, nextState) {&#10;  $END$&#10;}" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JAVA_SCRIPT" value="true" />
    <option name="JS_EXPRESSION" value="true" />
    <option name="JSX_HTML" value="true" />
    <option name="JS_STATEMENT" value="true" />
  </context>
</template>
```

## JSX
```xml
<template name="///" value="{/* $END$ */}" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JSX_HTML" value="true" />
  </context>
</template>
<template name="tdbdd" value="{/* TODO:BEFORE_DEPLOY $END$ */}" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JSX_HTML" value="true" />
  </context>
</template>
<template name="tdd" value="{/* TODO $END$ */}" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JSX_HTML" value="true" />
  </context>
</template>
<template name="tdbgg" value="{/* TODO:BUG $END$ */}" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JSX_HTML" value="true" />
  </context>
</template>
<template name="tdperr" value="{/* TODO:PERFORMANCE $END$ */}" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JSX_HTML" value="true" />
  </context>
</template>
<template name="tdreff" value="{/* TODO:REFACTOR $END$ */}" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JSX_HTML" value="true" />
  </context>
</template>
<template name="tduii" value="{/* TODO:UI $END$ */}" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JSX_HTML" value="true" />
  </context>
</template>
<template name="tduxx" value="{/* TODO:UX $END$ */}" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JSX_HTML" value="true" />
  </context>
</template>
```

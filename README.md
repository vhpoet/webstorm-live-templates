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
<template name="cl" value="console.log('$FILE$:$LINE$', $END$)" toReformat="false" toShortenFQNames="true">
  <variable name="FILE" expression="fileNameWithoutExtension()" defaultValue="" alwaysStopAt="false" />
  <variable name="LINE" expression="lineNumber()" defaultValue="" alwaysStopAt="false" />
  <context>
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
<template name="clhandle" value="$HANDLER_NAME$ = (e) =&gt; {&#10;  e.preventDefault()&#10;  &#10;  $END$&#10;}" toReformat="false" toShortenFQNames="true">
  <variable name="HANDLER_NAME" expression="" defaultValue="" alwaysStopAt="true" />
  <context>
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
<template name="eprev" value="e.preventDefault()" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
<template name="td" value="// TODO " toReformat="false" toShortenFQNames="true">
  <context>
    <option name="CSS" value="true" />
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
<template name="tdbd" value="// TODO:BEFORE_DEPLOY " toReformat="false" toShortenFQNames="true">
  <context>
    <option name="CSS" value="true" />
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
<template name="tdbg" value="// TODO:BUG " toReformat="false" toShortenFQNames="true">
  <context>
    <option name="CSS" value="true" />
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
<template name="tdper" value="// TODO:PERFORMANCE " toReformat="false" toShortenFQNames="true">
  <context>
    <option name="CSS" value="true" />
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
<template name="tdref" value="// TODO:REFACTOR " toReformat="false" toShortenFQNames="true">
  <context>
    <option name="CSS" value="true" />
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
<template name="tdsec" value="// TODO:SECURITY " toReformat="false" toShortenFQNames="true">
  <context>
    <option name="CSS" value="true" />
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
<template name="tdui" value="// TODO:UI " toReformat="false" toShortenFQNames="true">
  <context>
    <option name="CSS" value="true" />
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
<template name="tdux" value="// TODO:UX " toReformat="false" toShortenFQNames="true">
  <context>
    <option name="CSS" value="true" />
    <option name="JAVA_SCRIPT" value="true" />
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
<template name="ractionget" value="export const $NAME$ = (id) =&gt; ({&#10;  types: [types.$ACTIONTYPE$, types.$ACTIONTYPE$_SUCCESS, types.$ACTIONTYPE$_FAIL],&#10;  promise: (client) =&gt; client.get('/$URL$/' + id)&#10;})&#10;" toReformat="false" toShortenFQNames="true">
  <variable name="NAME" expression="" defaultValue="" alwaysStopAt="true" />
  <variable name="ACTIONTYPE" expression="" defaultValue="" alwaysStopAt="true" />
  <variable name="URL" expression="" defaultValue="" alwaysStopAt="true" />
  <context>
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
<template name="ractiongetall" value="export const $NAME$ = () =&gt; ({&#10;  types: [types.$ACTIONTYPE$, types.$ACTIONTYPE$_SUCCESS, types.$ACTIONTYPE$_FAIL],&#10;  promise: (client) =&gt; client.get('/$URL$')&#10;})&#10;" toReformat="false" toShortenFQNames="true">
  <variable name="NAME" expression="" defaultValue="" alwaysStopAt="true" />
  <variable name="ACTIONTYPE" expression="" defaultValue="" alwaysStopAt="true" />
  <variable name="URL" expression="" defaultValue="" alwaysStopAt="true" />
  <context>
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
<template name="ractionpost" value="export const $NAME$ = (data) =&gt; ({&#10;  types: [types.$ACTIONTYPE$, types.$ACTIONTYPE$_SUCCESS, types.$ACTIONTYPE$_FAIL],&#10;  promise: (client) =&gt; client.post('/$URL$', {data})&#10;})&#10;" toReformat="false" toShortenFQNames="true">
  <variable name="NAME" expression="" defaultValue="" alwaysStopAt="true" />
  <variable name="ACTIONTYPE" expression="" defaultValue="" alwaysStopAt="true" />
  <variable name="URL" expression="" defaultValue="" alwaysStopAt="true" />
  <context>
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
<template name="ractiontype" value="export const $ACTION$ = '$ACTION$'&#10;export const $ACTION$_SUCCESS = '$ACTION$_SUCCESS'&#10;export const $ACTION$_FAIL = '$ACTION$_FAIL'&#10;" toReformat="false" toShortenFQNames="true">
  <variable name="ACTION" expression="" defaultValue="" alwaysStopAt="true" />
  <context>
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
<template name="rcdm" value="componentDidMount() {&#10;  $END$&#10;}" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
<template name="rcdu" value="componentDidUpdate(prevProps, prevState) {&#10;  $END$&#10;}" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
<template name="rcwm" value="componentWillMount() {&#10;  $END$&#10;}" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
<template name="rcwrp" value="componentWillReceiveProps(nextProps) {&#10;  $END$&#10;}" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
<template name="rcwu" value="componentWillUpdate(nextProps, nextState) {&#10;  $END$&#10;}" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
<template name="rcwun" value="componentWillUnmount() {&#10;  $END$&#10;}" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
<template name="rreducer" value="case types.$ACTIONTYPE$:&#10;  return {&#10;    ...state,&#10;    $END$&#10;  }" toReformat="false" toShortenFQNames="true">
  <variable name="ACTIONTYPE" expression="" defaultValue="" alwaysStopAt="true" />
  <context>
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
<template name="rscu" value="shouldComponentUpdate(nextProps, nextState) {&#10;  $END$&#10;}" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
<template name="rsets" value="this.setState({&#10;  ...this.state,&#10;  $END$&#10;})" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
<template name="ststate" value="this.setState({&#10;  ...this.state,&#10;  $END$&#10;})" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
```

## JSX
```xml
<template name="///" value="{/* $END$ */}" description="comment" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JSX_HTML" value="true" />
  </context>
</template>
<template name="acl" value="&lt;a href=&quot;&quot; className={cx('$CLASSNAME$')}&gt;$END$&lt;/a&gt;" description="&lt;a&gt; with className" toReformat="false" toShortenFQNames="true">
  <variable name="CLASSNAME" expression="" defaultValue="" alwaysStopAt="true" />
  <context>
    <option name="JSX_HTML" value="true" />
  </context>
</template>
<template name="cln" value="className={cx('$END$')}" description="className" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
<template name="divcl" value="&lt;div className={cx('$CLASSNAME$')}&gt;$END$&lt;/div&gt;" description="&lt;div&gt; with className" toReformat="false" toShortenFQNames="true">
  <variable name="CLASSNAME" expression="" defaultValue="" alwaysStopAt="true" />
  <context>
    <option name="JSX_HTML" value="true" />
  </context>
</template>
<template name="divcll" value="&lt;div className={cx('$CLASSNAME$')}&gt;&#10;  $END$&#10;&lt;/div&gt;" description="&lt;div&gt; with className - multiline" toReformat="false" toShortenFQNames="true">
  <variable name="CLASSNAME" expression="" defaultValue="" alwaysStopAt="true" />
  <context>
    <option name="JSX_HTML" value="true" />
  </context>
</template>
<template name="spancl" value="&lt;span className={cx('$CLASSNAME$')}&gt;$END$&lt;/span&gt;" description="&lt;span&gt; with className" toReformat="false" toShortenFQNames="true">
  <variable name="CLASSNAME" expression="" defaultValue="" alwaysStopAt="true" />
  <context>
    <option name="JSX_HTML" value="true" />
  </context>
</template>
<template name="spancll" value="&lt;span className={cx('$CLASSNAME$')}&gt;&#10;  $END$&#10;&lt;/span&gt;" description="&lt;span&gt; with className - multiline" toReformat="false" toShortenFQNames="true">
  <variable name="CLASSNAME" expression="" defaultValue="" alwaysStopAt="true" />
  <context>
    <option name="JSX_HTML" value="true" />
  </context>
</template>
<template name="tdbdd" value="{/* TODO:BEFORE_DEPLOY $END$ */}" description="todo before deploy" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JSX_HTML" value="true" />
  </context>
</template>
<template name="tdbgg" value="{/* TODO:BUG $END$ */}" description="todo bug" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JSX_HTML" value="true" />
  </context>
</template>
<template name="tdd" value="{/* TODO $END$ */}" description="todo" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JSX_HTML" value="true" />
  </context>
</template>
<template name="tdperr" value="{/* TODO:PERFORMANCE $END$ */}" description="todo performance" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JSX_HTML" value="true" />
  </context>
</template>
<template name="tdreff" value="{/* TODO:REFACTOR $END$ */}" description="todo refactor" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JSX_HTML" value="true" />
  </context>
</template>
<template name="tduii" value="{/* TODO:UI $END$ */}" description="todo UI" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JSX_HTML" value="true" />
  </context>
</template>
<template name="tduxx" value="{/* TODO:UX $END$ */}" description="todo UX" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JSX_HTML" value="true" />
  </context>
</template>
```

## CSS
```
<template name="dbl" value="display: block;" description="display: block" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="CSS" value="true" />
  </context>
</template>
<template name="txtc" value="text-align: center;" description="text-align: center" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="CSS" value="true" />
  </context>
</template>
<template name="txtr" value="text-align: right;" description="text-align: right" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="CSS" value="true" />
  </context>
</template>
```

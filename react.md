```xml
<template name="ractiondel" value="export const $NAME$ = (id) =&gt; ({&#10;  types: [types.$ACTIONTYPE$, types.$ACTIONTYPE$_SUCCESS, types.$ACTIONTYPE$_FAIL],&#10;  promise: client =&gt; client.del('/$URL$/' + id)&#10;})&#10;" description="delete action" toReformat="false" toShortenFQNames="true">
  <variable name="NAME" expression="" defaultValue="" alwaysStopAt="true" />
  <variable name="ACTIONTYPE" expression="" defaultValue="" alwaysStopAt="true" />
  <variable name="URL" expression="" defaultValue="" alwaysStopAt="true" />
  <context>
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
<template name="ractionget" value="export const $NAME$ = (id) =&gt; ({&#10;  types: [types.$ACTIONTYPE$, types.$ACTIONTYPE$_SUCCESS, types.$ACTIONTYPE$_FAIL],&#10;  promise: client =&gt; client.get('/$URL$/' + id)&#10;})&#10;" description="get action" toReformat="false" toShortenFQNames="true">
  <variable name="NAME" expression="" defaultValue="" alwaysStopAt="true" />
  <variable name="ACTIONTYPE" expression="" defaultValue="" alwaysStopAt="true" />
  <variable name="URL" expression="" defaultValue="" alwaysStopAt="true" />
  <context>
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
<template name="ractiongetall" value="export const $NAME$ = () =&gt; ({&#10;  types: [types.$ACTIONTYPE$, types.$ACTIONTYPE$_SUCCESS, types.$ACTIONTYPE$_FAIL],&#10;  promise: client =&gt; client.get('/$URL$')&#10;})&#10;" description="get all action" toReformat="false" toShortenFQNames="true">
  <variable name="NAME" expression="" defaultValue="" alwaysStopAt="true" />
  <variable name="ACTIONTYPE" expression="" defaultValue="" alwaysStopAt="true" />
  <variable name="URL" expression="" defaultValue="" alwaysStopAt="true" />
  <context>
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
<template name="ractionpost" value="export const $NAME$ = (data) =&gt; ({&#10;  types: [types.$ACTIONTYPE$, types.$ACTIONTYPE$_SUCCESS, types.$ACTIONTYPE$_FAIL],&#10;  promise: client =&gt; client.post('/$URL$', {data})&#10;})&#10;" description="post action" toReformat="false" toShortenFQNames="true">
  <variable name="NAME" expression="" defaultValue="" alwaysStopAt="true" />
  <variable name="ACTIONTYPE" expression="" defaultValue="" alwaysStopAt="true" />
  <variable name="URL" expression="" defaultValue="" alwaysStopAt="true" />
  <context>
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
<template name="ractiontype" value="export const $ACTION$ = '$ACTION$'&#10;export const $ACTION$_SUCCESS = '$ACTION$_SUCCESS'&#10;export const $ACTION$_FAIL = '$ACTION$_FAIL'&#10;" description="action type" toReformat="false" toShortenFQNames="true">
  <variable name="ACTION" expression="" defaultValue="" alwaysStopAt="true" />
  <context>
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
<template name="rcdm" value="componentDidMount() {&#10;  $END$&#10;}" description="componentDidMount" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
<template name="rcdu" value="componentDidUpdate(prevProps, prevState) {&#10;  $END$&#10;}" description="componentDidUpdate" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
<template name="rcwm" value="componentWillMount() {&#10;  $END$&#10;}" description="componentWillMount" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
<template name="rcwrp" value="componentWillReceiveProps(nextProps) {&#10;  $END$&#10;}" description="componentWillReceiveProps" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
<template name="rcwu" value="componentWillUpdate(nextProps, nextState) {&#10;  $END$&#10;}" description="componentWillUpdate" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
<template name="rcwun" value="componentWillUnmount() {&#10;  $END$&#10;}" description="componentWillUnmount" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
<template name="rreducer" value="case types.$ACTIONTYPE$:&#10;  return {&#10;    ...state,&#10;    $END$&#10;  }" description="reducer" toReformat="false" toShortenFQNames="true">
  <variable name="ACTIONTYPE" expression="" defaultValue="" alwaysStopAt="true" />
  <context>
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
<template name="rscu" value="shouldComponentUpdate(nextProps, nextState) {&#10;  $END$&#10;}" description="shouldComponentUpdate" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
<template name="rsets" value="this.setState({&#10;  ...this.state,&#10;  $END$&#10;})" description="setState" toReformat="false" toShortenFQNames="true">
  <context>
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
```

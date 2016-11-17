```xml
<template name="afn" value="($var1$) =&gt; {&#10;  $END$&#10;}" description="arrow function" toReformat="false" toShortenFQNames="true">
  <variable name="var1" expression="" defaultValue="" alwaysStopAt="true" />
  <context>
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
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
<template name="imp" value="import $var1 from '$var1$'" description="import x from 'x'" toReformat="false" toShortenFQNames="true">
  <variable name="var1" expression="" defaultValue="" alwaysStopAt="true" />
  <context>
    <option name="JAVA_SCRIPT" value="true" />
  </context>
</template>
<template name="impp" value="import { $var1$ } from '$var2$'" description="import { x } from 'y'" toReformat="false" toShortenFQNames="true">
  <variable name="var1" expression="" defaultValue="" alwaysStopAt="true" />
  <variable name="var2" expression="" defaultValue="" alwaysStopAt="true" />
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

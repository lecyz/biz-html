$visitor: monster;

body {<br/>
&nbsp;&nbsp;@if $visitor == monster {<br/>
&nbsp;&nbsp;&nbsp;&nbsp;content: "Fuck off!";<br/>
} <br/>
&nbsp;&nbsp;@else if $visitor == human {<br/>
&nbsp;&nbsp;&nbsp;&nbsp;content: "Hello World!"<br/>
&nbsp;&nbsp;}<br/>
}
<br/><br/>
<h1>Fuck off!</h1>

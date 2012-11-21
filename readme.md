$visitor: monster;

body {
  @if $visitor == monster {
    color: red;
    content: "Fuck off!";
  } 

  @else if $visitor == human {
    content: "Hello World!"
    &:hover{
      -wekbit-transform: scale(1.1);
    }
}
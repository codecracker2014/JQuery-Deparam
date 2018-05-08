# JQuery-Deparam
Reverse function of $.param

$.fn.deparamQueryString("name=test&y=e&name=test")
Output: {name: "test", y: "e"}

$.fn.deparamQueryString("name=test&y=e")
Output: {name: "test", y: "e"}

$.fn.deparamQueryString("name[]=test&y=e&name[]=testB")
Output: {name[]: Array(2), y: "e"}


Yagami
======

<h2>Another Window Modal </h2>

Simple Ajax content

<pre>
  window.Light = YagamiBox.init({
      url : '/my/form/',
      title: 'My Window',
      width:'600px',
      height:'450px',
      afterLoaded : function(){
         // do something :D
      }
  });
</pre>


<button id="openBox"> View Box Animated</button>

<button id="openBox2"> View Box 2 No Animated</button>


<script type="text/javascript">

$('#openBox').click(function(){

var LBox = TheLigthBox.init({
url : 'remote.html',
title:'The Box is Yagami',
width:'1000px',
height:'500px',
animated:true,
onBeForeOpen : function(){
console.log(this);
}
});
});

$('#openBox2').click(function(){

var LBox = TheLigthBox.init({
url : 'remote.html',
title:'Yagami Box',
width:'1000px',
height:'500px',
autohide:true,
onBeForeOpen : function(){
console.log(this);
}
});
});


</script>

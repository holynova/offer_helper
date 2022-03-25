<script>
  let time = new Date().toLocaleTimeString()
  function init() {
   setInterval(() => {
     time = new Date().toLocaleTimeString()
   }, 1000);
  }
  init()
</script>

<div>
  <h1>齐天大圣到此一游</h1>
  <h3>time is {time}</h3>
  <button>reload</button>
</div>


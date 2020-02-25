<!DOCTYPE html>
<html>
<body>

<h2 id="iframeCatcher">iframe Catcher</h2>

<button id="iframePitcher" onclick="pitchMessage()">Pitch to Host</button>

<script>
function pitchMessage() {
  window.parent.postMessage("W3Schools domain - Hi Parent!", "*");
}
</script>

</body>
</html>

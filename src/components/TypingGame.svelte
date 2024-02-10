<script lang="ts">
  type Game = "waiting for input" | "in progress" | "game over";
  type Word = string;
  let game: Game = "waiting for input";
  let typedLetter = "";
  let words: Word[] = "The quick brown fox jumps over the lazy dog".split(" ");
  let wordIndex = 0;
  let letterIndex = 0;
  let correctLetters = 0;
  let wordsEl: HTMLDivElement;
  let letterEl: HTMLSpanElement;
  let inputEl: HTMLInputElement;
</script>

<div>
  <h1>typing game</h1>
</div>

<style></style>

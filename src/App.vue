<template>
  <div id="app">
    <Container>
      <ChatWindow>
        <ChatMessage username="Ivan" time="21.12.2019 05:00:50"
          >Hello, World!!!</ChatMessage
        >
      </ChatWindow>
    </Container>
  </div>
</template>

<script>
import Container from "./components/Container.vue";
import ChatMessage from "./components/ChatMessage.vue";
import ChatWindow from "./components/ChatWindow.vue";

export default {
  name: "App",
  components: {
    Container,
    ChatMessage,
    ChatWindow,
  },
};
</script>

<style>
body {
  margin: 0;
  background-color: #f9f9fa;
}
</style>

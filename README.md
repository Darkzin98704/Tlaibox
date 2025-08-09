# Tlaibox
Jogo chamado Tlaibox
<!-- index.html -->
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <title>Tlaibox - O mundo que você cria</title>
  <style>
    body { margin: 0; font-family: Arial, sans-serif; background: #1a1a1a; color: white; text-align: center; }
    canvas { display: block; margin: auto; }
    h1 { ma
    // server.js
const express = require('express');
const app = express();
const http = require('http').Server(app);
const WebSocket = require('ws');
const wss = new WebSocket.Server({ server: http });

app.use(express.static('public'));

wss.on('connection', (ws) => {
  console.
  server.js

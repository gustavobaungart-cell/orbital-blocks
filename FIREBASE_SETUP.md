# Firebase ranking (Orbital Blocks)

## 1) Criar projeto
1. Acesse https://console.firebase.google.com/
2. Crie um projeto
3. Em **Firestore Database**, clique em **Criar banco** (modo produção ou teste)

## 2) Configurar regras
1. Abra Firestore > Rules
2. Cole o conteúdo de `firestore.rules.txt`
3. Publicar regras

## 3) Configurar app web
1. Configurações do projeto > Seus apps > Web app
2. Copie as credenciais
3. Preencha `firebase-config.js`

## 4) Arquivos para subir no host
- `orbital_blocks_app_firebase.html`
- `firebase-config.js`

## 5) Teste
- Abra o app
- Jogue uma partida
- Confira coleção `scores` no Firestore

## Observação
- Esse setup já permite ranking global básico para teste com amigos.
- Para produção, adicionar proteção anti-spam (ex.: Cloud Functions + App Check).

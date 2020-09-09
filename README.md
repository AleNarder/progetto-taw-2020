# TAW 2020

Istruzioni su come eseguire l'applicazione in ambiente locale e in produzione
I percorsi che con prefisso . si intendo dalla radice del progetto

## Setup
#### Download dei repositories
```
git submodule init
git submodule update
```

#### Backend

```
cd backend

npm install
```

#### Frontend

``` 	
cd ./frontend

npm install

npm run build:android

npm run build:electron:linux
```
## Testing 
#### Android
```
aprire la cartella ./frontend/android in android studio ed eseguire l'applicazione
```
#### Web 
##### Con il backend in locale
```
cd ./backend

npm run dev

cd ./frontend

npm run serve
```
##### Con il backend in produzione 
```
cd ./frontend
npm run start
```
#### Electron 

installare il file .deb presente in  ./frontend/dist/installers
```

## Ambiente di produzione

Applicazione in esecuzione

https://taw-frontend.herokuapp.com/
# TAW 2020

Istruzioni su come eseguire l'applicazione in ambiente locale e in produzione

## Ambiente locale

### Backend
#### 1. Preparazione
```
cd backend
npm install
npm run build
```
#### 2. Testing
```
1. npm run dev
```

### Frontend
#### 1.  Preparazione:
``` 	
cd frontend
# Installa le dipendenze
npm install
# Compila i sorgenti per l'esecuzione su browser
npm run build:web 
# Compila i sorgenti per l'esecuzione su android in ./android
npm run build:android
# genera un file .deb installabile in ./dist/installers
npm run build:electron:linux
# genera la documentazione dei sorgenti
npm run build:docs
```
####  2.  Testing (con backend in locale)
##### 1. Android:
```
aprire da android studio ./android ed eseguire
```
##### 2. Web: 
```
npm run start
```
##### 3. Electron: 
```
installare il file .deb presente in  ./dist/installers
```
##### 4.  Documentazione: 
```
npm run start:docs
```

## Ambiente di produzione e risorse

Applicazione in esecuzione

https://taw-frontend.herokuapp.com/
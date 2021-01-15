# API Consulta CNPJ em Javascript (apiconsultacnpj.com.br)

### Consultar dados de um determinado CNPJ
```javascript
fetch(`https://api-publica.speedio.com.br/buscarcnpj?cnpj=00000000000191`)
  .then((body) => body.json())
	.then((data) => {
    // console.log(data)
  })
  .catch((error) => {})
```

### Consultar quantas empresas existem em um determinado CEP
```javascript
fetch(`https://api-publica.speedio.com.br/buscar-atividade-location-distance?atividade=tecnologia&location=01009-907&distance=5`)
  .then((body) => body.json())
	.then((data) => {
    // console.log(data)
  })
  .catch((error) => {})
```

### Consultar a idade média de vida de um determinado setor
```javascript
fetch(`https://api-publica.speedio.com.br/buscar-atividade-idade-media?atividade=mercado&location=SP`)
  .then((body) => body.json())
	.then((data) => {
    // console.log(data)
  })
  .catch((error) => {})
```

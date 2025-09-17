# Configurar uma fonte OPC UA

## Criar um ambiente virtual (recomendado)

Ao usar um ambiente virtual, você isola as dependências do projeto, evitando que interfiram no sistema global e, ao mesmo tempo, contorna o problema de permissões.

### Instale o pacote para criar ambientes virtuais (se necessário):

```bash
sudo apt-get install python3-venv
```

### Crie o ambiente virtual:

```bash
python3 -m venv myenv
```

### Ative o ambiente virtual:

```bash
source myenv/bin/activate
```

### Agora, instale o pacote opcua:

```bash
pip install opcua
```

### Quando terminar de trabalhar, desative o ambiente virtual:

```bash
deactivate
```

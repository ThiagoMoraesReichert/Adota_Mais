# Adota+
Projeto referente a matéria de Implementação de Software - Universidade do Vale do Rio dos Sinos

# Descrição:
A aplicação tem como foco principal conectar animais de rua abandonados a pessoas interessadas em adotá-los de forma segura e responsável.

### Tecnologias utilizadas: 
- Python
- HTML
- CSS
- Bcrypt Python
- SQLAlchemy
- Flask

# Como rodar o projeto:
### Comandos:

## 1 - Criar ambiente virtual
```
python -m venv venv
```

## 2 - Ativar ambiente
#### Linux/Mac:
```
source venv/bin/activate
```
#### Windows PowerShell:
```
venv\Scripts\Activate
```

## 3 - Instalar dependências
```
pip install Flask
pip install flask_sqlalchemy
pip install bcrypt_python

```

## 4 - Definir variaveis de ambiente
#### Linux/Mac:
```
export FLASK_APP=run.py
```
#### Windows PowerShell:
```
$env:FLASK_APP="run.py"
```

## 5 - Rodar a aplicação
```
flask run
```

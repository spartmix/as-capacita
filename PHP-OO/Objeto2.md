# Objeto

```php
<?php

class Usuario
{
    public $id;
	public $nome;
    public $email;

    public function setId($id)
    {
        $this->id = $id;
    }
	
	public function setNome($nome)
    {
        $this->nome = $nome;
    }

    public function setEmail($email)
    {
        $this->email = $email;
    }

    public function getId()
    {
        return $this->id;
    }
	
	public function getNome()
    {
        return $this->nome;
    }

    public function getEmail()
    {
        return $this->email;
    }
}

$usuario = new Usuario();

$usuario->setId(1);
$usuario->setNome('Marvin');
$usuario->setEmail('marvin@coracaodeouro.com');

echo $usuario->getId() . '<br>';
echo $usuario->getNome() . '<br>';
echo $usuario->getEmail() . '<br>';
```

[<< Anterior](https://github.com/agenciasys/as-capacita/blob/master/PHP-OO/Metodo.md#m%C3%A9todo)
|
[Próximo >>](https://github.com/agenciasys/as-capacita/blob/master/PHP-OO/Heranca.md#heran%C3%A7a)

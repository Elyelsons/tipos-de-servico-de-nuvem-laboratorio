# Comandos SQL utilizados no Lab

```sql
CREATE TABLE Produtos (
    Id INT PRIMARY KEY,
    Nome VARCHAR(50),
    Preco DECIMAL(10, 2)
);

INSERT INTO Produtos VALUES (1, 'Teclado', 199.99);
INSERT INTO Produtos VALUES (2, 'Mouse', 99.90);

SELECT * FROM Produtos;

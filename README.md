#TabelaCopadomundoSQL

CREATE TABLE CampeoesCopaDoMundo (
    Pais VARCHAR(100) NOT NULL,
    Ano INT NOT NULL,
    PRIMARY KEY (Pais, Ano)
);

INSERT INTO CampeoesCopaDoMundo (Pais, Ano) VALUES
    ('Uruguai', 1930),
    ('Itália', 1934),
    ('Itália', 1938),
    ('Uruguai', 1950),
    ('Alemanha Ocidental', 1954),
    ('Brasil', 1958),
    ('Brasil', 1962),
    ('Inglaterra', 1966),
    ('Brasil', 1970),
    ('Alemanha Ocidental', 1974),
    ('Argentina', 1978),
    ('Itália', 1982),
    ('Argentina', 1986),
    ('Alemanha Ocidental', 1990),
    ('Brasil', 1994),
    ('França', 1998),
    ('Brasil', 2002),
    ('Itália', 2006),
    ('Espanha', 2010),
    ('Alemanha', 2014),
    ('França', 2018);

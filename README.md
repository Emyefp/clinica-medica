# Clínica Simples

Projeto acadêmico simples para cadastrar e organizar consultas médicas. Feito com C#, ASP.NET Core, HTML, CSS, JavaScript e SQLite.

## O que dá para fazer

- Cadastrar uma consulta com paciente, médico, especialidade, data e situação.
- Buscar pelo nome do paciente, médico ou especialidade.
- Filtrar pela situação da consulta.
- Ordenar pela data ou pelo nome do paciente.
- Excluir uma consulta.

## Como executar

1. Instale o SDK do .NET 8: https://dotnet.microsoft.com/download/dotnet/8.0
2. Abra o terminal nesta pasta.
3. Execute `dotnet restore`.
4. Execute `dotnet run`.
5. Abra o endereço local mostrado no terminal (normalmente `http://localhost:5000`).

O banco de dados `dados/clinica.db` será criado automaticamente na primeira execução.

## Organização

- `Program.cs`: inicialização da aplicação e rotas da API.
- `Consulta.cs`: dados de uma consulta.
- `ConsultaRepository.cs`: comandos simples para guardar e buscar dados no SQLite.
- `wwwroot/`: página, estilos e interações do navegador.

> Este projeto é um exercício acadêmico. Use apenas dados fictícios; ele não foi feito para guardar informações reais de pacientes.

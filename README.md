# MuleLogic

## Descrição

Este repositório contém a especificação RAML da API BookMyHotel. A API BookMyHotel permite o gerenciamento de hotéis, registros de hóspedes e reservas. Ela fornece funcionalidades para listar hotéis, criar registros de hóspedes e gerenciar reservas.

## Detalhes da API

- **Base URI:** [http://bookmyhotel.com](http://bookmyhotel.com)
- **Tipo de Mídia Suportado:** `application/json`

## Tipos de Dados

A API utiliza os seguintes tipos de dados:

- `Error`: Erros gerais da API.
- `Hotel`: Informações sobre hotéis.
- `Registration`: Dados de registro de hóspedes.
- `Status`: Status das operações da API.

## Recursos Principais

### /registrations

- **GET**: Recupera uma lista de registros de hóspedes.
- **POST**: Cria um novo registro de hóspede.

### /registrations/

- **GET**: Obtém os detalhes de um registro de hóspede específico.
- **PATCH**: Atualiza um registro de hóspede.
- **DELETE**: Exclui um registro de hóspede.

### /hotels

- **GET**: Lista hotéis com base em parâmetros de consulta, como cidade, estado e país.
- **POST**: Cria um novo hotel.

### /hotels/

- **GET**: Obtém informações detalhadas sobre um hotel específico.
- **PATCH**: Atualiza informações de um hotel.
- **DELETE**: Exclui um hotel.

### /bookings

- **GET**: Lista todas as reservas disponíveis.
- **PATCH**: Atualiza informações de reserva.
- **DELETE**: Exclui uma reserva.

### /bookings/

- **GET**: Obtém detalhes de uma reserva específica.
- **PATCH**: Atualiza informações de uma reserva.
- **DELETE**: Exclui uma reserva.

## Uso

Você pode usar esta especificação RAML como base para criar a documentação completa da API BookMyHotel e implementar a API correspondente. Certifique-se de incluir exemplos e detalhes adicionais na documentação real, além de informações de autenticação e permissões, se necessário, para tornar a API totalmente funcional e compreensível para os usuários.

Para detalhes completos sobre os parâmetros de solicitação, respostas e exemplos de uso, consulte o código RAML fornecido na pasta `datatypes`.

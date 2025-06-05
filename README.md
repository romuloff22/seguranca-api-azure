# Documentação das Atividades Cursadas - Gerenciamento de APIs com Azure API Management

## Visão Geral
Este documento resume os principais conceitos e aprendizados sobre o serviço Azure API Management, cobrindo desde fundamentos até políticas avançadas de segurança.

## Módulo 1: Introdução ao Azure API Management

### O que é Azure API Management?
- Serviço completo para publicar, proteger, monitorar e analisar APIs
- Funciona como um gateway para APIs existentes
- Oferece recursos de transformação, limitação de taxa, caching e monitoramento
- Suporta APIs hospedadas em qualquer lugar (nuvem ou local)

## Módulo 2: Componentes Principais

### Gateway de API
- Ponto de entrada único para todas as APIs
- Funcionalidades:
  - Roteamento de requisições
  - Transformação de payloads
  - Limitação de taxa (rate limiting)
  - Cache de respostas
  - Balanceamento de carga

### Portal do Desenvolvedor
- Interface autoatendimento para consumidores de API
- Documentação automática das APIs
- Espaço para testes interativos
- Gerenciamento de chaves de assinatura

## Módulo 3: Políticas de Gerenciamento de API

### Tipos de Políticas
- **Políticas de entrada**: Aplicadas a requisições recebidas
- **Políticas de saída**: Aplicadas a respostas enviadas
- **Políticas de erro**: Aplicadas quando ocorrem erros

### Exemplos de Políticas Comuns
- Transformação XML/JSON
- Validação de JWT
- Limitação de taxa
- Caching
- Redefinição de headers

### Políticas Avançadas
- Composição de APIs (mashup)
- Enriquecimento de payloads
- Chamadas condicionais
- Circuit breaker
- Mocking de respostas

## Módulo 4: Segurança de APIs

### Proteção com Assinaturas
- Uso de chaves de assinatura (subscription keys)
- Gerenciamento no portal do desenvolvedor
- Níveis de escopo:
  - Produto
  - API
  - Operação

### Proteção com Certificados
- Autenticação mútua (mTLS)
- Validação de certificados clientes
- Configuração no nível do gateway
- Políticas de validação:
  - Emissor
  - Assunto
  - Thumbprint
  - Validade

## Fluxo de Trabalho Típico
1. Importar definição de API (OpenAPI/Swagger)
2. Configurar endpoints backend
3. Definir políticas de transformação/segurança
4. Publicar no portal do desenvolvedor
5. Monitorar uso e desempenho

## Melhores Práticas
- Usar versionamento de APIs
- Implementar limitação de taxa para prevenir abuso
- Documentar completamente no portal
- Monitorar métricas de uso e desempenho
- Implementar autenticação em camadas

## Casos de Uso Comuns
- Consolidação de múltiplos serviços backend
- Modernização de APIs legadas
- Criação de ecossistemas de desenvolvedores
- Monetização de APIs
- Governança de APIs em grandes organizações

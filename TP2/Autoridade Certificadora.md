# Autoridade Certificadora
## Requisitos
- Entidade confiável externa ao sistema desenvolvido
- Processo de emissão e associação de certificados com as diferentes entidades do sistema tenha em consideração a possibilidade de mecanismos heterogéneos (i.e. diferentes API, múltiplos mecanismos de autenticação)
- A emissão de certificados usa o método *Certificate Signing Request* (CSR)
- Atualmente, a comunicação com entidades externas é feita por uma API REST
- A Autoridade Certificadora disponibiliza a lista de certificados revogados através de um serviço *Online Certificate Status Protocol* (OCSP)
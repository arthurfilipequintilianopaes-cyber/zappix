### Prompt para Desenvolvimento de App Gerador de QR Code para PIX

**Descrição Geral:**  
Desenvolva um aplicativo mobile (iOS e Android) ou web responsivo para gerar QR codes para pagamentos via PIX. O app deve permitir que usuários criem QR codes personalizados com dados de pagamento PIX, incluindo chave PIX, valor, descrição e informações adicionais. O foco é na simplicidade, segurança e conformidade com as especificações do Banco Central do Brasil para PIX.

**Funcionalidades Principais:**
- **Cadastro de Chaves PIX:** Interface para adicionar e gerenciar múltiplas chaves PIX (CPF/CNPJ, e-mail, telefone, chave aleatória).
- **Geração de QR Code:** Campos para inserir valor, descrição do pagamento e dados do recebedor. Geração automática do QR code compatível com o padrão PIX.
- **Personalização:** Opções para adicionar imagem de perfil, logo ou texto personalizado ao QR code.
- **Histórico e Compartilhamento:** Salvar histórico de QR codes gerados e permitir compartilhamento via WhatsApp, e-mail ou cópia para área de transferência.
- **Validação:** Verificação em tempo real dos dados inseridos para garantir conformidade com o formato PIX.
- **Modo Offline:** Funcionalidade básica de geração sem necessidade de internet (exceto para validação opcional).

**Requisitos Técnicos:**
- **Linguagem/Framework:** React Native para mobile ou React.js para web, com integração de bibliotecas como `qrcode` ou `react-qr-code` para geração de QR codes.
- **API PIX:** Integração com APIs do Banco Central ou provedores de pagamento para validação de chaves e geração dinâmica.
- **Segurança:** Armazenamento seguro de dados usando criptografia local (ex: AsyncStorage com encriptação).
- **Design:** UI/UX intuitiva, seguindo guidelines do Material Design ou Human Interface Guidelines. Suporte a temas claro/escuro.
- **Compatibilidade:** Compatível com leitores de QR code padrão e apps de banco que suportam PIX.

**Fluxo de Uso Básico:**
1. Usuário abre o app e seleciona "Gerar QR Code".
2. Insere chave PIX, valor e descrição.
3. App valida os dados e gera o QR code.
4. Usuário visualiza, personaliza e compartilha o QR code.

**Considerações Adicionais:**
- Garantir acessibilidade (suporte a leitores de tela).
- Implementar testes unitários e de integração.
- Documentação completa para manutenção futura.
- Estimativa de prazo: 4-6 semanas para versão MVP.

Use este prompt como base para implementar o app, ajustando conforme necessidades específicas do projeto.

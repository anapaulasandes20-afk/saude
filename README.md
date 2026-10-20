# INDUFAR — fluxo em três etapas

1. Mini página de entrada com botão Continuar.
2. Leitor de QR pela câmera ou imagem.
3. Resultado AUTÉNTICO com página ilustrativa T.G. 15 mg, ou AUTENTICIDAD NO CONFIRMADA.

## Configuração
Edite `config.js` e troque `COLE_AQUI_O_CONTEUDO_EXATO_DO_QR_CODE_ORIGINAL` pelo conteúdo exato do QR autorizado. Qualquer outro conteúdo será recusado.

Publique em HTTPS (Netlify ou GitHub Pages) para permitir acesso à câmera.

**Limitação:** isto é um protótipo visual/local, não uma integração com AuthNow. O código válido fica visível no JavaScript e pode ser copiado; não comprova autenticidade física. Para produtos reais, use o sistema oficial ou validação segura autorizada pela INDUFAR. A ilustração da embalagem é provisória e deve ser substituída por imagem oficial autorizada antes da publicação.
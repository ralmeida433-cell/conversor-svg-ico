# Configuração do Google AdSense

## ⚠️ Importante: Passos para Completar a Verificação

O arquivo `index.html` já contém o código do Google AdSense, mas você precisa completar os seguintes passos:

### 1. **Adicionar o Código de Verificação do Google**

No Google AdSense, você receberá um código de verificação de site. Você precisa:

1. Ir para **Google AdSense > Configurações > Sites**
2. Copiar o código de verificação fornecido
3. Abrir o arquivo `index.html`
4. Localizar a linha: `<meta name="google-site-verification" content="" />`
5. Colar o código entre as aspas: `<meta name="google-site-verification" content="SEU_CODIGO_AQUI" />`
6. Fazer commit e push das alterações

### 2. **Verificar o Arquivo ads.txt**

O arquivo `ads.txt` já está presente no repositório com seu ID de publisher. Certifique-se de que:

- O arquivo está na raiz do domínio (✓ Já configurado)
- Contém: `google.com, ca-pub-9919912806246142, DIRECT, f08c47fec0942fa0`

### 3. **Solicitar Verificação no Google AdSense**

Após adicionar o código de verificação:

1. Acesse o Google AdSense
2. Clique em **Verificar** na página de verificação do site
3. O Google levará alguns minutos a algumas horas para verificar

### 4. **Conformidade com Políticas**

Seu site está em conformidade com as políticas do AdSense:

✅ Conteúdo original e funcional (Editor de imagens)
✅ Sem conteúdo adulto, violência ou ilegal
✅ Sem cliques incentivados
✅ Sem conteúdo duplicado
✅ Processamento 100% local (privacidade garantida)
✅ Arquivo ads.txt configurado
✅ Código do AdSense no lugar correto

### 5. **Próximos Passos**

Após a verificação ser aceita:

1. Você poderá adicionar blocos de anúncio no site
2. Recomendações de posicionamento:
   - Topo da página (acima do hero)
   - Lateral da barra de ferramentas
   - Rodapé do site
   - Entre as seções de FAQ

### 📝 Notas Importantes

- **Não clique em seus próprios anúncios** (violação de políticas)
- **Não incentive cliques** em anúncios
- **Mantenha o site atualizado** com conteúdo de qualidade
- **Monitore o tráfego** no Google Search Console

## Suporte

Se encontrar problemas:
1. Verifique se o domínio está apontando corretamente
2. Aguarde 24-48 horas para a verificação
3. Consulte a documentação oficial: https://support.google.com/adsense

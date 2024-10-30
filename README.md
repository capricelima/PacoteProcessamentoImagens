Um pacote simples para processamento de imagens em Python. Este pacote permite aplicar filtros básicos em imagens usando a biblioteca Pillow.

Você pode instalar o pacote usando o `pip`:
```bash
pip install meu_pacote


from meu_pacote.processamento import aplicar_filtro

# Aplique um filtro de desfoque em uma imagem
output_path = aplicar_filtro('caminho/para/sua/imagem.png', 'blur')
print(f'Imagem salva em: {output_path}')

# Aplique um filtro de nitidez em uma imagem
output_path = aplicar_filtro('caminho/para/sua/imagem.png', 'sharpen')
print(f'Imagem salva em: {output_path}')


### Como Personalizar

- **Título**: Substitua "Meu Pacote de Processamento de Imagens" pelo nome do seu pacote.
- **Instalação**: Certifique-se de que o comando de instalação esteja correto.
- **Exemplos**: Modifique os caminhos das imagens e o texto conforme necessário.
- **Filtros**: Adicione ou modifique os filtros conforme suas funcionalidades.
- **Contribuições e Licença**: Inclua informações adicionais sobre como contribuir e a licença que você está usando.

Sinta-se à vontade para ajustar o texto como preferir! Se precisar de mais alguma coisa, é só avisar.

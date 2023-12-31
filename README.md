# Docker Script de Instalação

Este repositório contém um script para facilitar a instalação do Docker em sistemas Linux baseados no Debian. O script automatiza o processo de instalação, configurando todos os requisitos necessários, incluindo Chave GPG, extensões, imagem teste (hello-world) e todas as funções necessárias para rodar containers.

## Instalação

Siga estas etapas para instalar o Docker em seu sistema:

1. **Clone este repositório:**
   ```
   git clone https://github.com/eliezershell/docker.git
   ```

2. **Execute o script de instalação:**
   ```
   cd docker; chmod +x instalador_docker.sh; ./instalador_docker.sh
   ```
   
## Notas Adicionais

- **Testado no Ubuntu 22.04:** Este script foi testado e aprovado no Ubuntu 22.04.
  
- **Suporte a Outras Distribuições:** Embora tenha sido testado no Ubuntu 22.04, este script também deve funcionar em outras distribuições baseadas no Debian.

- **Problemas e Suporte:** Se encontrar problemas durante o processo de instalação ou precisar de suporte, sinta-se à vontade para abrir uma [issue](https://github.com/eliezershell/docker/issues) neste repositório.

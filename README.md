Automação Google Ads - Extração e Upload de Relatórios
Este script automatiza o processo de extração de relatórios do Google Ads e upload para o Google Sheets, utilizando reconhecimento de imagens e automação de interface.

📋 Funcionalidades
  Extração automática de 3 tipos de relatórios do Google Ads:
  Relatório de Campanhas
  Relatório de Localizações Correspondentes (Matched Locations)
  Relatório de Termos de Pesquisa (Search Terms)
  Processamento automático:
  Renomeação de arquivos com data atual
  Upload automático para Google Sheets
  Substituição de arquivos existentes

🛠️ Dependências
    pip install opencv-python pyautogui numpy pygetwindow

📁 Estrutura de Arquivos
  projeto/
  ├── script.py
  └── img/

⚙️ Configuração
  * Imagens de Referência: Certifique-se de que todas as imagens na pasta img/ correspondem aos elementos da interface do Google Ads
  * Resolução: O script foi desenvolvido para uma resolução específica - ajuste as imagens se necessário
  * Google Sheets: Configure o acesso ao Google Sheets previamente
Como Usar
  Execute o script:
    * python script.py

O script irá automaticamente:
  * Fechar Chrome existente
  * Abrir novo Chrome
  * Navegar para Google Ads
  * Extrair os 3 relatórios
  * Fazer upload para Google Sheets
    
📊 Relatórios Gerados
  Relatório	Nome do Arquivo	Padrão de Busca
  Campanhas	base_google_ads_YYYYMM.csv	Campaign report*.csv
  Localizações	base_google_Matched_YYYYMM.csv	Matched locations report*.csv
  Termos de Pesquisa	base_google_Search_YYYYMM.csv	Search terms report*.csv

▶️ Como usar
  git clone https://github.com/seu-usuario/projeto-automacao-google-ads.git
  cd projeto-automacao-google-ads

👨‍💻 Autor Juan Mathias
🔗 LinkedIn | 💻 Desenvolvedor Python & Automação

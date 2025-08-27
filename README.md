# Modelagem de Sistema em PBL - Instituto de Tecnologia e Liderança

## 📋 Sobre o Projeto

Este projeto de pesquisa de iniciação científica foca na modelagem e desenvolvimento de um sistema inovador para Project-Based Learning (PBL) no contexto do Instituto de Tecnologia e Liderança (Inteli). O objetivo é criar uma solução tecnológica que otimize o processo de aprendizagem baseado em projetos, integrando metodologias pedagógicas avançadas com ferramentas digitais.

## 🎯 Objetivos

- **Desenvolver um sistema de modelagem** para acompanhamento e avaliação de projetos PBL
- **Implementar metodologias inovadoras** de aprendizagem baseada em projetos
- **Criar ferramentas digitais** que facilitem o processo de ensino-aprendizagem
- **Estabelecer métricas e indicadores** para avaliação de competências em PBL
- **Contribuir para a evolução** do modelo educacional do Inteli

## 👥 Equipe de Pesquisa

### **Afonso Brandão**
- **Instituição:** Instituto de Tecnologia e Liderança (Inteli)
- **Área de Atuação:** Tecnologia Educacional e Sistemas de Informação
- **Contribuição:** Desenvolvimento de sistemas e modelagem tecnológica

### **Raiane Brandão**
- **Instituição:** Instituto de Tecnologia e Liderança (Inteli)
- **Área de Atuação:** Metodologias Pedagógicas e PBL
- **Contribuição:** Design instrucional e metodologias de ensino

### **Vanessa Nunes**
- **Instituição:** Instituto de Tecnologia e Liderança (Inteli)
- **Área de Atuação:** Avaliação Educacional e Análise de Dados
- **Contribuição:** Métricas de avaliação e análise de resultados

## 🏛️ Sobre o Instituto de Tecnologia e Liderança (Inteli)

O Inteli é uma instituição de ensino superior inovadora que utiliza metodologias ativas de aprendizagem, com foco especial em Project-Based Learning (PBL). A instituição se destaca por:

- **Metodologia PBL Avançada:** Projetos reais com empresas parceiras
- **Formação em Tecnologia e Liderança:** Preparação para o mercado de trabalho
- **Inovação Pedagógica:** Uso de tecnologias educacionais de ponta
- **Parcerias Empresariais:** Conexão direta com o mercado de trabalho

## 📁 Estrutura do Projeto

```
-pesquisa_iniciacao_cientifica_gd_apb/
├── artigo/                          # Documentação acadêmica
│   ├── revisao_bibliometrica_gd_pbl.tex  # Template RBIE limpo
│   ├── references.bib              # Referências bibliográficas
│   ├── RBIEarticle.cls             # Classe LaTeX para RBIE
│   ├── newlogo.png                 # Logo do projeto
│   └── referencias/                # Documentos de referência
│       ├── kitchenham.pdf          # Protocolo Kitchenham
│       ├── modelo_inteli.pdf       # Documentação do modelo Inteli
│       └── outros_documentos.pdf   # Outras referências
└── README.md                       # Este arquivo
```

## 🔬 Metodologia de Pesquisa

### Abordagem
- **Revisão Sistemática:** Análise da literatura sobre PBL e sistemas educacionais
- **Desenvolvimento Iterativo:** Prototipagem e testes contínuos
- **Validação Empírica:** Testes com estudantes e professores do Inteli
- **Análise de Dados:** Métricas quantitativas e qualitativas

### Fases do Projeto
1. **Fase 1:** Revisão bibliográfica e definição de requisitos
2. **Fase 2:** Modelagem conceitual do sistema
3. **Fase 3:** Desenvolvimento de protótipos
4. **Fase 4:** Implementação e testes
5. **Fase 5:** Validação e documentação

## 📊 Áreas de Foco

### Tecnologia Educacional
- Sistemas de gestão de projetos PBL
- Ferramentas de colaboração digital
- Plataformas de avaliação contínua
- Analytics educacionais

### Metodologias Pedagógicas
- Design instrucional para PBL
- Estratégias de avaliação formativa
- Desenvolvimento de competências
- Feedback e autorregulação

### Análise de Dados
- Métricas de aprendizagem
- Indicadores de performance
- Análise de engajamento
- Relatórios de progresso

## 🛠️ Tecnologias Utilizadas

- **Desenvolvimento:** Python, JavaScript, React
- **Banco de Dados:** PostgreSQL, MongoDB
- **Análise de Dados:** Pandas, NumPy, Matplotlib
- **Documentação:** LaTeX, Markdown
- **Controle de Versão:** Git

## 📚 Produção Científica

### Artigos em Desenvolvimento
- Revisão sistemática sobre sistemas PBL
- Modelo de avaliação para projetos educacionais
- Framework de métricas para PBL

### Apresentações
- Seminários internos do Inteli
- Congressos de tecnologia educacional
- Workshops sobre PBL

## 🎓 Impacto Esperado

### Para o Inteli
- **Melhoria do modelo PBL:** Otimização dos processos educacionais
- **Ferramentas inovadoras:** Novas tecnologias para ensino
- **Métricas avançadas:** Melhor acompanhamento do progresso discente

### Para a Comunidade Acadêmica
- **Contribuições científicas:** Artigos e publicações
- **Metodologias replicáveis:** Framework para outras instituições
- **Conhecimento compartilhado:** Disseminação de boas práticas

## 📞 Contato

### Coordenação do Projeto
- **Email:** pesquisa.pbl@inteli.edu.br
- **Instituto:** Instituto de Tecnologia e Liderança
- **Localização:** São Paulo, Brasil

### Membros da Equipe
- **Afonso Brandão:** afonso.brandao@inteli.edu.br
- **Raiane Brandão:** raiane.brandao@inteli.edu.br  
- **Vanessa Nunes:** vanessa.nunes@inteli.edu.br

## 📄 Licença

Este projeto é desenvolvido no âmbito acadêmico do Instituto de Tecnologia e Liderança. Todos os direitos reservados.

## 🔧 Instalação e Uso do LaTeX

### Instalação do LaTeX

#### Ubuntu/Debian
```bash
# Atualizar repositórios
sudo apt update

# Instalar pacotes básicos do LaTeX
sudo apt install -y texlive-latex-base texlive-latex-recommended texlive-fonts-recommended

# Para instalação mais completa (opcional)
sudo apt install -y texlive-full
```

#### Verificar instalação
```bash
pdflatex --version
bibtex --version
```

### Compilação de Documentos

#### Compilar arquivo .tex simples
```bash
pdflatex documento.tex
```

#### Compilar com bibliografia (BibTeX)
Para documentos com referências bibliográficas, siga esta sequência:

```bash
# 1. Primeira compilação do LaTeX
pdflatex documento.tex

# 2. Compilar bibliografia
bibtex documento

# 3. Segunda compilação do LaTeX (para resolver referências)
pdflatex documento.tex

# 4. Terceira compilação do LaTeX (para finalizar numeração)
pdflatex documento.tex
```

#### Script de compilação automática
Crie um script `compile.sh` para automatizar:

```bash
#!/bin/bash
if [ $# -eq 0 ]; then
    echo "Uso: ./compile.sh nome_do_arquivo_sem_extensao"
    exit 1
fi

FILE=$1

echo "Compilando $FILE.tex..."
pdflatex $FILE.tex
bibtex $FILE
pdflatex $FILE.tex
pdflatex $FILE.tex

echo "Compilação concluída! Arquivo gerado: $FILE.pdf"
```

Para usar:
```bash
chmod +x compile.sh
./compile.sh revisao_bibliometrica_gd_pbl
```

#### Exemplo de compilação do artigo deste projeto
```bash
# Navegar para o diretório do artigo
cd artigo/

# Compilar o artigo com bibliografia
pdflatex revisao_bibliometrica_gd_pbl.tex
bibtex revisao_bibliometrica_gd_pbl
pdflatex revisao_bibliometrica_gd_pbl.tex
pdflatex revisao_bibliometrica_gd_pbl.tex
```

#### Limpeza de arquivos temporários
Após a compilação, você pode remover arquivos temporários:

```bash
# Remover arquivos auxiliares
rm -f *.aux *.log *.bbl *.blg *.toc *.out *.fdb_latexmk *.fls

# Ou criar um script clean.sh
echo "rm -f *.aux *.log *.bbl *.blg *.toc *.out *.fdb_latexmk *.fls" > clean.sh
chmod +x clean.sh
```

### Dicas importantes

- Use **UTF-8** como codificação para caracteres especiais
- Para projetos grandes, compile frequentemente para detectar erros
- Mantenha backup dos arquivos .bib
- Use editores como VS Code com extensão LaTeX Workshop para facilitar o desenvolvimento

## 🙏 Agradecimentos

- Instituto de Tecnologia e Liderança (Inteli)
- Professores orientadores
- Estudantes participantes dos testes
- Empresas parceiras que colaboram com projetos PBL

---

**Última atualização:** Dezembro 2024  
**Versão do projeto:** 1.0  
**Status:** Em desenvolvimento
# Aprendizagem Ativa de Engenharia de Software Experimental: Análise sobre Autoconfiança e Aprendizado

Repositório de artefatos do artigo que investiga a autoeficácia percebida de estudantes em uma disciplina de Engenharia de Software Experimental (ESE) ministrada com Aprendizagem Ativa. O estudo analisa se a vivência prática constrói a segurança necessária para que os discentes se sintam aptos a conduzir experimentos na vida profissional.

**Autores:** Caio César Sousa Bandeira, Ranya Duran Greco, Carlos Augusto Carneiro de Freitas Filho, Júlia Freitas Santos, Anna Beatriz Marques  
**Afiliação:** Universidade Federal do Ceará - Campus Russas (UFC)

---

## Conteúdo do Repositório

### Dados (`csv/`)

| Arquivo | Descrição |
|---------|-----------|
| `feedback-subjetivo.csv` | Respostas às 7 questões abertas do questionário de percepção (análise qualitativa) |
| `feedback-v2.csv` | Respostas completas ao questionário (24 fechadas + 7 abertas) |
| `notas.csv` | Notas dos trabalhos práticos TP1 e TP2 |

### Notebooks de Análise (`notebooks/`)

| Notebook | Descrição |
|----------|-----------|
| `boxplots_notas.ipynb` | Distribuição das notas dos TP1 e TP2 (Figura do artigo) |
| `boxplots.ipynb` | Níveis de conhecimento antes/depois em 7 tópicos (Figura do artigo) |
| `feature_importance_confianca.ipynb` | Análise de regressão (Random Forest) – importância das variáveis na confiança |
| `cronbach_alpha.ipynb` | Análise psicométrica – Alpha de Cronbach, correlações item-total, alpha se item deletado |

### Materiais Didáticos (`materials/`)

| Arquivo | Descrição |
|---------|-----------|
| `Descricao do trabalho pratico 1.pdf` | Especificação do TP1 – reanálise de experimento controlado |
| `Descricao do trabalho pratico 2.pdf` | Especificação do TP2 – planejamento e execução de estudo primário |
| `Criterios de avaliacao dos trabalhos praticos.pdf` | Critérios de avaliação dos TPs |
| `Guia de uso do JASP.pdf` | Guia para uso do JASP nas sessões de laboratório |
| `forms.pdf` | Questionário de percepção (estrutura/formulário) |

---

## Replicação das Análises

### Requisitos

- Python 3.8+
- Jupyter
- Pandas, NumPy, Matplotlib, Seaborn, Scipy

```bash
pip install pandas numpy matplotlib seaborn scipy jupyter
```

### Execução

1. Clone o repositório
2. Abra os notebooks em `notebooks/` na ordem desejada
3. Execute as células – os notebooks leem os dados de `csv/`

Os caminhos dos arquivos CSV nos notebooks assumem que a execução é feita a partir da raiz do repositório ou que os caminhos relativos estão corretos.

---

## Contexto da Disciplina

A disciplina de ESE (64h) foi ministrada com aulas dialogadas, estudos dirigidos, seminários e dois trabalhos práticos. O TP1 envolveu a reanálise de um experimento controlado publicado; o TP2, o planejamento, execução e análise de um estudo primário (experimento, estudo de caso ou survey). A metodologia detalhada está descrita em [Greco et al., SBES 2025](https://doi.org/10.5753/sbes.2025.11268).

---

## Citação

Se utilizar os dados ou materiais deste repositório, cite o artigo:

```bibtex
@inproceedings{ees-feedback,
  title={Aprendizagem ativa de Engenharia de Software Experimental: Uma análise sobre autoconfiança e aprendizado},
  author={Bandeira, Caio C{\'e}sar Sousa and Greco, Ranya Duran and Freitas Filho, Carlos Augusto Carneiro de and Santos, J{\'u}lia Freitas and Marques, Anna Beatriz},
  booktitle={[VI Simpósio Brasileiro de Educação em Computação]},
  year={[2026]},
  note={Artefatos disponíveis em: [URL/DOI do repositório]}
}
```

---

## Licença

Os dados e materiais são disponibilizados para fins acadêmicos e de pesquisa. Consulte os autores para outros usos.

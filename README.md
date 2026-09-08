# Atendimento Educacional Especializado: Concepções e Metodologias

Repositório dedicado à organização, catalogação e documentação de fontes e materiais de apoio sobre a **Política Nacional de Educação Especial Inclusiva (PNEEI)**, instituída pelo Decreto nº 12.686/2025 e regulamentada pelo Ministério da Educação (MEC/SECADI/DIPEPI).

---

## 📚 Coletânea Cadernos Pedagógicos (MEC)

A coleção [Cadernos Pedagógicos da PNEEI](https://www.gov.br/mec/pt-br/pneei/cadernos-pedagogicos) é composta por 14 volumes formativos voltados a docentes de AEE, gestores e equipes pedagógicas:

| Volume | Título | Temática Principal |
| :---: | :--- | :--- |
| **1** | *Política de Educação Especial Inclusiva: concepções, fundamentos e princípios* | Marcos normativos da PNEEI (Decreto nº 12.686/2025), Modelo Social da Deficiência e combate ao capacitismo. |
| **2** | *Atendimento Educacional Especializado (AEE): Concepções e Metodologias* | Papel articulador do professor do AEE, organização em turnos e tempo integral, barreiras à participação. |
| **3** | *Documentação do AEE na Escola Inclusiva: Estudo de Caso, PAEE e PEI* | Elaboração prática de instrumentos pedagógicos e avaliação sem dependência exclusiva de laudo clínico. |
| **4** | *Práticas pedagógicas inclusivas em salas de aula* | Planejamento pedagógico sob o Desenho Universal para a Aprendizagem (DUA) e diferenciação curricular. |
| **5** | *Educação Inclusiva e Tecnologia Assistiva* | Recursos e serviços de TA aplicados ao contexto escolar para autonomia e comunicação do estudante. |
| **6** | *Práticas Inclusivas e Estudantes Autistas* | Paradigma da neurodiversidade, rotinas pedagógicas e acessibilidade comunicacional para estudantes com TEA. |
| **7** | *Práticas Inclusivas e Estudantes com Altas Habilidades ou Superdotação* | Identificação pedagógica via estudo de caso, enriquecimento curricular e suplementação do AEE. |
| **8** | *Práticas Inclusivas e Estudantes com Deficiências Sensoriais* | Metodologias de ensino e acessibilidade para surdez/deficiência auditiva, cegueira/baixa visão e surdocegueira. |
| **9** | *Infâncias e Educação Especial Inclusiva* | Práticas pedagógicas na Educação Infantil, brincadeiras e acolhimento inclusivo nos primeiros anos. |
| **10** | *Práticas Inclusivas em Alfabetização e Letramento* | Processos de aquisição de leitura e escrita acessíveis e estratégias multimodais de letramento. |
| **11** | *Atendimento Educacional Especializado em Ambiente Hospitalar ou Domiciliar* | Continuidade da escolarização e atendimento pedagógico a estudantes em tratamento de saúde. |
| **12** | *Educação Inclusiva e Intersetorialidade* | Articulação entre Educação, Saúde, Assistência Social e redes de proteção aos direitos da pessoa com deficiência. |
| **13** | *Educação Inclusiva e Profissional de Apoio Escolar* | Atribuições, mediação e atuação integrada do profissional de apoio junto à equipe escolar. |
| **14** | *Gestão Escolar Inclusiva* | Papel da gestão democrática, planejamento institucional, acessibilidade arquitetônica e curricular. |

---

## 🌐 Fontes e Leituras Complementares

* [Portal MEC — Política Nacional de Educação Especial Inclusiva (PNEE-EI)](https://www.gov.br/mec/pt-br/pneei)
* [Jeduca — Entenda a nova política de educação especial e inclusiva](https://jeduca.org.br/noticia/entenda-a-nova-politica-de-educacao-especial-e-inclusiva-lancada-pelo-governo)
* [Toda Matéria — Educação Inclusiva: conceitos e objetivos](https://www.todamateria.com.br/educacao-inclusiva-entenda-o-que-e-e-seus-objetivos-com-exemplos/)
* [Caderno de Pesquisa no NotebookLM](https://notebooklm.google.com/notebook/ce96a3d1-ae83-4aed-9b2a-d16aa6dbfb41)

---

## 🛠️ Instruções de Armazenamento de Arquivos Grandes (Git LFS)

Caso os arquivos PDF dos cadernos excedam o limite padrão de arquivos individuais do GitHub:

```bash
# Instale e inicialize o Git LFS
git lfs install

# Rastreie os arquivos PDF
git lfs track "fontes/*.pdf"
git add .gitattributes

# Adicione os arquivos e envie para o repositório
git add .
git commit -m "docs: adiciona catalogo de cadernos pedagogicos e fontes"
git push origin main

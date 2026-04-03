# 📊 NPS Ranking — Automação de Performance (Varejo)

![Status](https://img.shields.io/badge/Vers%C3%A3o-Upgrade%202026-brightgreen)
![Foco](https://img.shields.io/badge/Ambiente-Sam's%20Club-blue)
![Mobile First](https://img.shields.io/badge/Interface-Mobile-orange)

Aplicação desenvolvida para transformar dados brutos de satisfação do cliente em um ranking visual e organizado, eliminando processos manuais e cálculos repetitivos.

## 📖 A História por trás do Código (Case Real)
No meu dia a dia no **Sam's Club**, recebo listas manuais com o número do associado e a nota da compra. Para identificar quem atendeu, cruzo os dados no sistema da empresa, que retorna o **ID numérico** do colaborador.

**O Desafio:** Como a gerência promove campanhas de incentivo com brindes para o Top 3, eu precisava atualizar o ranking constantemente. Fazer isso no papel ou em planilhas lentas consumia muito tempo.

**A Solução:** Desenvolvi este app focado em agilidade. Como já decorei a relação entre os IDs e os nomes da equipe, recebo o número no sistema e seleciono diretamente o nome do operador no aplicativo. O sistema:
1. Processa a pontuação automaticamente.
2. Organiza o ranking em tempo real (🥇, 🥈, 🥉).
3. Gera uma imagem de alta qualidade (PNG) pronta para eu enviar no grupo de WhatsApp do setor.

## 🚀 Funcionalidades (Versão Atualizada)
- **Cálculo Inteligente:** Foco em notas Promotoras (9 e 10) conforme regras de NPS.
- **Exportação de Imagem:** Uso da biblioteca `html2canvas` para transformar o ranking em foto.
- **Filtro Mensal:** Histórico automático que permite navegar pelos meses do ano.
- **Persistência de Dados:** Uso de `localStorage` para manter os dados salvos no navegador do celular.
- **Interface Dark Mode:** Otimizada para leitura rápida em ambientes de loja.

## 🛠️ Tecnologias Utilizadas
* **HTML5 / CSS3:** Estrutura e estilização responsiva.
* **JavaScript (ES6+):** Lógica de ordenação de arrays e manipulação de datas.
* **html2canvas:** Renderização de elementos DOM para imagem.
* **Google Fonts:** Tipografia `DM Sans`.

## 📱 Fluxo de Uso
1. **Identificar:** Consulto o ID do operador no sistema interno da empresa.
2. **Lançar:** Seleciono o nome correspondente no App e salvo a nota recebida.
3. **Compartilhar:** Gerar a imagem do ranking atualizado para a premiação do time.

---
**Desenvolvido por Eduarda Brito** *Estudante de Ciência da Computação | Transformando rotinas manuais em soluções digitais.* [GitHub](https://github.com/eduardabritox-lab)


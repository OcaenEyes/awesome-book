<div class="github-widget" data-repo="inoue0426/awesome-computational-biology"></div>
## Awesome Computational Biology [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

与计算生物学相关的数据库、软件和论文的知识集合.

&gt; 计算生物学涉及数据分析和理论方法的开发和应用，
&gt; 数学建模和计算模拟技术用于生物、生态、
 &gt; 行为和社会系统.  - [Wikipedia](https://en.wikipedia.org/wiki/Computational_biology)



## Databases
### scRNA
- [Gene Expression Omnibus](https://www.ncbi.nlm.nih.gov/geo/) - 公共功能基因组数据库.
- [Single Cell PORTAL](https://singlecell.broadinstitute.org/single_cell) - 单细胞 RNA 公共数据库.
- [Single Cell Expression Atlas](https://www.ebi.ac.uk/gxa/sc/home) - 单细胞 RNA 公共数据库.
### Compound
- [PubChem](https://pubchem.ncbi.nlm.nih.gov/) - 最大的化学数据库之一，例如化合物、基因和蛋白质.
- [ChEBI](https://www.ebi.ac.uk/chebi/) - 专注于小化合物的化学数据库.
- [ChEMBL](https://www.ebi.ac.uk/chembl/) - 具有类药物特性的生物活性分子数据库.
- [ChemSpider](http://www.chemspider.com/) - 化学结构数据库.
- [KEGG COMPOUND](https://www.genome.jp/kegg/compound/) - 小分子和生物聚合物的集合.
- [LIPID MAPS](https://www.lipidmaps.org/databases/lmsd/overview) - 脂质数据库.
### Pathway
- [PathwayCommons](https://www.pathwaycommons.org/) - 途径和相互作用数据库.
- [KEGG PATHWAY](https://www.genome.jp/kegg/pathway.html) - 收集绘制的路径图.
- [WikiPathways](https://wikipathways.org/) - 生物途径数据库.
### Mass Spectra
- [MassBank](http://www.massbank.jp/) - 用于质谱参考光谱的开源数据库和工具.
- [MoNA MassBank of North America](https://mona.fiehnlab.ucdavis.edu/) - 代谢物质谱、元数据和相关化合物的元数据库.
### Protein
- [THE HUMAN PROTEIN ATLAS](https://www.proteinatlas.org/) - 最大的人类蛋白质数据库之一包含细胞、组织和器官. 
- [PROTEIN DATA BANK](https://www.rcsb.org/) - 蛋白质、核酸和复杂组件的 3D 形状数据库.
- [UniProt](https://www.uniprot.org/) - 蛋白质功能信息的收集.
### Genome
- [Human Genome Resources at NCBI](https://www.ncbi.nlm.nih.gov/projects/genome/guide/human/index.shtml) - 图像、蛋白质组学、转录组学和系统生物学数据库.
- [GenBank](https://www.ncbi.nlm.nih.gov/genbank/) - NCBI 提供的基因序列数据库.
- [UCSC Genome Browser](https://genome.ucsc.edu/) - UCSC 提供的基因组吹风机.
- [cBioPortal](https://www.cbioportal.org/)  - 癌症基因组数据库. 这为很多患者提供了整体元视图.
### Disease
- [KEGG DRUG](https://www.genome.jp/kegg/drug/) - 已批准药物的综合药物信息资源.
- [DrugBank](https://www.drugbank.com/) - 由阿尔伯塔大学维护的药物和靶点数据库.
### Interaction
- 药物基因相互作用
  - [DGIdb](https://www.dgidb.org/) - 药物-基因相互作用和可药物基因组的数据库.
  - [Comparative Toxicogenomics Database](http://ctdbase.org/) - 化学-基因相互作用、化学-疾病关联、基因-疾病关联和化学-表型关联的数据库.
  - [SNAP](https://snap.stanford.edu/biodata/datasets/10002/10002-ChG-Miner.html#:~:text=Dataset%20information,or%20activation%20of%20the%20drug.) - 包含药物-基因相互作用的数据集. 
  - [Comparative Toxicogenomics Database](https://ctdbase.org/) - 药物-靶标相互作用的数据库.
  - [Therapeutics Data Commons](https://tdcommons.ai/) - 用于许多任务的数据库，例如药物靶标、药物反应、药物间相互作用.
- 药物（-细胞系）反应
  - [NCI60](https://dtp.cancer.gov/discovery_development/nci-60/) 一个专注于 60 种癌细胞系和多种药物的数据库.
  - [Genomics of Drug Sensitivity in Cancer (GDSC)](https://www.cancerrxgene.org/) - 药物敏感性数据库，包含 1000 个人类癌细胞系和 100 多种化合物.
  - [Cancer Cell Line Encyclopedia](https://sites.broadinstitute.org/ccle/)  - 癌细胞系数据库. 它有 1000 个细胞系.
- 化学蛋白质相互作用
  - [STITCH](http://stitch.embl.de/) - 化学蛋白质相互作用的数据库.
  - [BindingDB](https://www.bindingdb.org/rwd/bind/index.jsp) - 化合物和目标的数据库.

## Preprocess

- [Chemistry Development Kit](https://github.com/cdk/cdk) - 化学信息学和机器学习软件.
- [RDKit](https://github.com/rdkit/rdkit) - 化学信息学和机器学习软件.
- [Scanpy](https://scanpy.readthedocs.io/en/stable/) - Python 中的 scRNA 分析库.
- [Seurat](https://satijalab.org/seurat/) - R 中的 scRNA 分析库.

## Machine Learning Tasks and Models

### Drug Repurposing

- [DeepPurpose](https://github.com/kexinhuang12345/DeepPurpose) - 用于药物再利用的 DL 库等. 
- [DRKG](https://github.com/gnn4dr/DRKG) - 生物知识图谱库.

### Drug Target Interaction

- [NeoDTI](https://github.com/FangpingWan/NeoDTI) - 药物靶标相互作用库.

### Compound Protein Interaction

- [MCPINN](https://github.com/mhlee0903/multi_channels_PINN) - 使用复合蛋白质相互作用和机器学习进行药物发现的库.
- [TransformerCPI](https://github.com/lifanchen-simm/transformerCPI) - 使用 Transformer 预测复合蛋白质相互作用的库. 

<div class="github-widget" data-repo="danielecook/Awesome-Bioinformatics"></div>
## Awesome Bioinformatics [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Check URLs](https://github.com/danielecook/Awesome-Bioinformatics/actions/workflows/url-check.yml/badge.svg)](https://github.com/danielecook/Awesome-Bioinformatics/actions/workflows/url-check.yml) [![Generate TOC](https://github.com/danielecook/Awesome-Bioinformatics/actions/workflows/toc.yml/badge.svg)](https://github.com/danielecook/Awesome-Bioinformatics/actions/workflows/toc.yml)

 &gt; 生物信息学是一个跨学科领域，它开发用于理解生物数据的方法和软件工具.  — [Wikipedia](https://en.wikipedia.org/wiki/Bioinformatics)

精选的生物信息学软件、资源和库列表. 主要基于命令行，免费或开源. 请随时 [contribute](https://github.com/danielecook/Awesome-Bioinformatics/blob/master/CONTRIBUTING.md)!

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


<!-- END doctoc generated TOC please keep comment here to allow auto update -->

---

## Package suites

软件包套件收集特定语言或平台的软件包和安装工具. 我们有一些用于生物信息学的软件.

- **[Bioperl](https://github.com/bioperl/bioperl-live)** - 用于生物信息学、基因组学和生命科学的开源 Perl 工具的用户和开发者国际协会. [ [paper-2002](https://doi.org/10.1101%2Fgr.361602) | [web](https://bioperl.org) ]

- **[Bioconductor](https://github.com/Bioconductor)** - 大量用于分析和理解高通量基因组数据的工具，包括 1500 多个软件包. [ [paper-2004](https://link.springer.com/article/10.1186/gb-2004-5-10-r80) | [web](https://www.bioconductor.org) ]

- **[Biopython](https://github.com/biopython/biopython) ** - 免费提供的 Python 生物计算工具，包括说明书、包装和详尽的文档. 的一部分 [Open Bioinformatics Foundation](http://open-bio.org/) . 包含非常有用 [Entrez](https://biopython.org/DIST/docs/api/Bio.Entrez-module.html) 用于访问 NCBI 数据库的 API 包. [ [paper-2009](https://pubmed.ncbi.nlm.nih.gov/19304878) | [web](https://biopython.org) ]

- **[Bioconda](https://github.com/bioconda)** - 一个频道 [conda package manager](http://conda.pydata.org/docs/intro.html) 专注于生物信息学软件. 包括一个存储库，其中包含 3000 多个可随时安装（使用 `conda install`）的生物信息学包. [ [paper-2018](https://pubmed.ncbi.nlm.nih.gov/29967506) | [web](https://bioconda.github.io) ]

- **[BioJulia](https://github.com/BioJulia)** - Julia 编程语言的生物信息学和计算生物学基础设施. [ [web](https://biojulia.net) ]
- **[Rust-Bio](https://github.com/rust-bio/rust-bio)** - 对生物信息学有用的算法和数据结构的 Rust 实现. [ [paper-2016](http://bioinformatics.oxfordjournals.org/content/early/2015/10/06/bioinformatics.btv573.short?rss=1) ]
- **[SeqAn](https://github.com/seqan/seqan3)** - 用于序列分析的现代 C++ 库.
- **[(Poly)merase](https://github.com/TimothyStiles/poly)** - 用于工程生物的 Go 库和命令行实用程序.
- **[Biocaml](https://github.com/biocaml/biocaml)** - Biocaml 旨在成为生物信息学的高性能用户友好库.

## Data Tools

### Downloading
- **[GGD](https://github.com/gogetdata/ggd-cli) ** - 去获取数据； 用于获取基因组数据的命令行界面. [ [web](https://gogetdata.github.io) ]
- **[SRA-Explorer](https://github.com/ewels/sra-explorer)** - 轻松获取 SRA 下载链接和其他信息. [ [web](https://sra-explorer.info) ]

### Compressing
- **[Genozip](https://github.com/divonlan/genozip)** - 常见基因组文件格式（BAM、CRAM、FASTQ、VCF 等）的压缩器. [ [web](https://genozip.com/?utm_source=Awesome-Bioinformatics) | [paper-2021](https://www.researchgate.net/publication/349347156_Genozip_-_A_Universal_Extensible_Genomic_Data_Compressor) ]

## Data Processing

### Command Line Utilities

- **[Bioinformatics One Liners](https://github.com/stephenturner/oneliners)** - 有用的单行命令的 Git 仓库.
- **[BioNode](https://github.com/bionode/bionode)** - 模块化和通用生物信息学，Bionode 为生物信息学分析工作流程提供可管道化的 UNIX 命令行工具和 JavaScript API. [ [web](http://bionode.io) ]
- **[bioSyntax](https://github.com/bioSyntax/bioSyntax)** - vim/less/gedit/sublime 中计算生物学文件格式（SAM、VCF、GTF、FASTA、PDB 等）的语法突出显示. [ [paper-2018](https://pubmed.ncbi.nlm.nih.gov/30134911) | [web](http://www.bioSyntax.org) ]
- **[CSVKit](https://github.com/wireservice/csvkit)** - 用于处理 CSV/制表符分隔文件的实用程序. [ [web](https://csvkit.readthedocs.io/en/latest) ]
- **[csvtk](https://github.com/shenwei356/csvtk)** - 另一个跨平台、高效、实用且漂亮的 CSV/TSV 工具包. [ [web](https://bioinf.shenwei.me/csvtk) ]
- **[datamash](https://git.savannah.gnu.org/gitweb/?p=datamash.git)** - 数据转换和统计. [ [web](http://www.gnu.org/software/datamash) ]
- **[easy_qsub](https://github.com/shenwei356/easy_qsub) ** - 使用脚本模板轻松提交 PBS 作业. 支持多个输入文件.
- **GNU Parallel** - 在单个多核机器上并行运行作业的通用并行器. [Here](https://www.biostars.org/p/63816/) 是一些使用 GNU Parallel 的示例脚本. [ [web](http://www.gnu.org/software/parallel) ]
- **[grabix](https://github.com/arq5x/grabix)** - 一个用于随机访问 BGZF 文件的小工具.
- **[gsort](https://github.com/brentp/gsort)** - 根据指定顺序对基因组文件进行排序.
- **[tabix](https://github.com/samtools/tabix)** - 表文件索引. [ [paper-2011](https://pubmed.ncbi.nlm.nih.gov/21208982) ]
- **[wormtable](https://github.com/wormtable/wormtable)** - 大型数据集的一次写入多次读取表.
- **[zindex](https://github.com/mattgodbolt/zindex)** - 在压缩文本文件上创建索引.

## Next Generation Sequencing

### Workflow Managers

- **[BigDataScript](https://github.com/pcingola/BigDataScript)** - 一种跨系统脚本语言，用于处理不同规模和功能的计算机系统中的大数据管道. [ [paper-2014](https://pubmed.ncbi.nlm.nih.gov/25189778) | [web](https://pcingola.github.io/BigDataScript) ]
- **[Bpipe](https://github.com/ssadedin/bpipe)** - 一种用于定义流水线阶段并将它们链接在一起以制作流水线的小型语言. [ [web](http://docs.bpipe.org) ]
- **[Common Workflow Language](https://github.com/common-workflow-language/common-workflow-language)** - 一种描述分析工作流程和工具的规范，这些工作流程和工具可移植并可扩展到各种软件和硬件环境，从工作站到集群、云和高性能计算 (HPC) 环境. [ [web](http://www.commonwl.org) ]
- **[Cromwell](https://github.com/broadinstitute/cromwell)** - 面向科学工作流程的工作流程管理系统. [ [web](https://cromwell.readthedocs.io) ]
- **[Galaxy](https://github.com/galaxyproject) ** - 一个流行的开源、基于网络的平台，用于数据密集型生物医学研究. 具有多种功能，从数据分析到工作流管理再到可视化工具. [ [paper-2018](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6030816) | [web](https://galaxyproject.org) ]
- **[Nextflow](https://github.com/nextflow-io/nextflow) （推荐）** - 围绕 UNIX 管道概念建模的流畅 DSL，以可移植的方式简化了并行和可扩展管道的编写. [ [paper-2018](https://pubmed.ncbi.nlm.nih.gov/29412134) | [web](http://nextflow.io) ]
- **[redun](https://github.com/insitro/redun)** - 基于 python 的工作流管理器.
- **[Ruffus](https://github.com/cgat-developers/ruffus)** - 广泛用于科学和生物信息学的 python 计算管道库. [ [paper-2010](https://pubmed.ncbi.nlm.nih.gov/20847218) | [web](http://www.ruffus.org.uk) ]
- **[SciPipe](https://github.com/scipipe/scipipe)** - 嵌入在 Go 编程语言中的工作流库，专注于支持复杂的工作流构造，编译为单个二进制文件，为每个输出提供强大的文件命名和全面的审计报告 [ [paper-2019](https://pubmed.ncbi.nlm.nih.gov/31029061/) | [web](https://scipipe.org/) ]
- **[SeqWare](https://github.com/SeqWare/seqware)** - 基于 Hadoop Oozie 的工作流系统，专注于云环境中的基因组学数据分析. [ [paper-2010](https://pubmed.ncbi.nlm.nih.gov/21210981) | [web](https://seqware.github.io) ]
- **[Snakemake](https://bitbucket.org/snakemake)** - Python 中的工作流管理系统，旨在通过提供快速舒适的执行环境来降低创建工作流的复杂性. [ [paper-2018](https://pubmed.ncbi.nlm.nih.gov/29788404) | [web](https://snakemake.readthedocs.io) ]
- **[Workflow Descriptor Language](https://github.com/broadinstitute/wdl)** - 由 Broad 开发的工作流程标准. [ [web](https://software.broadinstitute.org/wdl) ]

### Pipelines

- **[Awesome-Pipeline](https://github.com/pditommaso/awesome-pipeline)** - 管道资源列表.
- **[Bactopia](https://github.com/bactopia/bactopia/)** - 使用 Nextflow 构建的灵活管道，用于细菌基因组的完整分析. [ [web](https://bactopia.github.io/) ]
- **[Bacannot](https://github.com/fmalmeida/bacannot)** - 一个通用但全面的细菌注释管道，使用 Nextflow 构建，具有用于调查结果的漂亮图形选项. [ [web](https://bacannot.readthedocs.io/en/latest/?badge=latest) ]
- **[bcbio-nextgen](https://github.com/chapmanb/bcbio-nextgen)** - 电池包括用于变体和 RNA-Seq 分析、结构变体调用、注释和预测的基因组分析管道. [ [web](https://bcbio-nextgen.readthedocs.io) ]
- **[R-Peridot](https://github.com/pentalpha/r-peridot)** - 使用直观的 GUI 进行差异表达分析的可定制管道. [ [web](http://www.bioinformatics-brazil.org/r-peridot) ]
- **[ngs-preprocess](https://github.com/fmalmeida/ngs-preprocess)** - 用于预处理短序列和长序列读取的管道，使用 Nextflow 构建. [ [web](https://ngs-preprocess.readthedocs.io/en/latest/?badge=latest) ]

### Sequence Processing

序列处理包括诸如多路分解原始读取数据和修剪低质量碱基等任务.

- **[AfterQC](https://github.com/OpenGene/AfterQC)** - fastq 数据的自动过滤、修剪、错误删除和质量控制. [ [paper-2017](https://pubmed.ncbi.nlm.nih.gov/28361673) ]
- **[FastQC](https://github.com/s-andrews/FastQC)** - 用于高通量序列数据的质量控制工具. [ [web](http://www.bioinformatics.babraham.ac.uk/projects/fastqc) ]
- **[Fastqp](https://github.com/mdshw5/fastqp)** - 使用 Python 的 FASTQ 和 SAM 质量控制.
- **[Fastx Tookit](https://github.com/agordon/fastx_toolkit)** - FASTQ/A short-reads 预处理工具：解复用、修剪、裁剪、质量过滤和屏蔽实用程序. [ [web](http://hannonlab.cshl.edu/fastx_toolkit) ]
- **[MultiQC](https://github.com/ewels/MultiQC)** - 将多个样本的生物信息学分析结果汇总到一份报告中. [ [paper-2016](https://pubmed.ncbi.nlm.nih.gov/27312411) | [web](http://multiqc.info) ]
- **[SeqFu](https://github.com/telatin/seqfu2)** - 用 Nim 编写的用于 FASTA/FASTQ 文件的序列操作工具包. [ [paper-2021](https://www.mdpi.com/2306-5354/8/5/59) | [web](https://telatin.github.io/seqfu2/) ]
- **[SeqKit](https://github.com/shenwei356/seqkit)** - 在 Golang 中用于 FASTA/Q 文件操作的跨平台和超快工具包. [ [paper-2016](https://pubmed.ncbi.nlm.nih.gov/27706213) | [web](https://bioinf.shenwei.me/seqkit) ]
- **[seqmagick](https://github.com/fhcrc/seqmagick)** - 在 Biopython 中以一种方便的方式进行文件格式转换. [ [web](http://seqmagick.readthedocs.io) ]
- **[Seqtk](https://github.com/lh3/seqtk)** - 用于处理 FASTA/Q 格式序列的工具包.
- **[smof](https://github.com/incertae-sedis/smof)** - UNIX 风格的 FASTA 操作工具.

### Data Analysis

以下项目允许通过引入专门的数据库进行可扩展的基因组分析.

- **[Hail](https://github.com/hail-is/hail)** - 可扩展的基因组分析.
- **[GLNexus](https://github.com/dnanexus-rnd/GLnexus)** - 用于群体测序项目的可扩展 gVCF 合并和联合变体调用. [ [paper-2018](https://www.biorxiv.org/content/10.1101/343970v1.abstract) ]

### Sequence Alignment

#### Pairwise

- **[Bowtie 2](https://github.com/BenLangmead/bowtie2)** - 一种超快且内存高效的工具，用于将测序读取与长参考序列对齐. [ [paper-2012](https://pubmed.ncbi.nlm.nih.gov/22388286) | [web](http://bowtie-bio.sourceforge.net/bowtie2) ]
- **[BWA](https://github.com/lh3/bwa)** - 用于 DNA 序列之间成对比对的 Burrow-Wheeler Aligner.
- **[WFA](https://github.com/smarco/WFA)** - 波前比对算法 (WFA)，它利用序列相似性来加速比对 [ [paper-2020](https://academic.oup.com/bioinformatics/advance-article/doi/10.1093/bioinformatics/btaa777/5904262) ]
- **[Parasail](https://github.com/jeffdaily/parasail)** - 用于全局、半全局和局部成对序列比对的 SIMD C 库 [ [paper-2016](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-016-0930-z) ]
- **[MUMmer](https://github.com/mummer4/mummer)** - 一个用于快速比对整个基因组的系统，无论是完整的还是草稿形式. [ [paper-1999](http://mummer.sourceforge.net/MUMmer.pdf) | [paper-2002](http://mummer.sourceforge.net/MUMmer2.pdf) | [paper-2004](http://mummer.sourceforge.net/MUMmer3.pdf) | [web](http://mummer.sourceforge.net) ]
- **[DIAMOND](https://github.com/bbuchfink/diamond)** - 一种超快蛋白质对齐器，用于类似搜索的“blastp”和“blastx”. [ [paper-2021](https://www.nature.com/articles/s41592-021-01101-x) ]

#### Multiple Sequence Alignment

- **[POA](https://github.com/ljdursi/poapy)** - 用于多个同源序列的快速比对和共识的部分顺序比对. [ [paper-2002](https://academic.oup.com/bioinformatics/article/18/3/452/236691) ]

#### Clustering

- **[MMseqs2](https://github.com/soedinglab/MMseqs2)** - 用于蛋白质和核苷酸序列集的超快速、灵敏的搜索和聚类套件. [ [paper-2017](https://www.nature.com/articles/nbt.3988) | [paper-2018](https://www.nature.com/articles/s41467-018-04964-5) ]

### Quantification

- **[Cufflinks](https://github.com/cole-trapnell-lab/cufflinks)** - Cufflinks 组装转录本，估计它们的丰度，并测试 RNA-Seq 样本中的差异表达和调节. [ [paper-2010](https://www.nature.com/articles/nbt.1621) ]
- **[RSEM](https://github.com/deweylab/RSEM)** - 用于从 RNA-Seq 数据估计基因和亚型表达水平的软件包. [ [paper-2011](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-12-323) | [web](http://deweylab.github.io/RSEM/) ]

### Variant Calling

- **[DeepVariant](https://github.com/google/deepvariant)** - 基于深度学习的变体调用者 [ [paper-2018](https://rdcu.be/7Dhl) ]
- **[freebayes](https://github.com/ekg/freebayes)** - 基于贝叶斯单倍型的多态性发现和基因分型. [ [web](http://arxiv.org/abs/1207.3907) ]
- **[GATK](https://github.com/broadgsa/gatk)** - 高通量测序数据中的变体发现. [ [web](https://software.broadinstitute.org/gatk) ]
- **[Octopus](https://github.com/luntergroup/octopus)** - 具有广泛适用性的多态贝叶斯基因分型模型. [ [paper-2021](https://www.nature.com/articles/s41587-021-00861-3) ]
- **[bcftools](https://github.com/samtools/bcftools)** - samtools/bcftools 是一套用于操作 NGS 数据的工具，可用于调用变体. [ [paper-2009](https://pubmed.ncbi.nlm.nih.gov/19505943) | [web](http://htslib.org) ]
#### Structural variant callers

- **[Delly](https://github.com/dellytools/delly)** - 通过集成的配对末端和拆分读取分析发现结构变异. [ [paper-2012](https://pubmed.ncbi.nlm.nih.gov/22962449) ]
- **[lumpy](https://github.com/arq5x/lumpy-sv)** - lumpy：结构变异发现的通用概率框架. [ [paper-2014](https://link.springer.com/article/10.1186/gb-2014-15-6-r84) ]
- **[manta](https://github.com/Illumina/manta)** - 映射测序数据的结构变体和插入缺失调用者. [ [paper-2015](https://pubmed.ncbi.nlm.nih.gov/26647377) ]
- **[gridss](https://github.com/PapenfussLab/gridss)** - GRIDSS：基因组重排识别软件套件. [ [paper-2017](https://pubmed.ncbi.nlm.nih.gov/29097403) ]
- **[smoove](https://github.com/brentp/smoove)** - 使用现有工具进行结构变异检出和基因分型，但很顺利.

### BAM File Utilities

- **[Bamtools](https://github.com/pezmaster31/bamtools)** - 用于处理 BAM 文件的工具集合. [ [paper-2011](https://academic.oup.com/bioinformatics/article/27/12/1691/255399) ]
- **[bam toolbox](https://github.com/AndersenLab/bam-toolbox) ** MtDNA：核覆盖；  BAM 工具箱可以输出 MtDNA 的比率：核覆盖率，代表线粒体含量.
- **[mergesam](https://github.com/DarwinAwardWinner/mergesam)** - 自动执行常见的 SAM 和 BAM 转换.
- **[mosdepth](https://github.com/brentp/mosdepth)** - 用于 WGS、外显子组或靶向测序的快速 BAM/CRAM 深度计算. [ [paper-2017](https://pubmed.ncbi.nlm.nih.gov/29096012/) ]
- **[SAMstat](https://github.com/TimoLassmann/samstat)** - 显示下一代测序的序列统计信息. [ [paper-2010](https://academic.oup.com/bioinformatics/article/27/1/130/201972) | [web](http://samstat.sourceforge.net) ]
- **[Somalier](https://github.com/brentp/somalier)** - 对 BAM/CRAM/VCF/GVCF 进行快速样本交换和相关性检查. [ [paper-2020](https://pubmed.ncbi.nlm.nih.gov/32664994) ]
- **[Telseq](https://github.com/zd1/telseq)** - Telseq 是一种从全基因组序列数据中估算端粒长度的工具. [ [paper-2014](https://academic.oup.com/nar/article/42/9/e75/1249448) ]

### VCF File Utilities

- **[bcftools](https://github.com/samtools/bcftools)** - 用于操作 VCF 文件的工具集. [ [paper-2016](https://pubmed.ncbi.nlm.nih.gov/26826718) | [paper-2017](https://pubmed.ncbi.nlm.nih.gov/28205675) | [web](http://samtools.github.io/bcftools) ]
- **[vcfanno](https://github.com/brentp/vcfanno)** - 使用其他 VCF/BED/tabixed 文件注释 VCF. [ [paper-2016](https://pubmed.ncbi.nlm.nih.gov/27250555) ]
- **[vcflib](https://github.com/vcflib/vcflib)** - 用于解析和操作 VCF 文件的 C++ 库.
- **[vcftools](https://github.com/vcftools/vcftools)** - VCF 操作和统计（例如连锁不平衡、等位基因频率、Fst）. [ [paper-2011](https://pubmed.ncbi.nlm.nih.gov/21653522) ]

### GFF BED File Utilities

- **[AGAT](https://github.com/NBISweden/AGAT)** - 处理任何 GTF/GFF 格式的基因注释的工具套件. [ [web](https://agat.readthedocs.io/en/latest/?badge=latest) ]
- **[gffutils](https://github.com/daler/gffutils)** - GFF 和 GTF 文件操作和相互转换. [ [web](http://daler.github.io/gffutils) ]
- **[BEDOPS](https://bedops.readthedocs.io/en/latest/index.html)** - 快速、高度可扩展且易于并行化的基因组分析工具包. [ [paper-2012](https://academic.oup.com/bioinformatics/article/28/14/1919/218826) ]
- **[Bedtools2](https://github.com/arq5x/bedtools2)** - A Swiss Army knife for genome arithmetic. [ [paper-2010](https://pubmed.ncbi.nlm.nih.gov/20110278) | [paper-2014](https://pubmed.ncbi.nlm.nih.gov/25199790) | [web](https://bedtools.readthedocs.io) ]

### Variant Simulation

- **[Bam Surgeon](https://github.com/adamewing/bamsurgeon)** - 用于向现有 .bam 文件添加突变的工具，用于测试突变调用者. [ [web](https://popmodels.cancercontrol.cancer.gov/gsr/packages/bamsurgeon) ]
- **[wgsim](https://github.com/lh3/wgsim)** - **带有 samtools！** - 读取模拟器. [ [web](https://popmodels.cancercontrol.cancer.gov/gsr/packages/wgsim) ]

### Variant Prediction/Annotation

- **[SIFT](https://github.com/teamdfir/sift)** - 预测氨基酸取代是否影响蛋白质功能. [ [paper-2003](https://pubmed.ncbi.nlm.nih.gov/12824425) | [web](http://sift.jcvi.org) ]
- **[SnpEff](https://github.com/pcingola/SnpEff)** - 遗传变异注释和效应预测工具箱. [ [paper-2012](https://www.tandfonline.com/doi/full/10.4161/fly.19695) | [web](https://pcingola.github.io/SnpEff) ]
- **[Ensembl VEP](https://anaconda.org/bioconda/ensembl-vep)** - VEP 确定您的变异（SNP、插入、缺失、CNV 或结构变异）对基因、转录本和蛋白质序列以及调控区域的影响. [ [paper-2016](https://doi.org/10.1186/s13059-016-0974-4) | [web](http://www.ensembl.org/info/docs/tools/vep/index.html) ]


### Python Modules

#### Data

- **[cruzdb](https://github.com/brentp/cruzdb)** - Pythonic 访问 UCSC 基因组数据库. [ [paper-2013](https://academic.oup.com/bioinformatics/article/29/23/3003/248468) ]
- **[pyensembl](https://github.com/openvax/pyensembl)** - Pythonic 访问 Ensembl 数据库. [ [web](https://pyensembl.readthedocs.io/en/latest/pyensembl.html) ]
- **[bioservices](https://github.com/cokelaer/bioservices)** - 从 Python 访问生物 Web 服务. [ [paper-2013](https://academic.oup.com/bioinformatics/article/29/24/3241/194040) | [web](http://bioservices.readthedocs.io) ]

#### Tools

- **[cyvcf](https://github.com/arq5x/cyvcf)** - 一个端口 [pyVCF](https://github.com/jamescasbon/PyVCF) 使用 Cython 提高速度.
- **[cyvcf2](https://github.com/brentp/cyvcf2) ** - Cython + HTSlib == 快速 VCF 解析； 甚至比 pyVCF 更快的解析. [ [paper-2017](https://pubmed.ncbi.nlm.nih.gov/28165109) | [web](https://brentp.github.io/cyvcf2) ]
- **[pyBedTools](https://github.com/daler/pybedtools)** - Python 包装器 [bedtools](https://github.com/arq5x/bedtools). [ [paper-2011](https://pubmed.ncbi.nlm.nih.gov/21949271) | [web](http://daler.github.io/pybedtools) ]
- **[pyfaidx](https://github.com/mdshw5/pyfaidx)** - Pythonic 访问 FASTA 文件.
- **[pysam](https://github.com/pysam-developers/pysam)** - Python 包装器 [samtools](https://github.com/samtools/samtools). [ [web](https://pysam.readthedocs.io/en/latest/api.html) ]
- **[pyVCF](https://github.com/jamescasbon/PyVCF)** - Python 的 VCF 解析器. [ [web](http://pyvcf.readthedocs.org/en/latest/index.html) ]

### Assembly
- **[SPAdes](https://github.com/ablab/spades)** - SPAdes（圣彼得堡基因组组装器）是一个组装工具包，包含各种组装管道和原核基因组组装的事实标准.
- **[SKESA](https://github.com/ncbi/SKESA) ** - SKESA 是一种用于微生物基因组的从头序列读取组装器. 它使用保守的启发式方法，旨在在基因组的重复区域创建中断. 这导致出色的序列质量，而不会显着损害连续性.

### Annotation
- **[Prokka](https://github.com/tseemann/prokka) ** - Prokka：快速原核基因组注释.  Prokka 是微生物基因组注释中引用最多的注释命令行工具之一.
- **[Bakta](https://github.com/oschwengers/bakta)** - Bakta is a tool for the rapid & standardized annotation of bacterial genomes & plasmids. It provides dbxref-rich and sORF-including annotations in machine-readable JSON & bioinformatics standard file formats for automatic downstream analysis.

## Long-read sequencing

### Long-read Assembly

- **[canu](https://github.com/marbl/canu)** - 用于大基因组和小基因组的单分子序列组装器.
- **[flye](https://github.com/fenderglass/Flye)** - 使用重复图进行单分子测序读取的从头组装器. 
- **[hifiasm](https://github.com/chhylp123/hifiasm)** - 用于准确 Hifi 读取的单倍型解析汇编器.
- **[wtdbg2](https://github.com/ruanjue/wtdbg2)** - 一种用于长噪声读取组装的模糊 Bruijn 图方法

## Visualization

### Genome Browsers / Gene Diagrams

以下工具可用于可视化基因组数据或构建定制的基因组数据可视化，包括来自 DNA-Seq、RNA-Seq 和 ChIP-Seq、变体等的序列数据.

- **[Squiggle](https://github.com/Lab41/squiggle)** - 易于使用的 DNA 序列可视化工具，可将 FASTA 文件转换为基于浏览器的可视化. [ [paper-2018](https://pubmed.ncbi.nlm.nih.gov/30247632) | [web](https://squiggle.readthedocs.io/en/latest/) ]
- **[biodalliance](https://github.com/dasmoth/dalliance) ** - 可嵌入的基因组查看器. 集成来自各种来源的数据，并可以直接从流行的基因组学文件格式（包括 bigWig、BAM 和 VCF）加载数据.
  [ [paper-2011](https://pubmed.ncbi.nlm.nih.gov/21252075) | [web](http://www.biodalliance.org) ]
- **[BioJS](https://github.com/biojs/biojs)** - BioJS 是一个包含一百多个 JavaScript 组件的库，使您能够使用当前的 Web 技术可视化和处理数据. [ [paper-2014](https://pubmed.ncbi.nlm.nih.gov/25075290/) | [web](http://biojs.net/) ]
- **[Circleator](https://github.com/jonathancrabtree/Circleator)** - 使用 BioPerl 和 SVG 对基因组相关数据进行灵活的循环可视化. [ [paper-2014](https://pubmed.ncbi.nlm.nih.gov/25075113) ]
- **[DNAism](https://github.com/drio/dnaism)** - 基于地平线图 D3 的 DNA 数据 JavaScript 库. [ [paper-2016](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-016-0891-2) | [web](http://drio.github.io/dnaism/) ]
- **[IGV js](https://github.com/igvteam/igv) ** - 基于 Java 的浏览器. 用于基因组数据和注释的快速、高效、可扩展的可视化工具. 处理多种格式. [ [paper-2019](https://pubmed.ncbi.nlm.nih.gov/31099383) | [web](https://software.broadinstitute.org/software/igv) ]
- **[Island Plot](https://github.com/lairdm/islandplot) ** - 基于 D3 JavaScript 的基因组查看器. 构建 SVG. [ [paper-2015](https://pubmed.ncbi.nlm.nih.gov/25916842/) ]
- **[JBrowse](https://github.com/GMOD/jbrowse)** - JavaScript 基因组浏览器，可通过插件和轨道定制进行高度定制. [ [paper-2016](https://pubmed.ncbi.nlm.nih.gov/27072794) | [web](http://jbrowse.org/) ]
- **[PHAT](https://github.com/chgibb/PHAT)** - 用于分析和可视化下一代测序数据集的点击式跨平台套件. [ [paper-2018](https://pubmed.ncbi.nlm.nih.gov/30561651) | [web](https://chgibb.github.io/PHATDocs) ]
- **[pileup.js](https://github.com/hammerlab/pileup.js)** - JavaScript 库，可用于生成交互式和高度可定制的基于 Web 的基因组浏览器. [ [paper-2016](https://pubmed.ncbi.nlm.nih.gov/27153605) ]
- **[scribl](https://github.com/chmille4/Scribl)** - JavaScript library for drawing canvas-based gene diagrams. [ [paper-2012](https://pubmed.ncbi.nlm.nih.gov/23172864) | [web](http://chmille4.github.io/Scribl) ]
- **Lucid Align** - 现代序列比对查看器. [ [web](https://lucidalign.com) ]

### Circos Related

- **[Circos](https://github.com/vigsterkr/circos)** - 圆形图的 Perl 包，非常适合基因组重排. [ [paper-2009](https://pubmed.ncbi.nlm.nih.gov/19541911) | [web](http://circos.ca) ]
- **ClicO FS** - Circos 的基于 Web 的交互式服务. [ [paper-2015](https://pubmed.ncbi.nlm.nih.gov/26227146) ]
- **OmicCircos** - 组学数据圆形图的 R 包. [ [paper-2014](https://pubmed.ncbi.nlm.nih.gov/24526832) | [web](http://www.bioconductor.org/packages/release/bioc/html/OmicCircos.html) ]
- **J-Circos** - 用于与 circos 图进行交互工作的 Java 应用程序. [ [paper-2014](https://pubmed.ncbi.nlm.nih.gov/25540184) | [web](http://www.australianprostatecentre.org/research/software/jcircos) ]
- **[rCircos](https://bitbucket.org/henryhzhang/rcircos/src/master/)** - 用于圆形图的 R 包. [ [paper-2013](https://pubmed.ncbi.nlm.nih.gov/23937229) | [web](http://watson.nci.nih.gov/cran_mirror/web/packages/RCircos/index.html) ]
- **[fujiplot](https://github.com/mkanai/fujiplot)** - 多个 GWAS 结果的 circos 表示. [ [paper-2018](https://www.nature.com/articles/s41588-018-0047-6) ]

## Database Access

- [Entrez Direct: E-utilities on the UNIX command line](http://www.ncbi.nlm.nih.gov/books/NBK179288/)  - 以编程方式访问 NCBI 数据库的 UNIX 命令行工具. 安装说明和示例可在链接中找到.

## Resources

### Becoming a Bioinformatician

- [What is a bioinformatician](http://blog.fejes.ca/?p=2418)
- [Bioinformatics Curriculum Guidelines: Toward a Definition of Core Competencies](http://www.ploscompbiol.org/article/info:doi%2F10.1371%2Fjournal.pcbi.1003496)
- [Top N Reasons To Do A Ph.D. or Post-Doc in Bioinformatics/Computational Biology](http://caseybergman.wordpress.com/2012/07/31/top-n-reasons-to-do-a-ph-d-or-post-doc-in-bioinformaticscomputational-biology/)
- [A 10-Step Guide to Party Conversation For Bioinformaticians](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2013-14-1-104) - 以下是有关如何在被问及以下问题时向未参与该领域的人传达概念的分步指南：“那么，你是做什么的？”
- [A History Of Bioinformatics (In The Year 2039)](https://www.youtube.com/watch?v=uwsjwMO-TEA) - C. Titus Brown 关于他回顾 2039 年生物信息学的演讲.可以找到他对这次演讲的笔记 [here](http://ivory.idyll.org/blog/2014-bosc-keynote.html).
- [A farewell to bioinformatics](https://madhadron.com/science/farewell_to_bioinformatics.html) - 对生物信息学现状的批判性看法.
- [A Series of Interviews with Notable Bioinformaticians](http://www.acgt.me/blog/2014/3/25/101-questions-a-new-series-of-interviews-with-notable-bioinformaticians) - Keith Bradnam 博士“认为向一群著名的生物信息学家提出一系列简单的问题，以评估他们对生物信息学研究现状的感受，并可能获得他们对他们有用的任何提示生物信息学职业.”
- [Open Source Society University on Bioinformatics](https://github.com/ossu/bioinformatics) - 对于那些想在自己的时间免费完成生物信息学课程的人来说，这是一条坚实的道路，课程来自世界上最好的大学.
- [Rosalind](http://rosalind.info/) - Rosalind 是一个通过解决问题来学习生物信息学的平台.
- [A guide for the lonely bioinformatician](http://www.opiniomics.org/a-guide-for-the-lonely-bioinformatician/) - 本指南面向生物信息学家，旨在引导他们实现更好的职业发展.
- [A brief history of bioinformatics](https://doi.org/10.1093/bib/bby063)

### Bioinformatics on GitHub

- [Awesome-alternative-splicing](https://github.com/HussainAther/awesome-alternative-splicing) - 可变剪接资源列表，包括软件、数据库和其他工具.
- [Awesome AI-based Protein Design](https://github.com/opendilab/awesome-AI-based-protein-design) - 基于人工智能的蛋白质设计研究论文集.

### Sequencing

- [Next-Generation Sequencing Technologies - Elaine Mardis (2014)](https://youtu.be/6Is3W7JkFp8) [1:34:35] - 对下一代和第三代测序技术的出色（技术）概述，以及在癌症研究中的一些应用.
- [Annotated bibliography of \*Seq assays](https://liorpachter.wordpress.com/seq/) - 约 100 篇关于从转录到转座因子发现的各种测序技术和分析的论文列表.
- [For all you seq... (PDF)](http://www.illumina.com/content/dam/illumina-marketing/documents/applications/ngs-library-prep/ForAllYouSeqMethods.pdf)  (3456x5471) - Illumina 的大量信息图，说明有多少种测序技术有效. 技术涵盖蛋白质-蛋白质相互作用、RNA 转录、RNA-蛋白质相互作用、RNA 低水平检测、RNA 修饰、RNA 结构、DNA 重排和标记、DNA 低水平检测、表观遗传学和 DNA-蛋白质相互作用. 包括参考资料.

### RNA-Seq

- [Review papers on RNA-seq (Biostars)](https://www.biostars.org/p/52152/) - 包括许多关于 RNA-seq 和分析方法的开创性论文.
- [Informatics for RNA-seq: A web resource for analysis on the cloud](https://github.com/griffithlab/rnaseq_tutorial)  - 关于使用 Amazon AWS 云服务在云中执行 RNA-seq 分析的教育资源. 主题包括准备数据、预处理、差异表达、异构体发现、数据可视化和解释.
- [RNA-seqlopedia](http://rnaseq.uoregon.edu/) - RNA-seqlopedia 对 RNA-seq 以及进行成功的 RNA-seq 实验所需的选择进行了精彩的概述.
- [A survey of best practices for RNA-seq data analysis](http://genomebiology.biomedcentral.com/articles/10.1186/s13059-016-0881-8) - 为 RNA-seq 计算分析提供了出色的路线图，包括挑战/障碍和需要注意的事项，以及如何将 RNA-seq 数据与其他数据类型集成.
- [Stories from the Supplement](https://www.youtube.com/watch?v=5NiFibnbE8o) [46:39] - Lior Pachter 博士分享了他在著名 RNA-seq 分析软件 CuffDiff 和 [Cufflinks](http://cole-trapnell-lab.github.io/cufflinks/) 并解释了他们的一些方法.
- [List of RNA-seq Bioinformatics Tools](https://en.wikipedia.org/wiki/List_of_RNA-Seq_bioinformatics_tools) - 维基百科上的分析所需的 RNA-seq 生物信息学工具的广泛列表，范围从质量控制、对齐、拼接分析和可视化的分析管道的所有部分.
- [RNA-seq Analysis](https://github.com/crazyhottommy/RNA-seq-analysis) - [@crazyhottommy](https://github.com/crazyhottommy)进行 RNA-seq 分析时关于各种步骤和注意事项的注释.

### ChIP-Seq

- [ChIP-seq analysis notes from Tommy Tang](https://github.com/crazyhottommy/ChIP-seq-analysis) - ChIP-seq 数据资源，包括论文、方法、软件链接和分析.

### YouTube Channels and Playlists

- [Current Topics in Genome Analysis 2016](https://www.genome.gov/12514288/current-topics-in-genome-analysis-2016-course-syllabus-handouts-and-videos/) - 在 NIH 举办的 14 场精彩系列讲座，内容涉及基因组学的当前主题，从序列分析到测序技术，甚至更多的转化主题，如基因组医学.
- [GenomeTV](https://www.youtube.com/user/GenomeTV) - “GenomeTV 是 NHGRI 的官方视频资源集，从讲座到新闻纪录片，再到处理基因组研究的研究、问题和临床应用的会议的完整视频集.”
- [Leading Strand](https://www.youtube.com/user/LeadingStrand)  - 冷泉港实验室 (CSHL) 会议的主题演讲. 更多关于 [The Leading Strand](http://theleadingstrand.cshl.edu/).
- [Genomics, Big Data and Medicine Seminar Series](https://www.youtube.com/playlist?list=PLqLDR0CTP9_pboZCk6gR9Zn4kW7h9XWJI) - “我们的研讨会致力于 GBM 的关键交叉点，深入研究将深刻塑造未来的‘前沿’技术和方法.”
- [Rafael Irizarry's Channel](https://www.youtube.com/user/RafalabChannel/videos) - Rafael Irizarry 博士关于基因组学统计的讲座和学术讲座.
- [NIH VideoCasting and Podcasting](https://www.youtube.com/user/nihvcast)  - “NIH VideoCast 以实时流媒体视频的形式通过 Internet 向全球观众直播研讨会、大会和会议.” 不仅仅是基因组学和生物信息学视频，还有许多关于生物信息学和基因组学领域特定用途的精彩演讲.

### Blogs

- [ACGT](http://www.acgt.me/) - 基思·布拉德南 (Keith Bradnam) 博士写道：“关于生物学、基因组学的思考，以及生物信息学首字母缩略词的滥用对人类的持续威胁.”
- [Opiniomics](http://www.opiniomics.org/) - Mick Watson 博士撰写有关生物信息学、基因组和生物学的文章.
- [Bits of DNA](https://liorpachter.wordpress.com/) - Lior Pachter 博士撰写有关计算生物学的评论和评论.
- [it is NOT junk](http://www.michaeleisen.org/blog/) - Michael Eisen 博士撰写了“关于基因组、DNA、进化、开放科学、棒球和其他重要事物的博客”
- [#!/perl/bioinfo](https://bioinfoperl.blogspot.com) - EEAD-CSIC 的计算和结构生物学小组用西班牙语和英语撰写关于植物基因组学、计算和结构生物学问题的想法和代码.

### Miscellaneous

- [The Leek group guide to genomics papers](https://github.com/jtleek/genomicspapers/) - 专业策划的基因组学论文，以加快基因组学、RNA-seq、统计（用于基因组学）、软件开发等方面的速度.
- [A New Online Computational Biology Curriculum](https://doi.org/10.1371/journal.pcbi.1003662) - “本文介绍了数百个免费视频课程的目录，这些课程可能对那些希望扩展其生物信息学和计算生物学知识的人感兴趣.这些课程以大学院系为蓝本分为 11 个学科领域，并附有评论和职业建议. “
- [How Perl Saved the Human Genome Project](http://www.foo.be/docs/tpj/issues/vol1_2/tpj0102-0001.html) - Lincoln D. Stein 关于 Perl 编程语言在人类基因组计划中的重要性的轶事.
- [Educational Papers from Nature Biotechnology and PLoS Computational Biology](https://liacs.leidenuniv.nl/~hoogeboomhj/mcb/nature_primer.html) - 关于计算生物学和生物信息学中使用的各种方法的引物和简短教育文章的链接页面.
- [The PeerJ Bioinformatics Software Tools Collection](https://peerj.com/collections/45-bioinformatics-software/) - 由 Keith Crandall 和 Claus White 策划的工具集，旨在整理 PeerJ 中最有趣、创新和相关的生物信息学工具文章.

## Online networking groups

- [Bioinformatics (on Discord)](https://discord.com/invite/3uxbPns) - 用于通用生物信息学的 Discord 服务器
- [r-bioinformatics](https://www.reddit.com/r/bioinformatics/comments/7ndwm1/rbioinformatics_slack_channel_and_an_open_call/) - r/bioinformatics 的官方 Slack 工作区 ([send a direct message to apfejes on reddit](https://www.reddit.com/message/compose/?to=apfejes&subject=Request%20to%20join%20the%20r/bioinformatics%20Slack%20group&message=I%20would%20like%20to%20request%20to%20join%20the%20r/bioinformatics%20Slack%20group))
- [BioinformaticsGRX](https://bioinformaticsgrx.es/) - 位于西班牙格拉纳达的生物信息学家社区
- [Comunidad de Desarolladores de Software en Bioinformática](https://comunidadbioinfo.github.io/) - 一个以拉丁美洲为中心的生物信息学家社区
- [COMBINE](https://combine.org.au/) - 奥地利生物信息学学生小组

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

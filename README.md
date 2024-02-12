# Deep learning based model for regulatory epigenome
I am doing my master thesis about learning DNA sequence activity like accessibility. There's a lot of research out there on this topic. Inspired by a great collection of research papers at inspired by [papers-for-molecular-design-using-DL](https://github.com/AspirinCode/papers-for-molecular-design-using-DL/blob/main/README.md?plain=1) and [Machine-learning-for-proteins](https://github.com/yangkky/Machine-learning-for-proteins/tree/master), I decided to create my own collection. My aim is to understand these papers better and share what I learn, hope this can help people who interested in this field.

**Updating ...** 

## Menu
[Reviews](#reviews)  
[Predicting chromatin accessibility from sequence](#predicting-chromatin-accessibility-from-sequence)  
[Predicting gene expression from sequence](#predicting-gene-expression-from-sequence)  
[Predicting TF binding from sequence](#predicting-tf-binding-from-sequence)  
[Genomic Foundation Models](#genomic-foundation-models)  
[DL-based enhancer design](#dl-based-enhancer-design)  
[Datasets](#datasets)

## Reviews
**Chromatin accessibility and the regulatory epigenome.**  
Sandy L. Klemm, Zohar Shipony, William J. Greenleaf.  
*Nature Reviews Genetics, January 2019.*  
[[10.1038/s41576-018-0089-8](https://doi.org/10.1038/s41576-018-0089-8)]

## Predicting chromatin accessibility from sequence  
**Basset: learning the regulatory code of the accessible genome with deep convolutional neural networks.**  
David R. Kelley, Jasper Snoek, and John L. Rinn.  
*Genome Research, May 2016.*  
[[10.1101/gr.200535.115](http://www.genome.org/cgi/doi/10.1101/gr.200535.115)][[github code](https://github.com/davek44/Basset)]

**Integrating regulatory DNA sequence and gene expression to predict genome-wide chromatin accessibility across cellular contexts.**  
Surag Nair, Daniel S Kim, Jacob Perricone, Anshul Kundaje.  
*Bioinformatics, July 2019.*  
[[10.1093/bioinformatics/btz352](https://doi.org/10.1093/bioinformatics/btz352)][[github code](https://github.com/kundajelab/ChromDragoNN)]

**scBasset: sequence-based modeling of single-cell ATAC-seq using convolutional neural networks.**  
Han Yuan, David R. Kelley.  
*Nature Methods, August 2022.*  
[[10.1038/s41592-022-01562-8](https://doi.org/10.1038/s41592-022-01562-8)][[github code](https://github.com/calico/scBasset)]

**Bias factorized, base-resolution deep learning models of chromatin accessibility reveal cis-regulatory sequence syntax, transcription factor footprints and regulatory variants.**  
Anusri Pampari, Anna Shcherbina, Anshul Kundaje.  
*Manuscript in preparation.*  
[[github code](https://github.com/kundajelab/chrombpnet)]

**EpiGePT: a Pretrained Transformer model for epigenomics.**  
Zijing Gao, Qiao Liu, Wanwen Zeng, Rui Jiang, Wing Hung Wong.  
*bioRxiv, February 2024.*  
[[10.1101/2023.07.15.549134](https://doi.org/10.1101/2023.07.15.549134)][[github code](https://github.com/ZjGaothu/EpiGePT)][[online web](https://health.tsinghua.edu.cn/epigept/)]

## Predicting gene expression from sequence  
**Sequential regulatory activity prediction across chromosomes with convolutional neural networks.**  
David R. Kelley, Yakir A. Reshef, Maxwell Bileschi, David Belanger, Cory Y. McLean and Jasper Snoek.  
*Genome Research, March 2018.*   
[[10.1101/gr.227819.117](http://www.genome.org/cgi/doi/10.1101/gr.227819.117)][[github code](https://github.com/calico/basenji)]  

**Effective gene expression prediction from sequence by integrating long-range interactions.**  
Žiga Avsec, Vikram Agarwal, Daniel Visentin, Joseph R. Ledsam, Agnieszka Grabska-Barwinska, Kyle R. Taylor, Yannis Assael, John Jumper, Pushmeet Kohli & David R. Kelley.  
*Nature Methods, October 2021.*  
[[10.1038/s41592-021-01252-x](https://doi.org/10.1038/s41592-021-01252-x)][[github code](https://github.com/google-deepmind/deepmind-research/tree/master/enformer)]  

## Predicting TF binding from sequence  
**Base-resolution models of transcription-factor binding reveal soft motif syntax.**  
Žiga Avsec, Melanie Weilert, Avanti Shrikumar, Sabrina Krueger, Amr Alexandari, Khyati Dalal, Robin Fropf, Charles McAnany, Julien Gagneur, Anshul Kundaje, Julia Zeitlinger.  
*Nature Genetics, February 2021.*  
[[10.1038/s41588-021-00782-6](https://doi.org/10.1038/s41588-021-00782-6)][[github code](https://github.com/kundajelab/bpnet/)]

## Genomic Foundation Models
**DNABERT: pre-trained Bidirectional Encoder Representations from Transformers model for DNA-language in genome.**  
Yanrong Ji, Zhihan Zhou, Han Liu, Ramana V Davuluri.  
*Bioinformatics, August 2021.*  
[[10.1093/bioinformatics/btab083](https://doi.org/10.1093/bioinformatics/btab083)][[github code](https://github.com/jerryji1993/DNABERT)][[hugging face](https://huggingface.co/zhihan1996)]

**DNABERT-2: Efficient Foundation Model and Benchmark For Multi-Species Genome.**  
Zhihan Zhou, Yanrong Ji, Weijian Li, Pratik Dutta, Ramana Davuluri, Han Liu.  
*arXiv, June 2023.*  
[[10.48550/arXiv.2306.15006](https://doi.org/10.48550/arXiv.2306.15006)][[github code](https://github.com/Zhihan1996/DNABERT_2)][[hugging face](https://huggingface.co/zhihan1996/DNABERT-2-117M)]

**The Nucleotide Transformer: Building and Evaluating Robust Foundation Models for Human Genomics.**  
Hugo Dalla-Torre, Liam Gonzalez, Javier Mendoza-Revilla, Nicolas Lopez Carranza, Adam Henryk Grzywaczewski, Francesco Oteri, Christian Dallago, Evan Trop, Bernardo P. de Almeida, Hassan Sirelkhatim, Guillaume Richard, Marcin Skwark, Karim Beguir, Marie Lopez, Thomas Pierrot.   
*bioRxiv, September 2023.*  
[[10.1101/2023.01.11.523679](https://doi.org/10.1101/2023.01.11.523679)][[github code](https://github.com/instadeepai/nucleotide-transformer)][[hugging face](https://huggingface.co/collections/InstaDeepAI/nucleotide-transformer-65099cdde13ff96230f2e592)]  

**HyenaDNA: Long-Range Genomic Sequence Modeling at Single Nucleotide Resolution.**
Eric Nguyen, Michael Poli, Marjan Faizi, Armin Thomas, Callum Birch-Sykes, Michael Wornow, Aman Patel, Clayton Rabideau, Stefano Massaroli, Yoshua Bengio, Stefano Ermon, Stephen A. Baccus, Chris Ré.  
*arXiv, June 2023.*  
[[10.48550/arXiv.2306.15794](https://doi.org/10.48550/arXiv.2306.15794)][[github code](https://github.com/HazyResearch/hyena-dna)][[hugging face](https://huggingface.co/papers/2306.15794)]

## DL-based enhancer design
**Cell-type-directed design of synthetic enhancers.**  
Ibrahim I. Taskiran, Katina I. Spanier, Hannah Dickmänken, Niklas Kempynck, Alexandra Pančíková, Eren Can Ekşi, Gert Hulselmans, Joy N. Ismail, Koen Theunis, Roel Vandepoel, Valerie Christiaens, David Mauduit & Stein Aerts.  
*Nature, December 2023.*  
[[10.1038/s41586-023-06936-2](https://doi.org/10.1038/s41586-023-06936-2)]

**DNA-Diffusion: Leveraging Generative Models for Controlling Chromatin Accessibility and Gene Expression via Synthetic Regulatory Elements.**  
Lucas Ferreira DaSilva, Simon Senan, Zain Munir Patel, Aniketh Janardhan Reddy, Sameer Gabbita, Zach Nussbaum, César Miguel Valdez Córdova, Aaron Wenteler, Noah Weber, Tin M. Tunjic, Talha Ahmad Khan, Zelun Li, Cameron Smith, Matei Bejan, Lithin Karmel Louis, Paola Cornejo, Will Connell, Emily S. Wong, Wouter Meuleman,  Luca Pinello.  
*bioRxiv, February 2024.*  
[[10.1101/2024.02.01.578352](https://doi.org/10.1101/2024.02.01.578352)][[github code](https://github.com/pinellolab/DNA-Diffusion)]

## Datasets
**DNaseI Hypersensitivity sites (DNase-seq)**  
```bash
# ENCODE
wget -r ftp://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeAwgDnaseUniform

# Roadmap
wget -r -A "*DNase.hotspot.fdr0.01.peaks.bed.gz" http://egg2.wustl.edu/roadmap/data/byFileType/peaks/consolidated/narrowPeak
```

**DNase-seq + ChIp-seq + CAGE**
```bash
wget https://storage.googleapis.com/131k/sample_wigs.txt
wget https://storage.googleapis.com/131k/l131k_w128.bed
wget https://storage.googleapis.com/131k/l131k_w128.h5
```

**sc-ATAC seq**  
[Buenrostro_2018](https://github.com/pinellolab/scATAC-benchmarking/tree/master/Real_Data/Buenrostro_2018/input)  




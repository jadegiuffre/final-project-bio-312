# final-project-bio-312
ncbi-acc-download -F genbank XP_001624893.1
   72  n
   73  ncbi-acc-download -F genbank XP_001624893.1
   74  ncbi-acc-download -h
   75  ls
   76  cd labs/lab2
   77  ncbi-acc-download -F genbank NW_001834114.1
   78  ls
   79  less NW_001834114.1.gbk
   80  ncbi-acc-download -F fasta NW_00183114.1
   81  ncbi-acc-download -F fasta NW_001834114.1
   82  ncbi-acc-download -F gff3 NW_001834114.1
   83  grep LOC5503943 NW_001834114.1.gff > LOC5503943.gff
   84  grep -v X2 LOC5513668.gff > LOC5513668.notX2.gff
   85  gt gff3 -sort  -tidy -force -o LOC5503943.sorted.gff LOC5503943.X1.gff
   86  grep -v X2 LOC5503943.gff > LOC5503943.notX2.gff
   87  grep -v X3 LOC5503943.gff > LOC5503943.notX2.gff
   88  gt gff3 -sort  -tidy -force -o LOC5513668.sorted.gff LOC5513668.X1.gff
   89  gt stat LOC5503943.sorted.counts.gff
   90  gt stat LOC5503943.sorted.gff
   91  ls -lrt
   92  gt stat exonlengthdistri LOC5503943.gff
   93  gt stat LOC5503943.gff
   94  ls -lrt
   95  ncbi-acc-download -F gff3 NW_001834114.1
   96  ls -lrt
   97  grep -v X2 LOC5503943.gff > LOC5503943.notX2.gff
   98  grep -v X3 LOC5503943.notX2.gff > LOC5503943.X1.gff
   99  ls -lrt
  100  gt gff3 -sort  -tidy -force -o LOC5513668.sorted.gff LOC5513668.X1.gff
  101  gt stat LOC5503943.sorted.gff
  102  gt stat LOC5503943.sorted.counts.gff
  103  gt stat -genelengthdistri -exonlengthdistri -intronlengthdistri -cdslengthdistri -addintrons -force  -o LOC5513668.sorted.counts.gff LOC5513668.sorted.gff
  104  ls -lrt
  105  ls
  106  cd labs/lab2
  107  ncbi-acc-download -h
  108  ls -l
  109  ncbi-acc-download -F genbank NW_001834348.1
  110  ls
  111  less NW_001834348.1.gbk
  112  ncbi-acc-download -F fasta NW_001834348.1
  113  ncbi-acc-download -F gff3 NW_001834348.1
  114  grep LOC5513668 NW_001834348.1.gff > LOC5513668.gff
  115  grep -v X2 LOC5513668.gff > LOC5513668.notX2.gff
  116  grep -v X3 LOC5513668.notX2.gff > LOC5513668.X1.gff
  117  gt gff3 -sort  -tidy -force -o LOC5513668.sorted.gff LOC5513668.X1.gff
  118  gt stat -genelengthdistri -exonlengthdistri -intronlengthdistri -cdslengthdistri -addintrons -force  -o LOC5513668.sorted.counts.gff LOC5513668.sorted.gff
  119  ls -lrt
  120  gt stat LOC5513668.sorted.counts.gff
  121  less LOC5513668.sorted.counts.gff
  122  ls
  123  cd labs/lab2
  124  ncbi-acc-download -h
  125  ls -l
  126  ncbi-acc-download -F genbank NW_001834114.1
  127  ls
  128  less NW_001834114.1.gbk
  129  ncbi-acc-download -F fasta NW_001834114.1
  130  grep LOC5503943  NW_001834114.1.gff > LOC5503943.gff
  131  grep -v X2 LOC5503943.gff > LOC5503943.notX2.gff
  132  grep -v X3 LOC5503943.notX2.gff > LOC5503943.X1.gff
  133  gt gff3 -sort  -tidy -force -o LOC5513668.sorted.gff LOC5513668.X1.gff
  134  gt stat -genelengthdistri -exonlengthdistri -intronlengthdistri -cdslengthdistri -addintrons -force  -o LOC5503943.sorted.counts.gff LOC5503943.sorted.gff
  135  ls
  136  cd labs/lab2
  137  ls -l
  138  less LOC5503943.sorted.gff
  139  less LOC5503943.X1.gff
  140  gt gff3 -sort  -tidy -force -o LOC5503943.sorted.gff LOC5503943.X1.gff
  141  less LOC5503943.sorted.gff
  142  gt stat -genelengthdistri -exonlengthdistri -intronlengthdistri -cdslengthdistri -addintrons -force -o LOC5503943.sorted.counts.gff LOC5503943.sorted.gff
  143  less LOC5503943.sorted.counts.gff
  144  pwd
  145  ls
  146  cd tools
  147  la
  148  ls
  149  cd /home/ec2-user/tools/samtools-1.10/examples
  150  man ls
  151  cd ..
  152  cd
  153  ncbi-genome-download -h
  154  ncbi-genome-download -F gff -T 45351 invertebrate
  155  ncbi-genome-download -F fasta -T 45351 invertebrate
  156  ls -ltr
  157  cd data/refseq/invertebrate/gcf
  158  pwd
  159  ls -lrt
  160  more refseq
  161  pwd
  162  ls -lrt
  163  pwd
  164  cd data 
  165  ls 
  166  cd /~data
  167  cd ~/data
  168  ncbi-genome-download -F gff -T 45351 invertebrate
  169  ncbi-genome-download -F fasta -T 45351 invertebrate
  170  pwd
  171  more
  172  ncbi-genome-download -F gff -T 45351 invertebrate
  173  ncbi-genome-download -F fasta -T 45351 invertebrate
  174  ls -lrt
  175  cd refseq
  176  ls
  177  cd invertebrate
  178  ls
  179  cd GCF_000209225.1
  180  ls
  181  ls GCF_000209225.1
  182  gunzip GCF_000209225.1_ASM20922v1_genomic.fna.gz
  183  gunzip GCF_000209225.1_ASM20922v1_genomic.gff.gz
  184  less GCF_000209225.1_ASM20922v1_genomic.fna.gz
  185  ls
  186  less -S GCF_000209225.1_ASM20922v1_genomic.gff
  187  pwd
  188  ls
  189  cd tools
  190  ls
  191  cd /home/ec2-user/tools/samtools-1.10/examples
  192  man ls
  193  ls
  194  cd ..
  195  cd
  196  ncbi-genome-download -h
  197  ncbi-genome-download -F gff -T 45351 invertebrate
  198  ncbi-genome-download -F fasta -T 45351 invertebrate
  199    gunzip GCF_000209225.1_ASM20922v1_genomic.fna.gz
  200  gunzip GCF_000209225.1_ASM20922v1_genomic.gff.gz
  201  bestidea=bio312iscool
  202  echo $bestidea
  203  geneid=LOC5513668
  204  echo $geneid
  205  grep -c $geneid GCF_000209225.1_ASM20922v1_genomic.gff
  206  less -S GCF_000209225.1_ASM20922v1_genomic.gff
  207  gunzip GCF_000209225.1_ASM20922v1_genomic.fna.gz
  208  ncbi-genome-download -F gff -T 45351 invertebrate
  209  ncbi-genome-download -F fasta -T 45351 invertebrate
  210  ls -lrt
  211  pwd refseq
  212  cd
  213  pwd reqseq
  214  pwd refseq
  215  ls -lrt
  216  cd refseq
  217  more refseq
  218  grep $geneid $gffFile > $geneid.gff
  219  nano WolfieExtractTrans.sh
  220  ls
  221  cd labs/lab3
  222  ncbi-acc-download -F genbank NW_001834114.1
  223  ls
  224  less NW_001834114.1
  225  less NW_001834114.1.gbk
  226  ncbi-acc-download -F fasta NW_001834114.1
  227  ncbi-acc-download -F gff3 NW_001834114.1
  228  grep LOC5503943 NW_001834114.1.gff > LOC5503943.gff
  229  grep -v X2 LOC5503943.gff LOC5503943.notX2.gff
  230  grep -v X2 LOC5503943.gff > LOC5503943.notX2.gff
  231  grep -v X3 LOC5503943.notX2.gff > LOC5503943.X1.gff
  232  gt gff3 -sort  -tidy -force -o LOC5503943.sorted.gff LOC5503943.X1.gff
  233  gt stat -genelengthdistri -exonlengthdistri -intronlengthdistri -cdslengthdistri -addintrons -force  -o LOC5503943.sorted.counts.gff LOC5503943.sorted.gff
  234  grep CDS LOC5503943.X1.gff > LOC5503943.X1.cds.gff
  235  bedtools getfasta -s -fi NW_001834114.1 -fo LOC5503943.X1.cds.fa -bed LOC5503943.X1.cds.gff
  236  less LOC5503943.X1.cds.fa
  237  git config --global user.name "your username" #who is making changes
  238  cd ~/labs
  239  git clone https://github.com/Bio312/lab4-jadegiuffre
  240  cd ~/labs
  241  git clone https://github.com/Bio312/lab4-jadegiuffre
  242  rmdir lab4
  243  mv lab4-jadegiuffre lab4
  244  cd lab4
  245  ncbi-acc-download -F fasta AF254382.1
  246  ncbi-acc-download -F gff3 AF254382.1
  247  ncbi-acc-download -F genbank AF254382.1
  248  ncbi-acc-download -F fasta NR_145820.1 
  249  ncbi-acc-download -F gff3 NR_145820.1
  250  ncbi-acc-download -F genbank NR_145820.1
  251  ls -lrt
  252  less AF254382.1.fa
  253  less NR_145820.1.gbk
  254  cat AF254382.1.fa  NR_145820.1.fa > 18s.fa
  255  git config --global user.name "jadegiuffre"
  256  git config --global user.email jade.giuffre@stonybrook.edu
  257  git config --global credential.helper store
  258  git config --global credential.helper cache
  259  git config --global core.editor nano
  260  less 18s.fa
  261  muscle -in 18s.fa -out 18s.aligned.fa
  262  alv -k 18s.aligned.fa | less -r
  263   t_coffee -other_pg seq_reformat -in 18s.aligned.fa -output sim
  264  cd ~
  265  ls
  266  cd data
  267  ncbi-genome-download -F gff -T 9606 vertebrate_mammalian
  268  ncbi-genome-download -F fasta -T 9606 vertebrate_mammalian
  269  gunzip GCF_000001405.39_GRCh38.p13_genomic.fna.gz
  270  gunzip GCF_000001405.39_GRCh38.p13_genomic.gff.gz
  271  cd refseq
  272  ls
  273  gunzip GCF_000001405.39_GRCh38.p13_genomic.fna.gz
  274  cd vertebrate_mammalian
  275  ls
  276  cd GCF_000001405.39
  277  gunzip GCF_000001405.39_GRCh38.p13_genomic.fna.gz
  278  gunzip GCF_000001405.39_GRCh38.p13_genomic.gff.gz
  279  cd ~labs/lab4
  280  cd ~
  281  labs
  282  labs/lab4
  283  cd labs/lab4
  284  ls
  285  nano WolfieExtractTrans.sh
  286  git commit -a -m "added a greeting to WolfieExtractTrans.sh"
  287  git status
  288  git log
  289  git restore WolfieExtractTrans.sh
  290  git status
  291  nano WolfieExtractTrans.sh
  292  git commit -a -m "replaced a line of code in WolfiExtract script with one Dr. Rest provided; excludes numeric isoforms X2-20 and alphabetic isoforms a-z"
  293  git status
  294  git log
  295  geneid=TJP1
  296  export geneid
  297  fastaFile=/home/ec2-user/data/refseq/vertebrate_mammalian/GCF_000001405.39/GCF_000001405.39_GRCh38.p13_genomic.fna
  298  export fastaFile
  299  gffFile=/home/ec2-user/data/refseq/vertebrate_mammalian/GCF_000001405.39/GCF_000001405.39_GRCh38.p13_genomic.gff
  300  export gffFile
  301  bash WolfieExtractTrans.sh
  302  nano wolfieextracttrans.sh
  303  nano WolfieExtractTrans.sh
  304  geneid=TJP1
  305  export geneid
  306  fastaFile=/home/ec2-user/data/refseq/vertebrate_mammalian/GCF_000001405.39/GCF_000001405.39_GRCh38.p13_genomic.fna
  307  export fastaFile
  308  gffFile=/home/ec2-user/data/refseq/vertebrate_mammalian/GCF_000001405.39/GCF_000001405.39_GRCh38.p13_genomic.gff
  309  export gffFile
  310  bash WolfieExtractTrans.sh
  311  cd ~
  312  cd data
  313  ls
  314  ncbi-genome-download -F gff -T 9606 vertebrate_mammalian
  315  ncbi-genome-download -F fasta -T 9606 vertebrate_mammalian
  316  gunzip GCF_000001405.39_GRCh38.p13_genomic.fna.gz
  317  ls
  318  cd refseq
  319  ls
  320  cd vertebrate_mammalian
  321  ls
  322  cd ~/data
  323  ls
  324  cd labs/lab4
  325  cd ~/labs
  326  cd ~/lab4
  327  cd lab4
  328  ls
  329  echo $fastaFile
  330  ls $fastaFile
  331  ls 
  332  ls $gfffile
  333  $gffFile
  334  ls $gffFile
  335  less WolfieExtractTrans.sh
  336  nano WolfieTransExtract.sh
  337  nano WolfieExtractTrans.sh 
  338  geneid=TJP1
  339  export geneid
  340  fastaFile=/home/ec2-user/data/refseq/vertebrate_mammalian/GCF_000001405.39/GCF_000001405.39_GRCh38.p13_genomic.fna
  341  export fastaFile
  342  gffFile=/home/ec2-user/data/refseq/vertebrate_mammalian/GCF_000001405.39/GCF_000001405.39_GRCh38.p13_genomic.gff
  343  export gffFile
  344  bash WolfieExtractTrans.sh
  345  less TJP1.sorted.counts.txt.
  346  ls
  347  less TJP1.sorted.counts
  348  less TJP1.sorted.counts.txt
  349  sed -i "1 s/^.*$/>Hs_TJP1/" TJP1.X1.cds.union.fa
  350  sed -i "1 s/^.*$/>Nv_LOC5513668/" LOC5513668.X1.cds.union.fa 
  351  cat LOC5513668.X1.cds.union.fa TJP1.X1.cds.union.fa > NucRec.cds.fa
  352  muscle -in NucRec.cds.fa -out NucRec.cds.aligned.fa  
  353  alv -k NucRec.cds.aligned.fa | less -r
  354  t_coffee -other_pg seq_reformat -in NucRec.cds.aligned.fa -output sim
  355  bash WolfieCountGaps.sh
  356  faTrans NucRec.cds.aligned.fa  NucRec.cds.aligned.trans.fa
  357  alv -k NucRec.cds.aligned.trans.fa | less -r
  358  t_coffee -other_pg seq_reformat -in NucRec.cds.aligned.trans.fa -output sim
  359  bash WolfieCountGaps.sh
  360  t_coffee -other_pg seq_reformat -in NucRec.cds.aligned.fa -output sim
  361  t_coffee -other_pg seq_reformat -in NucRec.cds.trX.nt_ali.fasta -output sim  
  362   translatorx -i NucRec.cds.fa -o NucRec.cds.trX -p M
  363  alv -k NucRec.cds.trX.nt_ali.fasta | less -r
  364   elinks NucRec.cds.trX.aa_based_codon_coloured.html
  365  alv -k NucRec.cds.trX.aa_ali.fasta | less -r
  366  t_coffee -other_pg seq_reformat -in NucRec.cds.trX.nt_ali.fasta -output sim  
  367   bash WolfieCountGaps.sh
  368  bash WolfieCountGaps.sh 
  369  t_coffee -other_pg seq_reformat -in NucRec.cds.trX.aa_ali.fasta -output sim
  370  bash WolfieCountGaps.sh
  371  history > lab4.commandhistory.txt
  372  git add
  373  git commit -a -m "Adding all new data files I generated to the repository."
  374  git status
  375  git push
  376  git status
  377  ls
  378  git add .
  379  git commit -a -m "comment" 
  380  git pull
  381  git push
  382  cd ~/labs/lab5
  383  git clone https://github.com/Bio312/lab5-jadegiuffre
  384  mkdir ~/data/blast
  385  pwd
  386  ls
  387  cd lab5-jadegiuffre
  388  gunzip proteomes/*.gz
  389  cat  proteomes/* > ~/data/blast/allprotein.fas
  390  makeblastdb -in ~/data/blast/allprotein.fas -parse_seqids -dbtype prot
  391  ncbi-acc-download -F fasta -m protein XP_032239066.1
  392  blastp -db ~/data/blast/allprotein.fas -query XP_032239066.1.fa -outfmt 0 -max_hsps 1 > XP_032239066.blastp.typical.out
  393  less XP_032239066.blastp.typical.out 
  394  blastp -db ~/data/blast/allprotein.fas -query XP_032239066.1.fa -outfmt "6 sseqid pident length mismatch gapopen evalue bitscore pident stitle"  -max_hsps 1 -out XP_032239066.blastp.detail.out
  395  grep -c Homo XP_032239066.blastp.detail.out
  396  blastp -db ~/data/blast/allprotein.fas -query XP_032239066.1.fa -outfmt 0 -max_hsps 1 > XP_032239066.blastp.typical.out
  397  less XP_032239066.blastp.typical.out
  398  awk '{if ($6<0.00000000000001)print $1 }' XP_032239066.blastp.detail.out > XP_032239066.blastp.detail.filtered.out
  399  wc -l XP_032239066.blastp.detail.filtered.out
  400  seqkit grep --pattern-file XP_032239066.blastp.detail.filtered.out ~/data/blast/allprotein.fas > XP_032239066.blastp.detail.filtered.fas
  401  muscle -in XP_032239066.blastp.detail.filtered.fas -out XP_032239066.blastp.detail.filtered.aligned.fas
  402   t_coffee -other_pg seq_reformat -in XP_032239066.blastp.detail.filtered.aligned.fas -output sim
  403  alv -k XP_032239066.blastp.detail.filtered.aligned.fas | less -r 
  404  t_coffee -other_pg seq_reformat -in XP_032239066.blastp.detail.filtered.aligned.fas -action +rm_gap 50 -out allhomologs.aligned.r50.fa
  405  alv -kli --majority allhomologs.aligned.r50.fa | less -RS
  406  ncbi-acc-download -F fasta -m protein XP_001624893.1
  407   blastp -db ~/data/blast/allprotein.fas -query XP_001624893.1.fa -outfmt 0 -max_hsps 1 > XP_001624893.1.blastp.typical.out
  408  less XP_001624893.1.blastp.typical.out
  409  blastp -db ~/data/blast/allprotein.fas -query XP_001624893.1.fa -outfmt "6 sseqid pident length mismatch gapopen evalue bitscore pident stitle"  -max_hsps 1 -out XP_001624893.1.blastp.detail.out
  410  less XP_001624893.1.blastp.detail.out
  411  less XP_001624893.1.blastp.typical.out
  412  awk '{if ($6<0.00000000000001)print $1 }' XP_001624893.1.blastp.detail.out > XP_001624893.1.blastp.detail.filtered.out
  413  wc -l XP_001624893.1.detailed.filtered.out
  414  wc -l XP_001624893.blastp.detail.filtered.out
  415  awk '{if ($6<0.00000000000001)print $1 }' XP_001624893.blastp.detail.out > XP_001624893.blastp.detail.filtered.out
  416  less XP_001624893.blastp.filtered.out
  417  XP_001624893.blastp.detailed.out
  418  less XP_001624893.blastp.detailed.out
  419  blastp -db ~/data/blast/allprotein.fas -query XP_032239066.1.fa -outfmt "6 sseqid pident length mismatch gapopen evalue bitscore pident stitle"  -max_hsps 1 -out XP_001624893.blastp.detail.out
  420  less XP_001624893.blastp.detail.out
  421  awk '{if ($6<0.00000000000001)print $1 }' XP_001624893.blastp.detail.out > XP_001624893.blastp.detail.filtered.out
  422  wc -l XP_001624893.blastp.detail.filtered.out 
  423  seqkit grep --pattern-file XP_001624893.blastp.detail.filtered.out ~/data/blast/allprotein.fas > XP_001624893.blastp.detail.filtered.fas
  424  muscle -in XP_001624893.blastp.detail.filtered.fas -out XP_001624893.blastp.detail.filtered.aligned.fas
  425  t_coffee -other_pg seq_reformat -in XP_001624893.blastp.detail.filtered.aligned.fas -output sim
  426  history > lab5.commandhistory.txt
  427  git add
  428  git add .
  429  git commit -a -m "Adding all new data files I generated in AWS to the repository."
  430  git pull --no-edit
  431  git push
  432  git clone https://github.com/Bio312/lab6-jadegiuffre
  433  awk '{if ($3>=50 &&  $6<0.0000000001)print $1 }' ~/labs/lab5/XP_001630613.blastp.detail.out > ~/labs/lab5/XP_001630613.blastp.detail.filtered.out
  434  cd ~/labs/lab6
  435  awk '{if ($3>=50 &&  $6<0.0000000001)print $1 }' ~/labs/lab5/XP_001630613.blastp.detail.out > ~/labs/lab5/XP_001630613.blastp.detail.filtered.out
  436  cd ~/labs/lab5
  437  awk '{if ($3>=50 &&  $6<0.0000000001)print $1 }' ~/labs/lab5/XP_001630613.blastp.detail.out > ~/labs/lab5/XP_001630613.blastp.detail.filtered.out
  438  cd ~/labs/lab6
  439  ls
  440  git clone https://github.com/Bio312/lab6-jadegiuffre
  441  ls
  442  cd lab6-jadegiuffre
  443  awk '{if ($3>=50 &&  $6<0.0000000001)print $1 }' ~/labs/lab5/XP_001630613.blastp.detail.out > ~/labs/lab5/XP_001630613.blastp.detail.filtered.out
  444  awk '{if ($3>=50 &&  $6<0.0000000001)print $1 }' ~/labs/lab5/lab5-jadegiuffre XP_001630613.blastp.detail.out > ~/labs/lab5/lab5-jadegiuffre/XP_001630613.blastp.detail.filtered.out
  445  pwd
  446  cd ..
  447  cd lab5
  448  pwd
  449  cd ..
  450  pwd
  451  cd lab5
  452  ls
  453  cd lab5-jadegiuffre
  454  ls
  455  cd ..
  456  cd lab6
  457  pwd
  458  cd ..
  459  pwd
  460  cd lab6
  461  awk '{if ($3>=50 &&  $6<0.0000000001)print $1 }'~/labs/lab5/lab5-jadegiuffre/XP_001624893.blastp.detail.out > ~/labs/lab5/lab5-jadegiuffre/XP_001624893.blastp.detail.filtered.out
  462  awk '{if ($3>=50 &&  $6<0.0000000001)print $1 }' ~/labs/lab5/lab5-jadegiuffre/XP_001624893.blastp.detail.out > ~/labs/lab5/lab5-jadegiuffre/XP_001624893.blastp.detail.filtered.out
  463  >Drosophila_melanogaster_Discs_large_5_Q9VKG8
  464  ls -lrt
  465  cd ..
  466  cd/lab5
  467  cd lab5
  468  cd lab5-jadegiuffre
  469  ls -a
  470  ls -lrt
  471  cat XP_001624893.blastp.detail.filtered.i
  472  cat XP_001624893.blastp.detail.filtered.out 
  473  cat XP_001624893.blastp.detail.filtered.out | wc -; 
  474  cat XP_001624893.blastp.detail.filtered.out | wc -l
  475  cat XP_001624893.blastp.detail.out | wc -l
  476  cd ~/tools
  477  git clone git://github.com/tjunier/newick_utils.git
  478  cd newick_utils/
  479  autoreconf -fi
  480  ./configure
  481  make
  482  sudo make install
  483  nw_display -h
  484  cd ~/labs/lab6/lab6-jadegiuffre
  485  echo "((You,your_sister),your_cousin);" > family.tre
  486  nw_display family.tre 
  487  nw_display -s family.tre > family.tre.svg
  488  git add family.tre.svg
  489  git commit -m "created an svg from a newick file" family.tre.svg
  490  git pull --no-edit
  491  git push
  492  echo "(((Echinodermata,Chordata),Arthropoda),Cnidaria);" > phyla.tre
  493  nw_display phyla.tre
  494  nw_reroot phyla.tre Chordata >phyla.reroot.tre  
  495  nw_display phyla.reroot.tre
  496  echo "
  497  q
  498  newtree.tre
  499  nw_display species.tre
  500  echo "(((Homo_sapiens,Strongylocentrotus_purpuratus),Drosophila_melanogster),(Nematostella_vectensis,Pocillopora_damicornis));> species.tre
  501  species.tre
  502  echo "(((Homo_sapiens,Strongylocentrotus_purpuratus),Drosophila_melanogaster),(Nematostella_vectensis,Pocillopora_damicornis)) > species.tre
  503  echo "(((Homo_sapiens,Strongylocentrotus_purpuratus),Drosophila_melanogster),(Nematostella_vectensis,Pocillopora_damicornis));" > species.tre
  504  nw_display species.tre
  505  nw_display -s species.tre > species.tre.svg
  506  git add species.tre.svg
  507  git commit -m "created an svg from a newick file" species.tre.svg
  508  git pull --no-edit
  509  git push
  510  iqtree -s allhomologs.aligned.r50.fa -nt 2
  511  less allhomologs.aligned.r50.fa.iqtree
  512  nw_display allhomologs.aligned.r50.fa.treefile
  513  gotree draw png -w 1000 -i allhomologs.aligned.r50.fa.treefile  -r -o  allhomologs.aligned.r50.fa.png
  514  cd ~/labs/lab7
  515  git clone https://github.com/Bio312/lab7-jadegiuffre
  516  cd lab7-jadegiuffre
  517  cp ~/labs/lab6/lab6-jadegiuffre/family.tre family.tre
  518  ls
  519  iqtree -s XP_001630613.aligned.r50.fa -bb 1000 -nt 2 --prefix XP_001630613.r50.ufboot
  520  nw_reroot XP_001630613.r50.ufboot.treefile Drosophila_melanogaster_Disks_large_1_DLG1_P31007 Nematostella_vectensis_disks_large_homolog_1_XP_001638123.2 Pocillopora_damicornis_A0A3M6TL78 Homo_sapiens_Disks_large_homolog_3_DLG3_Q92796 Homo_sapiens_Disks_large_homolog_4_DLG4_P78352 Homo_sapiens_Disks_large_homolog_1_DLG1_Q12959 Homo_sapiens_Disks_large_homolog_2_DLG2_Q15700 >XP_001630613.r50.ufboot.MendozaRoot.treefile 
  521  nw_display XP_001630613.r50.ufboot.MendozaRoot.treefile 
  522  nw_display -s XP_001630613.r50.ufboot.MendozaRoot.treefile  -w 1000 -b 'opacity:0' > XP_001630613.r50.ufboot.MendozaRoot.svg
  523  java -jar ~/tools/Notung-3.0-beta/Notung-3.0-beta.jar --help 
  524  touch toyspecies.tre
  525  nano toyspecies.tre
  526  touch toygenetree.tre
  527  nano toygenetree.tre
  528  touch toybatch.txt
  529  nano toybatch.txt
  530  less toygenetree.tre
  531  java -jar ~/tools/Notung-3.0-beta/Notung-3.0-beta.jar -b toybatch.txt --reconcile --speciestag prefix --savepng --treestats --events --homologtabletabs --phylogenomics 
  532  less toygenetree.tre.reconciled.png
  533  more toygenetree.tre.reconciled.png
  534  git add .
  535  git pull
  536  git add . 
  537  git pull
  538  git push
  539  git pull --no-edit
  540  git push
  541  git commit
  542  git add . 
  543  git pull --no-edit
  544   git commit -a -m "Adding all new data files I generated in AWS to the repository"
  545  git pull --no-edit
  546  git add .
  547   git commit -a -m "Adding all new data files I generated in AWS to the repository"
  548  git pull --no-edit
  549  git push
  550  sudo yum install numpy
  551  sudo easy_install -U ete3
  552  python ~/tools/recPhyloXML/python/NOTUNGtoRecPhyloXML.py -g toygenetree.tre.reconciled --include.species
  553  git add . 
  554  git commit -a -m "Adding all new data files generated in AWS to the repository"
  555  git pull --no-edit
  556  git push
  557  touch zobatch.txt
  558  nano zobatch.txt
  559  java -jar ~/tools/Notung-3.0-beta/Notung-3.0-beta.jar -b zobatch.txt --reconcile --speciestag prefix  --savepng --treestats --events  --phylogenomics 
  560  git add . 
  561  git commit -a -m "Adding all new data files I generated in AWS to the repository"
  562  git pull --no-edit
  563  git push
  564  python ~/tools/recPhyloXML/python/NOTUNGtoRecPhyloXML.py -g XP_001630613.r50.ufboot.MendozaRoot.treefile.reconciled --include.species
  565  git add . 
  566  git commit -a -m
  567  git add . 
  568  git commit -a -m "Adding all new data files I generated in AWS to the repository"
  569  git pull --no-edit
  570  git push
  571  nw_display  species.tre
  572  column -t -s $'\t' zobatch.txt.species.tre.geneGainLoss.txt | less -S
  573  java -jar ~/tools/Notung-3.0-beta/Notung-3.0-beta.jar -b zobatch.txt --root --speciestag prefix  --savepng --treestats --events  --phylogenomics
  574  iqtree XP_001624893.1.fa -nt -2
  575  iqtree XP_001624893.1.blastp.detail.filtered.out -nt -2
  576  iqtree XP_001624893.blastp.detail.filtered.fas
  577  Adding all new data files I generated in AWS to the repository.
  578  iqtree XP_001624893.blastp.detail.filtered.fas 
  579  cd ~labs/lab5
  580  cd ~/labs/lab5
  581  cd labs/lab5
  582  ls
  583  cd labs/lab5-jadegiuffre
  584  cd lab5-jadegiuffre
  585  ls
  586  t_coffee -other_pg seq_reformat -in XP_001624893.blastp.detail.filtered.aligned.fas -action +rm_gap 50 -out XP_001624893.aligned.r50.fa
  587  grep ">" XP_001624893.aligned.r50.fa 
  588  grep -c ">" XP_001624893.aligned.r50.fa 
  589  cp XP_001624893.aligned.r50.fa ~/labs/lab7/lab7-jadegiuffre
  590  nano XP_0016
  591  nano XP_001624893.aligned.r50.fa 
  592  grep "XP_001624893"  XP_001624893.aligned.r50.fa
  593  grep "XP_001624893"  XP_001624893*
  594  wc -l XP_001624893.1.blastp.detail.filtered.out 
  595  seqkit grep --pattern-file XP_001624893.blastp.detail.filtered.out ~/data/blast/allprotein.fas > XP_001624893.blastp.detail.filtered.fas
  596  muscle -in XP_001624893.blastp.detail.filtered.fas -out XP_001624893.blastp.detail.filtered.aligned.fas
  597  t_coffee -other_pg seq_reformat -in XP_001624893.blastp.detail.filtered.aligned.fas -action +rm_gap 50 -out XP_001624893.aligned.r50.fa
  598  nano XP_001624893.aligned.r50.fa 
  599  grep "XP_001624893" XP_001624893.aligned.r50.fa 
  600  rm XP_001624893.blastp.detail.filtered.fas
  601  rm XP_001624893.blastp.detail.filtered.aligned.fas
  602  rm XP_001624893.aligned.r50.fa 
  603  seqkit grep --pattern-file XP_001624893.blastp.detail.filtered.out ~/data/blast/allprotein.fas > XP_001624893.blastp.detail.filtered.fas
  604  grep "XP_00162" XP_001624893.blastp.detail.filtered.fas 
  605  grep "XP_00162" XP_001624893.blastp.detail.filtered.out 
  606  less XP_001624893.blastp.detail.filtered.out 
  607  grep "XP_0016" XP* 
  608  grep "XP_00162" XP* 
  609  less XP_001624893.1.blastp.detail.filtered.out 
  610  seqkit grep --pattern-file XP_001624893.1.blastp.detail.filtered.out ~/data/blast/allprotein.fas > XP_001624893.blastp.detail.filtered.fas
  611  muscle -in XP_001624893.blastp.detail.filtered.fas -out XP_001624893.blastp.detail.filtered.aligned.fas
  612  t_coffee -other_pg seq_reformat -in XP_001624893.blastp.detail.filtered.aligned.fas -action +rm_gap 50 -out XP_001624893.aligned.r50.fa
  613  grep "XP_001624893"  XP_001624893.aligned.r50.fa
  614  nano XP_001624893.aligned.r50.fa 
  615  cp XP_001624893.aligned.r50.fa ~/labs/lab7/lab7-jadegiuffre
  616  cp XP_001624893.aligned.r50.fa ~/labs/lab6/lab6-jadegiuffre
  617  cd ~/labs/lab6
  618  cd lab6-jadegiuffre
  619  iqtree -s XP_001624893.aligned.r50.fa -nt 2
  620  gotree reroot midpoint -i XP_001624893.aligned.fa.treefile -o XP_001624983.aligned.r50.fa.midpoint.treefile
  621  ls
  622  gotree
  623  gotree reroot midpoint -i XP_001624893.aligned.r50.fa.treefile -o XP_001624893.aligned.r50.fa.midpoint.treefile
  624  cd ~/labs/lab7
  625  cd lab7/lab7jadegiuffre
  626  cd lab7-jadegiuffre
  627  iqtree -s XP_001624893.aligned.r50.fa -bb 1000 -nt 2 --prefix XP_001624893.r50.ufboot
  628  ls
  629  nw_display XP_001624893.r50.ufboot.midpoint.treefile 
  630  nw_display XP_0001624893.r50.midpoint.treefile
  631  XP_001624893.r50.uftboot.treefile
  632  XP_001624893.r50.ufboot.treefile
  633  nw_display XP_001624893.r50.ufboot.MendozaRoot.treefile 
  634  nw_display XP_001624893.r50.ufboot.treefile
  635  cd ~/labs/lab8
  636  git clone https://github.com/Bio312/lab8-jadegiuffre
  637  cp ~/labs/lab7/lab7-jadegiuffre/XP_001630613.r50.ufboot.MendozaRoot.treefile .
  638  ls
  639  cp ~/labs/lab7/lab7-jadegiuffre/XP_001630613.aligned.r50.fa .
  640  ls
  641  cp ~/labs/lab7/lab7-jadegiuffre/XP_001630613.r50.ufboot.treefile .
  642  ls
  643  cp ~/labs/lab7/lab7-jadegiuffre/species.tre 
  644  cp ~/labs/lab7/lab7-yourname/species.tre .
  645  cp ~/labs/lab7/lab7-jadegiuffre/species.tre
  646  ls
  647  cd ~/labs/lab7
  648  ls
  649  cd lab7-jadegiuffre
  650  ls
  651  less species.tre
  652  cd ~/labs/lab8
  653  cd lab8-jadegiuffre
  654  cp ~/labs/lab7/lab7-yourname/species.tre .
  655  cp ~/labs/lab7/lab7-yourname/zobatch.txt .
  656  less species.tre
  657  touch species.tre
  658  nano species.tre
  659  ls
  660  touch zobatch.txt
  661  nano zobatch.txt
  662  ls
  663  cp ~/labs/lab7/lab7-yourname/XP_001630613.r50.ufboot.MendozaRoot.treefile .
  664  nano zobatch.txt
  665  cp ~/labs/lab7/lab7-jadegiuffre/XP_001630613.r50.ufboot.MendozaRoot.treefile .
  666  ls
  667  cp ~/labs/lab7/lab7-jadegiuffre/XP_001630613.aligned.r50.fa .
  668  ls
  669  cp ~/labs/lab7/lab7-jadegiuffre/XP_001630613.r50.ufboot.treefile .
  670  ls
  671  java -jar ~/tools/Notung-3.0-beta/Notung-3.0-beta.jar -b zobatch.txt --rearrange --speciestag prefix  --savepng --treestats --events  --outputdir zoreconcileRearrange --edgeweights name --threshold 90
  672  less zobatch.txt.treeSummary.txt
  673  ls
  674  less zoreconcilRearrange
  675  more zoreconcileRearrange
  676  cd zoreconcileRearrange
  677  less zobatch.txt.treeSummary.txt 
  678  git add .
  679  git commit -a -m "Adding all new data files I generated in AWS to the repository."
  680  git pull --no-edit
  681  git push
  682  python ~/tools/recPhyloXML/python/NOTUNGtoRecPhyloXML.py -g XP_001630613.r50.ufboot.MendozaRoot.treefile.rearrange.0 --include.species
  683  git add .
  684  git commit -a -m "Adding all new data files I generated in AWS to the repository."
  685  git pull --no-edit
  686  git push
  687  cd ../
  688  java -jar ~/tools/Notung-3.0-beta/Notung-3.0-beta.jar -g zoreconcileRearrange/XP_001630613.r50.ufboot.MendozaRoot.treefile.rearrange.0   -s species.tre --reconcile --speciestag prefix  --treeoutput newick --nolosses
  689  gotree unroot -i XP_001630613.r50.ufboot.MendozaRoot.treefile.rearrange.0.reconciled -o XP_001630613.r50.ufboot.unrooted.treefile.rearrange
  690  cat XP_001630613.r50.ufboot.treefile XP_001630613.r50.ufboot.unrooted.treefile.rearrange > XP_001630613.r50.alternativetrees
  691  iqtree -s XP_001630613.aligned.r50.fa -z XP_001630613.r50.alternativetrees -au -zb 10000 --prefix ZO1_altTrees -m LG+F+R5 -nt 2 -te XP_001630613.r50.ufboot.treefile
  692  less ZO1_altTrees.iqtree
  693  cd ~/labs/lab7
  694  cd lab7-jadegiuffre
  695  nw_display XP_001624893.r50.ufboot.treefile
  696  ls
  697  gotree reroot midpoint -i XP_001624893.aligned.r50.fa.treefile -o XP_001624893.aligned.r50.fa.midpoint.treefile
  698  cd ~/labs/lab6
  699  lab6-jadegiuffre
  700  cd lab6-jadegiuffre
  701  ls
  702  cd ~/labs/lab7
  703  cd lab7-jadegiuffre
  704  ls
  705  cp ~/labs/lab6/lab6-jadegiuffre/ XP_001624893.aligned.r50.fa.midpoint.treefile 
  706  ls
  707  nw_display XP_001624893.aligned.r50.fa.midpoint.treefile 
  708  iqtree -s XP_001624893.aligned.r50.fa -bb 1000 -nt 2 --prefix XP_001624893.r50.ufboot
  709  nw_display XP_001624893.r50.ufboot.fa.midpoint.treefile
  710  nw_display XP_001624893.aligned.r50.fa
  711  java -jar ~/tools/Notung-3.0-beta/Notung-3.0-beta.jar -b zobatch.txt --reconcile --speciestag prefix  --savepng --treestats --events  --phylogenomics 
  712  ls
  713  touch locbatch.txt
  714  nano locbatch.txt
  715  java -jar ~/tools/Notung-3.0-beta/Notung-3.0-beta.jar -b locbatch.txt --reconcile --speciestag prefix  --savepng --treestats --events  --phylogenomics
  716  nw_display -s XP_001624893.aligned.r50.fa.midpoint.treefile -w 1000 -b 'opacity:0' > XP_001624893.aligned.r50.fa.midpoint.svg
  717  git add
  718  git add . 
  719  git pull
  720  git add .
  721  git pull
  722  x
  723  git add .
  724  git commit -a -m "Adding all new data files I generated in AWS to the repository."
  725  git pull --noedit
  726  git push
  727  logout
  728  cd ~/labs/lab9
  729  git clone https://github.com/Bio312/lab9-jadegiuffre
  730  cd lab9-jadegiuffre
  731  iprscan5   --email jade.giuffre@stonybrook.edu  --multifasta --useSeqId --sequence   XP_032239066.blastp.detail.filtered.ren.fas
  732  cat *.tsv.txt > maguk.domains.all.tsv
  733  grep Pfam maguk.domains.all.tsv >  maguk.domains.pfam.tsv
  734  awk 'BEGIN{FS="\t"} {print $1"\t"$3"\t"$7"@"$8"@"$5}' maguk.domains.pfam.tsv | datamash -sW --group=1,2 collapse 3 | sed 's/,/\t/g' | sed 's/@/,/g' > maguk.domains.pfam.evol.tsv
  735  git add . 
  736  git commit -a -m "Adding all new data files I generated in AWS to the repository."
  737   git pull --no-edit
  738  git push
  739  cd ~/labs/lab8
  740  ls
  741  pwd
  742  ls -lpwd
  743  cd ..
  744  cd lab9/lab9-jadegiuffre/
  745  pwd 
  746  ls -lrt
  747  cut -f 1 maguk.domains.pfam.tsv | sort | uniq -c
  748  grep Q07157 maguk.domains.pfam.tsv |less -S
  749  grep XP_032239065 maguk.domains.pfam.tsv |less -S
  750  grep XP_032239066 maguk.domains.pfam.tsv |less -S
  751  history > lab9.commandhistory.txt
  752  git add . 
  753  git commit -a -m "Adding all new data files I generated in AWS to the repository."
  754  git pull --no-edit
  755  git push
  756  cd ~/labs/lab10
  757  git clone https://github.com/Bio312/lab10-jadegiuffre
  758  cd lab10-jadegiuffre
  759  fastq-dump SRR9437431
  760  echo SRR9437431.fastq >.gitignore
  761  less -S SRR9437431.fastq
  762  less -S SRR9437431.fastq 
  763  fastq-dump SRR10034524
  764  echo SRR10034524.fastq >>.gitignore
  765  less -S SRR10034524.fastq
  766  sudo yum install -y freetype-devel libpng
  767  curl -O https://bootstrap.pypa.io/get-pip.py
  768  python get-pip.py --user
  769  rm get-pip.py
  770  pip install matplotlib
  771  pip install --upgrade setuptools
  772  pip install quast
  773  quast.py --large  /home/ec2-user/data/refseq/vertebrate_mammalian/GCF_000001405.39/GCF_000001405.39_GRCh38.p13_genomic.fna    --min-contig 0 --threads 2
  774  quast.py --large  /home/ec2-user/data/refseq/invertebrate/GCF_000209225.1/GCF_000209225.1_ASM20922v1_genomic.fna    --min-contig 0 --threads 2
  775  less report.txt
  776  cd ~quast_results
  777  cd labs/lab10/lab10-jadegiuffre/quast_results/results_2020_10_29_23_27_50
  778  ls
  779  cd quast_results
  780  ls
  781  less report.txt
  782  cd results_2020_10_29_23_14_26
  783  less report.txt
  784  cd quast_results
  785  cd ~labs/lab10
  786  cd ~/labs/lab10
  787  cd quast_results
  788  git clone https://github.com/Bio312/lab10-jadegiuffre
  789  cd lab10-jadegiuffre
  790  ls
  791  cd quast_results
  792  cd results_2020_10_29_23_27_50
  793  less report.txt
  794  cd lab10-jadegiuffre
  795  cd ~labs/lab10
  796  cd ~/labs/lab10
  797  cd lab10-jadegiuffre
  798  cd quast_results
  799  cd results_2020_10_29_23_14_26 
  800  less report.txt
  801  cd ~/labs/lab10
  802  cd lab10-jadegiuffre
  803  cd quast_results
  804  cd results_2020_10_29_23_14_26
  805  less report.txt
  806  cd ~/labs/lab10
  807  cd lab10-jadegiuffre
  808  cd quast_results 
  809  cd results_2020_10_29_23_27_50
  810  less report.txt
  811  cd ~/labs/lab10
  812  cd lab10-jadegiuffre
  813  cd quast_results
  814  cd results_2020_10_29_23_14_26
  815  less report.txt
  816  cd ~/labs/lab10
  817  cd lab10-jadegiuffre
  818  cd quast_results
  819  cd results_2020_10_29_23_27_50
  820  less report.txt
  821  cd ~/labs/lab10
  822  cd lab10-jadegiuffre
  823  cd quast_results
  824  cd results_2020_10_29_23_14_26
  825  less report.txt
  826  cd ~/labs/lab10
  827  cd lab10-jadegiuffre
  828  cd quast_results
  829  cd results_2020_10_29_23_27_50
  830  less report.txt
  831  cd ~/labs/lab10
  832  cd lab10-jadegiuffre
  833  cd quast_results
  834  cd results_2020_10_29_23_14_26
  835  less report.txt
  836  cd ~/labs/lab10
  837  cd lab10-jadegiuffre
  838  cd quast_results
  839  cd results_2020_10_29_23_2
  840  cd results_2020_10_29_23_27_50
  841  less report.txt
  842   history > lab10.commandhistory.txt
  843  git add .
  844  git commit -a -m "Adding all new data files I generated in AWS to the repository."
  845  git pull --no-edit
  846  git push
  847  cd ~/labs/lab10
  848  cd lab10-jadegiuffre
  849  ls
  850  cd quast_results
  851  ls
  852  git add .
  853  git commit -a -m "Adding all new data files I generated in AWS to the repository."
  854   git pull --no-edit
  855  git push
  856  cd ~/labs/lab6
  857  awk '{if ($3>=50 &&  $6<0.0000000001)print $1 }' ~/labs/lab5/XP_001624893.blastp.detail.out > ~/labs/lab5/XP_001624893.blastp.detail.filtered.out
  858  Adding all new data files I generated in AWS to the repository.
  859  cd ~/labs/lab5
  860  ls
  861  cd lab5-jadegiuffre
  862  ls
  863  cd ~/labs/lab6
  864  awk '{if ($3>=50 &&  $6<0.0000000001)print $1 }' ~/labs/lab5/lab5-jadegiuffre/XP_001624893.blastp.detail.out > ~/labs/lab5/lab5-jadegiuffre/XP_001624893.blastp.detail.filtered.out
  865  cd ~/labs/lab5
  866  cd lab5-jadegiuffre
  867  ls
  868  cd ~/labs/lab6
  869  iqtree -s XP_001624893.aligned.r50.fa -nt 2
  870  git clone https://github.com/Bio312/lab5-jadegiuffre
  871  cd ~/labs/lab5
  872  cd lab5-jadegiuffre
  873  iqtree -s XP_001624893.aligned.r50.fa -nt 2
  874   history > lab5.commandhistory.txt
  875   git add .
  876  git commit -a -m "Adding all new data files I generated in AWS to the repository."
  877  git pull --no-edit
  878  git add . 
  879  git commit -a -m "Adding all new data files I generated in AWS to the repository."
  880  git add .
  881  git commit -a -m "Adding all new data files I generated in AWS to the repository."
  882  history > lab5.commandhistory.txt
  883  git add .
  884  git commit -a -m "Adding all new data files I generated in AWS to the repository."
  885  git pull --no-edit
  886  git push
  887  cd ~/labs/lab6
  888  iqtree -s XP_001624893.aligned.r50.fa -nt 2
  889  ls
  890  lab6-jadegiuffre
  891  cd lab6-jadegiuffre
  892  ls
  893  less XP_001624893.aligned.r50.fa.iqtree
  894  w_display -s  XP_0016244983.aligned.r50.fa.midpoint.treefile -w 1000 -b 'opacity:0' >  XP_001624983.aligned.r50.fa.midpoint.svg
  895  nw_display -s  XP_001624983.aligned.r50.fa.midpoint.treefile -w 1000 -b 'opacity:0' >  XP_001624983.aligned.r50.fa.midpoint.svg
  896  ls
  897   history > lab6.commandhistory.txt
  898  git add . 
  899  git commit -a -m "Adding all new data files I generated in AWS to the repository."
  900  git pull --no-edit
  901  git push
  902  echo "((((Pocillopora_damicornis_Uncharacterized_protein_A0A3M6UJT7:0.2444293289,(Nematostella_vectensis_XP_001624893.1:0.0000010122,Nematostella_vectensis_XP_032230419.1:0.042941378):0.1929581421):0.3810823709,(Drosophila_melanogaster_Transcription_elongation_factor_S-II_P20232|TFS2:0.1804339959,Drosophila_melanogaster_IP08861p_Q9VXS6:0.4926627488):0.3272498461):0.0543396174,(Strongylocentrotus_purpuratus_TFIIS_central_domain-containing_protein_W4YXG1:0.8878284099,((Homo_sapiens_Transcription_elongation_factor_A_protein_3_O75764_TCEA3:0.4213513294,Homo_sapiens_Transcription_elongation_factor_A_protein_2_Q15560_TCEA2:0.2313677705):0.1063284891,Homo_sapiens_Transcription_elongation_factor_A_protein_1_P23193_TCEA1:0.2485173314):0.1386784324):0.0372990563):0.59127114595,Homo_sapiens_Transcription_elongation_factor_A_N-terminal_Central_domain_containing_protein_TEANC_Q8N8B7:1.5163986121500002);"
  903  species.tre
  904  q
  905  cq
  906  q
  907  "
  908  echo "((((Pocillopora_damicornis_Uncharacterized_protein_A0A3M6UJT7:0.2444293289,(Nematostella_vectensis_XP_001624893.1:0.0000010122,Nematostella_vectensis_XP_032230419.1:0.042941378):0.1929581421):0.3810823709,(Drosophila_melanogaster_Transcription_elongation_factor_S-II_P20232|TFS2:0.1804339959,Drosophila_melanogaster_IP08861p_Q9VXS6:0.4926627488):0.3272498461):0.0543396174,(Strongylocentrotus_purpuratus_TFIIS_central_domain-containing_protein_W4YXG1:0.8878284099,((Homo_sapiens_Transcription_elongation_factor_A_protein_3_O75764_TCEA3:0.4213513294,Homo_sapiens_Transcription_elongation_factor_A_protein_2_Q15560_TCEA2:0.2313677705):0.1063284891,Homo_sapiens_Transcription_elongation_factor_A_protein_1_P23193_TCEA1:0.2485173314):0.1386784324):0.0372990563):0.59127114595,Homo_sapiens_Transcription_elongation_factor_A_N-terminal_Central_domain_containing_protein_TEANC_Q8N8B7:1.5163986121500002); "
  909  echo ((((Pocillopora_damicornis_Uncharacterized_protein_A0A3M6UJT7:0.2444293289,(Nematostella_vectensis_XP_001624893.1:0.0000010122,Nematostella_vectensis_XP_032230419.1:0.042941378):0.1929581421):0.3810823709,(Drosophila_melanogaster_Transcription_elongation_factor_S-II_P20232|TFS2:0.1804339959,Drosophila_melanogaster_IP08861p_Q9VXS6:0.4926627488):0.3272498461):0.0543396174,(Strongylocentrotus_purpuratus_TFIIS_central_domain-containing_protein_W4YXG1:0.8878284099,((Homo_sapiens_Transcription_elongation_factor_A_protein_3_O75764_TCEA3:0.4213513294,Homo_sapiens_Transcription_elongation_factor_A_protein_2_Q15560_TCEA2:0.2313677705):0.1063284891,Homo_sapiens_Transcription_elongation_factor_A_protein_1_P23193_TCEA1:0.2485173314):0.1386784324):0.0372990563):0.59127114595,Homo_sapiens_Transcription_elongation_factor_A_N-terminal_Central_domain_containing_protein_TEANC_Q8N8B7:1.5163986121500002);
  910  ls
  911  less XP_0016244983.aligned.r50.fa.midpoint.svg
  912  less  XP_001624983.aligned.r50.fa.midpoint.svg
  913  gotree reroot midpoint -i XP_0016244983.aligned.r50.fa.treefile -o XP_001624983.aligned.r50.fa.midpoint.treefile
  914  gotree reroot midpoint -i XP_001624983.aligned.r50.fa.treefile -o XP_001624983.aligned.r50.fa.midpoint.treefile
  915  echo ";" > family.tre
  916  "((((Pocillopora_damicornis_Uncharacterized_protein_A0A3M6UJT7:0.2444293289,(Nematostella_vectensis_XP_001624893.1:0.0000010122,Nematostella_vectensis_XP_032230419.1:0.042941378):0.1929581421):0.3810823709,(Drosophila_melanogaster_Transcription_elongation_factor_S-II_P20232|TFS2:0.1804339959,Drosophila_melanogaster_IP08861p_Q9VXS6:0.4926627488):0.3272498461):0.0543396174,(Strongylocentrotus_purpuratus_TFIIS_central_domain-containing_protein_W4YXG1:0.8878284099,((Homo_sapiens_Transcription_elongation_factor_A_protein_3_O75764_TCEA3:0.4213513294,Homo_sapiens_Transcription_elongation_factor_A_protein_2_Q15560_TCEA2:0.2313677705):0.1063284891,Homo_sapiens_Transcription_elongation_factor_A_protein_1_P23193_TCEA1:0.2485173314):0.1386784324):0.0372990563):0.59127114595,Homo_sapiens_Transcription_elongation_factor_A_N-terminal_Central_domain_containing_protein_TEANC_Q8N8B7:1.5163986121500002);" > species.tre
  917  nw_display -s XP_001624893.aligned.r50.fa.midpoint.treefile -w 1000 -b 'opacity:0' >  XP_001624983.aligned.r50.fa.midpoint.svg
  918  less XP_001624983.aligned.r50.fa.midpoint.svg
  919  ls
  920  git add .
  921   history > lab6.commandhistory.txt
  922  git add .
  923  git commit -a -m "Adding all new data files I generated in AWS to the repository."
  924  git pull --no-edit
  925  git push
  926  cd labs/lab7
  927  cd ~/labs/lab7
  928  cd lab7-jadegiuffre
  929  cp ~/labs/lab6/lab6-jadegiuffre/XP_001624893.aligned.r50.fa.midpoint.treefile .
  930  cp ~/labs/lab6/lab6-jadegiuffre/XP_001624893.aligned.r50.fa
  931  cp ~/labs/lab6/lab6-jadegiuffre/XP_001624893.aligned.r50.fa .
  932  ls
  933  history > lab7.commandhistory.txt
  934  git add .
  935  git commit -a -m "Adding all new data files I generated in AWS to the repository."
  936  git pull --no-edit
  937  git push
  938  cd ~/labs/lab11
  939  git clone https://github.com/Bio312/lab11-yourname 
  940  git clone https://github.com/Bio312/lab11-jadegiuffre
  941  cd lab11-jadegiuffre
  942  fastq-dump SRR1297272  --gzip
  943  fastq-dump SRR1297273 --gzip
  944  fastq-dump SRR1297281 --gzip
  945  fastq-dump SRR1297282 --gzip
  946  less SRR1297281.fastq.gz
  947  ~/tools/FastQC/fastqc SRR1297281.fastq.gz
  948  sudo service httpd start
  949  sudo cp SRR1297281_fastqc.html /var/www/html/SRR1297281_fastqc.html
  950  dig +short myip.opendns.com @resolver1.opendns.com
  951   ~/tools/FastQC/fastqc SRR1297281.fastq.gz
  952   sudo service httpd start
  953   sudo cp SRR1297281_fastqc.html /var/www/html/SRR1297281_fastqc.html
  954  cd ~/labs/lab11
  955  cd lab11-jadegiuffre
  956  ~/tools/FastQC/fastqc SRR1297281.fastq.gz
  957  sudo service httpd start
  958  sudo cp SRR1297281_fastqc.html /var/www/html/SRR1297281_fastqc.html
  959  java -jar ~/tools/Trimmomatic-0.39/trimmomatic-0.39.jar SE -phred33 SRR1297281.fastq.gz SRR1297281.trimmed.fastq.gz LEADING:3 TRAILING:3 SLIDINGWINDOW:4:15 MINLEN:36
  960  sudo service httpd start
  961  sudo cp SRR1297281_fastqc.html /var/www/html/SRR1297281_fastqc.html
  962  dig +short myip.opendns.com @resolver1.opendns.com
  963  ls -lrt
  964  pwd
  965  java -jar ~/tools/Trimmomatic-0.39/trimmomatic-0.39.jar SE -phred33 SRR1297282.fastq.gz SRR1297282.trimmed.fastq.gz LEADING:3 TRAILING:3 SLIDINGWINDOW:4:15 MINLEN:36
  966  java -jar ~/tools/Trimmomatic-0.39/trimmomatic-0.39.jar SE -phred33 SRR1297272.fastq.gz SRR1297272.trimmed.fastq.gz LEADING:3 TRAILING:3 SLIDINGWINDOW:4:15 MINLEN:36
  967  java -jar ~/tools/Trimmomatic-0.39/trimmomatic-0.39.jar SE -phred33 SRR1297273.fastq.gz SRR1297273.trimmed.fastq.gz LEADING:3 TRAILING:3 SLIDINGWINDOW:4:15 MINLEN:36
  968  ls ~/data/refseq/invertebrate/GCF_000209225.1/
  969  cd data
  970  cd ~/data
  971  ncbi-genome-download -F gff -T 45351 invertebrate
  972  ncbi-genome-download -F fasta -T 45351 invertebrate
  973    gunzip GCF_000209225.1_ASM20922v1_genomic.fna.gz
  974  gunzip GCF_000209225.1_ASM20922v1_genomic.fna.gz
  975  cd ~//home/ec2-user/data/refseq/invertebrate/GCF_000209225.1/
  976  cd~/home/ec2-user/data/refseq/invertebrate/GCF_000209225.1/
  977  pwd
  978  cd refseq
  979  cd invertebrate
  980  cd GCF_000209225.
  981  ls
  982  less GCF_000209225.1
  983  cd GCF_000209225.1
  984  gunzip GCF_000209225.1_ASM20922v1_genomic.fna.gz
  985  gunzip GCF_000209225.1_ASM20922v1_genomic.gff.gz
  986  ls ~/data/refseq/invertebrate/GCF_000209225.1/
  987  cd MD5SUMS
  988  less MD5SUMS
  989  ls ~/data/refseq/invertebrate/GCF_000209225.1/
  990  cd ~/labs/lab11
  991  cd lab11-jadegiuffre
  992  hisat2-build ~/data/refseq/invertebrate/GCF_000209225.1/GCF_000209225.1_ASM20922v1_genomic.fna nemat_genome_index
  993  hisat2  -U SRR1297281.trimmed.fastq.gz -S SRR1297281.sam -x nemat_genome_index  -p 2
  994  hisat2  -U SRR1297282.trimmed.fastq.gz -S SRR1297282.sam -x nemat_genome_index  -p 2
  995  hisat2  -U SRR1297272.trimmed.fastq.gz -S SRR1297272.sam -x nemat_genome_index  -p 2
  996  hisat2  -U SRR1297273.trimmed.fastq.gz -S SRR1297273.sam -x nemat_genome_index  -p 2
  997  cd ~/labs/lab11
  998  lab11-jadegiuffre
  999  cd lab11-jadegiuffre
 1000  history > lab11.commandhistory.txt
 1001  git add .
 1002  git commit -a -m "Adding all new data files I generated in AWS to the repository."
 1003  git pull --no-edit
 1004  git push
 1005  cd ~/labs/lab8
 1006  cd lab8-jadegiuffre
 1007  java -jar ~/tools/Notung-3.0-beta/Notung-3.0-beta.jar -b locbatch.txt --rearrange --speciestag prefix  --savepng --treestats --events  --outputdir zoreconcileRearrange --edgeweights name --threshold 90 
 1008  ls
 1009  cp ~/labs/lab7/lab7-jadegiuffre/locbatch.txt 
 1010  cp ~/labs/lab7/lab7-jadegiuffre/loc.tre
 1011  cp --help
 1012  cp ~/labs/lab7/lab7-yourname/XP_001624893.aligned.r50.fa 
 1013  cp ~/labs/lab7/lab7-jadegiuffre/XP_001624893.aligned.r50.fa 
 1014  cp ~/labs/lab7/lab7-jadegiuffre/XP_001624893.aligned.r50.fa/labs/lab8/lab8-jadegiuffre
 1015    history > lab8.commandhistory.txt
 1016  git add . 
 1017  git commit -a -m "Adding all new data files I generated in AWS to the repository."
 1018  git pull --noedit
 1019  git push
 1020  ls
 1021  cd zoreconcileRearrange
 1022  ls
 1023  cd ~/labs/lab8
 1024  ls
 1025  cd lab8-jadegiuffre
 1026  ls
 1027  cp ~/labs/lab7/lab7-jadegiuffre/zobatch.txt .
 1028  cp cp ~/labs/lab7/lab7-jadegiuffre/locbatch.txt .
 1029  cp ~/labs/lab7/lab7-jadegiuffre/XP_001624893.aligned.r50.fa .
 1030  ls
 1031  java -jar ~/tools/Notung-3.0-beta/Notung-3.0-beta.jar -b locbatch.txt --rearrange --speciestag prefix  --savepng --treestats --events  --outputdir locreconcileRearrange --edgeweights name --threshold 90 
 1032  cp ~/labs/lab7/lab7-jadegiuffre/loc.tre .
 1033  nano loc.tre
 1034  java -jar ~/tools/Notung-3.0-beta/Notung-3.0-beta.jar -b locbatch.txt --rearrange --speciestag prefix  --savepng --treestats --events  --outputdir locreconcileRearrange --edgeweights name --threshold 90 
 1035  nano loc.tre
 1036  java -jar ~/tools/Notung-3.0-beta/Notung-3.0-beta.jar -b locbatch.txt --rearrange --speciestag prefix  --savepng --treestats --events  --outputdir locreconcileRearrange --edgeweights name --threshold 90 
 1037  nano loc.tre
 1038  java -jar ~/tools/Notung-3.0-beta/Notung-3.0-beta.jar -b locbatch.txt --rearrange --speciestag prefix  --savepng --treestats --events  --outputdir locreconcileRearrange --edgeweights name --threshold 90 
 1039  nano loc.tre
 1040  java -jar ~/tools/Notung-3.0-beta/Notung-3.0-beta.jar -b locbatch.txt --rearrange --speciestag prefix  --savepng --treestats --events  --outputdir locreconcileRearrange --edgeweights name --threshold 90 
 1041  loc.tre
 1042  nano loc.tre
 1043  java -jar ~/tools/Notung-3.0-beta/Notung-3.0-beta.jar -b locbatch.txt --rearrange --speciestag prefix  --savepng --treestats --events  --outputdir locreconcileRearrange --edgeweights name --threshold 90 
 1044  nano loc.tre
 1045  java -jar ~/tools/Notung-3.0-beta/Notung-3.0-beta.jar -b locbatch.txt --rearrange --speciestag prefix  --savepng --treestats --events  --outputdir locreconcileRearrange --edgeweights name --threshold 90 
 1046  java -jar ~/tools/Notung-3.0-beta/Notung-3.0-beta.jar -b loc.tre --rearrange --speciestag prefix  --savepng --treestats --events  --outputdir locreconcileRearrange --edgeweights name --threshold 90 
 1047  cd ~/labs/lab7
 1048  cd lab7-jadegiuffre
 1049  ls
 1050  nw_display XP_001624893.r50.aligned.r50.fa.midpoint.treefile
 1051  nw_display  XP_001624893.aligned.r50.fa.midpoint.treefile
 1052  nw_display locbatch.tre
 1053  iqtree -s XP_001624893.aligned.r50.fa -bb 1000 -nt 2 --prefix XP_001624893.r50.ufboot
 1054  less XP_001624893.r50.ufboot.ckp.gz 
 1055  cd ~/labs/lab6
 1056  cd lab6-jadegiuffre
 1057  ls
 1058  nw_display XP_001624893.aligned.r50.fa.treefile
 1059  gotree draw png -w 1000 -i XP_001624893.aligned.r50.fa.treefile  -r -o  XP_001624893.aligned.r50.fa.png
 1060  ls

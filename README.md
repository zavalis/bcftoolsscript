# bcftoolsscript
`cd /to/folder`
Check it `for f in *.vcf;  bcftools query -f '%CHROM\t%POS\t%REF\t%ALT[\t%ID]\n' "$f" > ${f%.*}.txt done`

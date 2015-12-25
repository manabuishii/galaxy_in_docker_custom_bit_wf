# galaxy_in_docker_custom_bit_wf

## Quick start

Just create 3 directories that are empty.

```
mkdir -p data/transcriptome_ref_fasta
mkdir -p data/adapter_primer
mkdir export
```

docker run

```
docker run -d -p 10500:80 --privileged=true -v $PWD/export:/export -v $PWD/data:/data/ myoshimura
080822/galaxy_in_docker_bitwf:151224
```
